# MemPadX Portable (for Windows)

For more information see the main project:
 https://github.com/qwwwest/mempadx

This version here in Windows only.
It is portable and you do not need to have Python installed on Windows.
You download the zip, you unzip, and it works.


**MemPadX** is a plain text outliner and note taking program with a tree structured index. All pages are stored in a single file.

 ![MemPadX](mempadx.jpg)

 
This file was generated with PyInstaller:
python -m PyInstaller --distpath ../winapp/dist --workpath  ../winapp/build --name MempadX --noconsole --onedir --collect-all tkinterdnd2  --add-data "ressources/*.png;./ressources" --add-data "views/themes/Forest-ttk-theme/*.tcl;./views/themes/Forest-ttk-theme" --add-data "views/themes/Forest-ttk-theme/forest-light/*.png;./views/themes/Forest-ttk-theme/forest-light" --add-data "views/themes/Forest-ttk-theme/forest-dark/*.png;./views/themes/Forest-ttk-theme/forest-dark" main.py
 