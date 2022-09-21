# WatchListWebApp
WatchList in WebApp form made with PYQT6

Currently a WIP.

# Open/Use Project Files Yourself

1. Get [Python 3.9.0](https://www.python.org/downloads/release/python-390/)
2. Open a terminal and type 'pip install pyqt6-tools'
3. Locate pyqt6 designer (generally on win10 under user/(username)/AppData/Local/Programs/Python/Python39/Lib/site-packages/qt6_applications/QT/bin)
4. Open the .ui file in the designer

# Create Py Files Relating to UI files

1. CD in the terminal into the directory with the UI file
2. type 'pyuic6 -x (ui file name).ui -o (output file).py' <- x = executable version, o = output
3. Works properly if there's no response other than a new line
