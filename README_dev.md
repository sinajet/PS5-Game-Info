## README For Developers

### Requirement
* Python 3.9+
* venv
* QtDesigner (Optional)

### Setup the Project

Fork and then clone the project 
```
git clone https://github.com/YOURUSERNAME/PS5-Game-Info.git
```

Setup the virtual environement and activate it

```
$ python -m venv ./venv
$ source venv/bin/activate

# For Windows
$ .\venv\Scripts\activate
```

Install the required packages
```
$ pip install -r requirements.txt
```

Then you can run the `PS5_Game_Info.py` python script
```
$ python PS5_Game_Info.py
```

To play around with the UI, you can download the Qt installer for your current platform from the [official download site](https://www.qt.io/download-qt-installer) and then follow the on-screen instructions. In this case, to complete the installation process, you need to [register a Qt account](https://login.qt.io/register).

#### Converting `.ui` file to Python (WIP: this breaks the python script)

To generate a Python output file run `pyuic6` from the command line, passing the `PS5_Game_Info.ui` file and the target file for output, with a `-o` parameter. The following will generate a Python file named `PS5_Game_Info.py` which contains the created UI.

```
pyuic6 PS5_Game_Info.ui -o PS5_Game_Info.py
```


### Build the Excutable File (for Windows)

Install `PyInstaller` if it's not already installed

```
$ pip install PyInstaller
```

Then you can build the app using the following command:

```
pyinstaller PS5_Game_Info.py
```

The executable file will be located in `dist/PS5_Game_Info/PS5_Game_Info.exe`

## Useful Resources
* [Qt Designer and Python: Build Your GUI Applications Faster](https://realpython.com/qt-designer-python/)
* [Packaging PyQt6 applications for Windows with PyInstaller & InstallForge](https://www.pythonguis.com/tutorials/packaging-pyqt6-applications-windows-pyinstaller/)