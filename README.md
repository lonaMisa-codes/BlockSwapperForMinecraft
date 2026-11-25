# Block Swapper for Minecraft

Open a Litematica `.litematic` schematic in 3D, fly around it, select individual blocks, replace them, and save a new file. Everything runs in the browser; nothing is uploaded.

## Use it

Open the GitHub Pages site for this repo (Settings → Pages → deploy from `main`, root folder), or open `index.html` in a browser.

## Real Minecraft textures

The page draws its own vanilla-style textures (Classic and Bare). For the real look, open the **View** tab and press **Get the real Minecraft textures**. It downloads the game's textures once, from Mojang's servers (or a public mirror of the same files if the browser blocks that), and keeps them in your browser.

You can also load a resource pack `.zip` or the Minecraft Java `.jar` from your device. To make a pack the default for everyone who opens your site, press **Download pack.zip for GitHub**, put the file next to `index.html` and commit it. Minecraft's textures belong to Mojang, so only do that if you are comfortable publishing them.

A pack saved on a device (the "Remember it on this device" option) takes priority over `pack.zip` on that device.
