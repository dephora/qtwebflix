# qtwebflix
A qt webengine program that I use for netflix

<b>Now available in the AUR</b>
<html>https://aur.archlinux.org/packages/qtwebflix-git/<html>



<b>Requirements-</b> qt5,qtwebegine(with proprietary codecs)
You must compile qtwebengine with proprietary codecs.

Read this <html>http://blog.qt.io/blog/2016/06/03/netflix-qt-webengine-5-7/</html>

Instructions:
  1. Install qt5
  2. Compile qtwebengine according to the link above
  3. Dowload the source
  4. cd into the folder
  5. Type make clean
  6. Type qmake -config release
  7. Type make
  8. Binary will be labeled netflix
  9. Enjoy a standalone netflix player :) f11 for fullscreen and crtl + q to quit
    
  

