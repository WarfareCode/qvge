## Qt Visual Graph Editor  [![Download qvge](https://img.shields.io/sourceforge/dm/qvge.svg)](https://sourceforge.net/projects/qvge/files)

qvge is a multiplatform graph editor written in C++/Qt. Its main goal is to make possible visually edit two-dimensional graphs
in a simple and intuitive way.

Please note that qvge is not a replacement for such a software like Gephi, Graphvis, Dot, yEd, Dia and so on. It is neither a tool for "big data analysis" nor a math application. It is really just a simple graph editor :)

![Screenshot1](https://a.fsdn.com/con/app/proj/qvge/screenshots/qvge%20screenshot.PNG/245/183/2)
![Screenshot2](https://a.fsdn.com/con/app/proj/qvge/screenshots/qvge%20screenshot%202.PNG/245/183/2)

### Main Features

- Easy creation and parametrising of small-sized till middle-sized graphs
- Dynamically maintained list of commutations between nodes
- Directed, undirected and mixed graphs supported
- Loading GraphML and GEXF files (as well as native XGR format)
- Export into PDF and popular image formats

### Installation

Prebuild Windows binaries can be loaded here:

[![Download qvge](https://a.fsdn.com/con/app/sf-download-button)](https://sourceforge.net/projects/qvge/files)

Or you can get qvge's sources and build them by yourself. In this case you need to have installed Qt 5.x toolkit and corresponding C++ compiler with C++11 support. qvge uses native Qt build system (main project file is qvgeapp.pro) so it should look like:

~~~~
cd <directory-with-qvgeapp.pro>
qmake
make (Linux) or nmake (Windows)
~~~~

### Supported OSes

qvge has been tested on Microsoft Windows 10 and several Linux OSes. Theoretically it should run on (almost) any OS which have Qt 5.x installed.

### Credits

qvge uses following 3rd party components:

- [Qt](https://www.qt.io) (c) Qt Company 
- [Qt property browser](https://github.com/qtproject/qt-solutions) (c) Qt Company 
- [QSint widgets library](https://sourceforge.net/projects/qsint) (c) Sintegrial Technologies
- [Inkscape](https://inkscape.org) (SVG icons)
- [read_proc library](https://daknuett.eu/personal) (c) Daniel Knuettel
