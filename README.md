# Fortnite-Afk-Token-Tool
Tool that auto-connects to a squad fill match and stays there for 20 or more minutes, or leaves whenever dead! Feel free to use.
Run from VScode with python
1. Install Python (if you haven’t)

Download it from python.org/downloads and run the installer.
On the first screen, tick “Add python.exe to PATH” before clicking Install. This is the most common thing people miss.
To check it worked, open Command Prompt and type python --version. You should see a version number.

2. Install the Python extension in VS Code

Press Ctrl+Shift+X to open Extensions.
Search for Python (published by Microsoft) and click Install.

3. Open the file

Download fortnite_loop_bot.py from the file card above and put it in a folder, for example C:\fortnite-bot.
In VS Code, choose File → Open Folder and select that folder. Click “Yes, I trust the authors” if asked.
Click fortnite_loop_bot.py in the left sidebar.

4. Pick the Python interpreter

Press Ctrl+Shift+P, type Python: Select Interpreter, and choose the Python version you installed.

5. Install the libraries

Open the terminal with Ctrl+` (the key under Esc).
Paste this and press Enter:
  pip install opencv-python mss pyautogui numpy
Wait for it to finish. If it says pip is not recognized, Python wasn’t added to PATH. Re-run the Python installer, choose Modify or Repair, and tick the PATH option.

6. Run it

In the terminal, type python fortnite_loop_bot.py and press Enter.
Or click the ▶ Run button at the top right of the editor.
The bot’s window should pop up.
