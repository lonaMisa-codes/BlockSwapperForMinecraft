# Block Swapper for Minecraft

Open a Litematica `.litematic` schematic in 3D, fly around it, select individual blocks, replace them, and save a new file. Everything runs in the browser; nothing is uploaded.

## Use it

Open the GitHub Pages site for this repo (Settings → Pages → deploy from `main`, root folder), or open `index.html` in a browser.

## Real Minecraft textures

The page draws its own vanilla-style textures (Classic and Bare). For the real look, load a resource pack:

1. In the app, open the **View** tab → **Load a texture pack…** and pick a resource pack `.zip` (for example Faithful or Bare Bones) or the Minecraft Java `.jar` (`.minecraft/versions/<version>/<version>.jar`).
2. Press **Download pack.zip for GitHub**. It is a small copy with only the block textures.
3. Put `pack.zip` in this folder, next to `index.html`, and commit it. The page loads it automatically.

A pack saved on a device (the "Remember it on this device" option) takes priority over `pack.zip` on that device.
