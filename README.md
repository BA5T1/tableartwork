# Tableartwork
blender renders previewtable from texture.png
you don't need any blender skills

![Pirates_Life_Original_2024](https://github.com/user-attachments/assets/f491e20f-9c20-414a-876b-b10cfcd3f8a9)

How does it work?

1) create new table-texture with table_preview_template.png
2) place this your-texture.png in /Textures
3) edit "newtables.csv" matching your new texture:
   - your-texture (without extension)
   - set dmd 1 or 0 (dmd/solidstate)
4) in blender open script-tab
5) execute script (play icon)

New rendered [tablename][manufactor].png will be stored in /RenderedImages

> [!NOTE]
> You can add multiple tables at once.
