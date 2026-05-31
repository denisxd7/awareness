# Nightcord is actually malware

Version 1.18.2 of Nightcord contained a TokenLogger

Never lose your Discord token ever again, thanks to Nightcord's :sparkles: **PREMIUM SYNC** :sparkles: services!
This code found in v1.18.2 uploads your Discord token to Nightcord's Server. 
<img width="2012" height="900" alt="image" src="https://raw.githubusercontent.com/denisxd7/awareness/refs/heads/main/Nighcord/599065820-8d9536b7-e5e5-4692-abd5-9007b8f22ef9.png" />

<details>
  <summary>How to verify this is real</summary>
  
  - Download `nightcord-dist.zip` from here: https://github.com/disbored/archival-nightcord-releases/releases/v1.18.2-releases
  - This is a mirror because Nightcord loves deleting evidence.
  - You can verify this is the real build by comparing its hash to the hash listed here: https://web.archive.org/web/20260527210411/https://github.com/nightcordoff/nightcordclient-releases/releases/tag/v1.18.2
  - Once downloaded, open `renderer.js` with any text editor and search for x-discord-token
</details>

This code seems to no longer be present in new releases, however
- Do you really want to trust Developers who pushed a token logger once? They will definitely do it again at some point
- Nightcord is extremely suspicious & dangerous for many other reasons

## What makes Nightcord very suspicious even if you ignore the TokenLogger

- Its download is an entire gigabyte because it contains large binaries. This makes no sense whatsoever and is impossible to verify. There's a high likelihood of something nasty being hidden in one of these binaries.
- Its download also includes Discord binaries, which is Copyright infringement (illegal)
- For the longest time, Nightcord did not share their source code. This infringes on both Vencord's and Equicord's Copyright and is also illegal
- Even now that they published source code, all of Vencord's and Equicord's [change history](https://github.com/Vendicated/Vencord/commits/main/) was stripped out, which makes it hard to verify changes.
  It also has questionable legality due to removing attribution. Every line of code in Vencord is owned by whoever wrote it (that's over 200 people in total!). Removing history makes it impossible to tell who wrote what.
- Their developers are skids and have absolutely no idea what they're doing. All Nightcord code seems to be AI-generated, is of horrible quality and uses practices that worsen security and even risk your Discord Account.
- As of today, one of the main developers of Nightcord was flagged for fraud/spam by Discord. Is this really who you want to be trusting?
  <img width="1422" height="684" alt="image" src="https://gist.github.com/user-attachments/assets/000c33ca-9b07-48e8-90b4-ac3c5ce846d5" />

  Credits to [Vendicated](https://gist.github.com/Vendicated)
