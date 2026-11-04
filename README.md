# QCB Token Tool

## What is QCB Token Tool?

QCB Token Tool is a small Windows program that watches your screen and clicks the end-of-match buttons in Fortnite for you: **Continue**, then **Skip**, then **Play Again**. It repeats this after every match.

It only looks at the screen and moves the mouse. It does not touch the game files.

> **Heads up:** Epic's rules don't allow automating gameplay, and anti-cheat can flag it. Use it at your own risk, and not on an account you care about.

## What do I need?

- A Windows 10 or 11 PC and an internet connection (for the first setup only).
- Fortnite set to **Windowed Fullscreen** (Settings -> Video -> Window Mode).

Setup installs the rest for you:

- Python 3.12 (with tkinter)
- opencv-python, mss, pyautogui and numpy

## How do I install it? (once)

1. Download the zip. On GitHub, click the green **Code** button, then **Download ZIP**.
2. Right-click the zip -> **Extract All** -> **Extract**. Don't run files from inside the zip.
3. Open the extracted folder, then the **setup** folder.
4. Double-click **SETUP** (it may show as `SETUP.bat`).
5. Click **Yes** on the pop-up. If a blue screen says "Windows protected your PC", click **More info** -> **Run anyway**.
6. Wait while the black window installs everything (about 5 minutes). Don't close it, even if it looks stuck.
7. When it says **ALL DONE**, press **Y** to open the tool. A **QCB Token Tool** shortcut is now on your desktop.

## How do I use it?

1. Open Fortnite and start your first match yourself. The tool doesn't press the first Ready button.
2. Double-click the **QCB Token Tool** shortcut on your desktop and click **Yes**.
3. Press **START** in the tool window.
4. You have 5 seconds: click on the Fortnite window.
5. Leave it alone. When the match ends it clicks Continue, Skip and Play Again by itself, and keeps repeating.

## How do I stop it?

- Press **STOP** in the tool window, or
- move the mouse into the **top-left corner** of the screen.

## Prefer doing it by hand?

If you already have Python 3.9 or newer, you can skip setup:

```
pip install opencv-python mss pyautogui numpy
python fortnite_loop_bot.py
```

## Something went wrong?

- **The window doesn't open:** double-click `setup\run_with_console.bat`. It shows the error message.
- **A button isn't clicked:** press **Test detection** while that screen is showing. If the number for the right button is below 0.75, drag **Match strictness** down a little.
- **You moved the folder:** run **SETUP** again from the new place.

## What is in this folder?

- `START_QCB_TOKEN_TOOL.bat` - opens the tool as administrator
- `fortnite_loop_bot.py` - the program
- `setup/SETUP.bat` - one-time installer
- `setup/run_with_console.bat` - opens the tool with a console that shows errors
- `setup/requirements.txt` - the Python libraries it needs

## Credits

Made by **-gy**.

<p align="center">
  <img src="setup/logo.png" width="240" alt="QCB Token Tool logo">
</p>
