# Tableartwork
blender renders previewtable from texture.png<br>
you don't need any blender skills

<table><tr><td><img src="https://github.com/BA5T1/tableartwork/blob/main/table_preview_template.png" alt="" width="300"></td><td><img src="https://github.com/user-attachments/assets/0b3650be-43ee-4de6-9dbd-9af9bf176c76" alt="" width="300"></td></tr></table>



![Pirates_Life_Original_2024](https://github.com/user-attachments/assets/f491e20f-9c20-414a-876b-b10cfcd3f8a9)


How does it work?!

1a) create new table-texture with table_preview_template.png
OR
1b) export artwork with 
2) place this your-texture.png in /Textures
3) edit "newtables.csv" matching your new texture:
   - name: e.g. Terminator 2
   - manufactor: e.g. Williams 1977
   - image: your-texture (filename without path and extension)
   - dmd: 1 or 0 (dmd/solidstate)
   - other fields are ignored (leave them empty)
5) install blender (once)
6) open blender file / in blender open script-tab
7) execute script (play icon)

New rendered "[tablename] [manufactor].png" will be stored in /RenderedImages

> [!NOTE]
> You can add multiple tables at once.
