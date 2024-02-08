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
