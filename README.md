# MONOJOG-Plus
Live Link: https://abida3564.github.io/MONOJOG-Plus/

Guidance

•  Step 1: Turn on the ESP32 and NeuroSky headset. Confirm ESP32 IP is 192.168.1.104 via Serial Monitor. 

•  Step 2: Open CMD or PowerShell and start Cloudflare Tunnel:
DOS

cd C:\tools

cloudflared.exe tunnel --edge-ip-version 4 --protocol http2 --url http://192.168.1.104

•  Step 3: Copy the generated [https://xxxx.trycloudflare.com](https://xxxx.trycloudflare.com) URL (keep the terminal window open).

•  Step 4: Open your GitHub Pages( https://abida3564.github.io/MONOJOG-Plus/ ) dashboard (index.html), paste the URL into Data Source URL, and click Connect.

•  Step 5: Verify the badge shows Live • signal valid. Enter profile info and click Apply Profile.

•  Step 6: Click Launch Game, pick a game, and remain still for 15 pre-game baseline samples. 

•  Step 7: Play normally, then click Finish & Compare and sit still for 15 post-game samples to view before/after EEG results. 

cloudflared.exe tunnel --edge-ip-version 4 --protocol http2 --url http://192.168.1.104

cloudflared.exe tunnel --edge-ip-version 4 --protocol http2 --url 10.204.24.18

cloudflared.exe tunnel --edge-ip-version 4 --protocol http2 --url https://10.204.24.18

