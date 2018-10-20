# ProcessingPrinters
How to use real printer with Processing :

 - Install IrfanView on your computer.
 - Go to your C:/Program Files (x83)/IrfanView/ Foler, and create a link of the i_view32.exe application
 - Copy the link in your sketch Data folder.
 - Copy and modify the line to print what you want :

Line for processing sketch :

launch(dataPath("i_view32.lnk"),dataPath("exemple.jpg"),"/print");
