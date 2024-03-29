# System requirements and setup

## Mac

1. Open Terminal.
2. Run `python --version`. See what Python version you have. You need at least Python 3.12. You can get it from the [main Python website](https://www.python.org/downloads/).
3. Fetch and install [Visual Studio Code](https://code.visualstudio.com/) if you don't already have it.
4. Fetch the zip of this course (your instructor will tell you how).
4. In Terminal, run:
```
unzip ~/Downloads/browser-learning.zip
cd browser-learning
python3 -m venv venv
. venv/bin/activate
python3 -m pip install -r src/requirements.txt
```

## Chromebooks

1. Under the main menu in bottom left corner of the screen, open Terminal. Follow the instructions to turn on the Linux environment if necessary. Go with all the standard settings. (Note that this environment may not be available for guest users)
2. Fetch the zip of this course (the instructor will tell you how). Copy it into the Linux environment from Chrome's downloads page.
3. In the terminal, run these commands: (you might need to slightly change the filename in the first command)
```
unzip browser-learning.zip
cd browser-learning
./install-linux-prerequisites.sh
python3 -m venv venv
. venv/bin/activate
python3 -m pip install -r src/requirements.txt
```

## Other types of machine

Do what's required to install:

* Python 3.12+
* `tcpdump`
* Visual Studio code, or some other good code editor (the students will be doing lots of _reading code_ so a good IDE is highly recommended)