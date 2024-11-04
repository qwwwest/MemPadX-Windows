# MemPadX Portable (for Windows)

For more information see the main project:
 https://github.com/qwwwest/mempadx

This version here in Windows only.
It is portable, so you do not need to install it, nor to have Python installed on Windows.
You download the zip file, you unzip it, and **MemPadX** works out of the box.


**MemPadX** is a plain text outliner and note taking program with a tree structured index. 
All pages are stored in a single file.

 ![MemPadX](mempadx.jpg)

It is a port in Python of **MemPad**, a Windows program made by [Horst Schaeffer](https://horstmuc.de/wmem.htm). I have been using Mempad for 20 years, but I am using Linux more and more and I *really*  wanted to use MemPad in Linux. Unfortunately the program  failed to work in Wine, so i decided to bring it to Linux, MacOS, and more with a version written in python _from scratch_. I did not use the windows source code. I only read how worked the binary Mempad File Format.

Also, my purpose is not to make a clone of MemPad for Windows. I want more. For example, I added the possibility to display a subset of Markdown: titles, bold, italics links are displayed as you type.
 
This file was generated with PyInstaller:
python -m PyInstaller --distpath ../winapp/dist --workpath  ../winapp/build --name MempadX --noconsole --onedir --collect-all tkinterdnd2  --add-data "ressources/*.png;./ressources" --add-data "views/themes/Forest-ttk-theme/*.tcl;./views/themes/Forest-ttk-theme" --add-data "views/themes/Forest-ttk-theme/forest-light/*.png;./views/themes/Forest-ttk-theme/forest-light" --add-data "views/themes/Forest-ttk-theme/forest-dark/*.png;./views/themes/Forest-ttk-theme/forest-dark" main.py
 