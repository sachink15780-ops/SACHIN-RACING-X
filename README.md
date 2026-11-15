# SACHIN RACING X

A mobile-first 3D racing game prototype powered by Three.js.

## Play locally
Open `index.html` in a modern browser with an internet connection. The game loads Three.js and PeerJS from public CDNs.

## Controls
- Mobile: hold the left/right arrows to steer; hold the blue accelerator to speed up; use the red brake to slow down.
- Desktop: arrow keys or WASD.

## Online room prototype
Choose Multiplayer → Create Online Room, then share the generated room code. Another player can enter that code and join. This uses PeerJS peer-to-peer data channels and depends on public signaling/STUN connectivity. It is a prototype, not a production matchmaking service. A production release still needs a maintained signaling service, authoritative server, anti-cheat and device/network testing.

## Publish on GitHub Pages
Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then Save. After GitHub finishes deploying, the game will be available at:

`https://sachink15780-ops.github.io/SACHIN-RACING-X/`
