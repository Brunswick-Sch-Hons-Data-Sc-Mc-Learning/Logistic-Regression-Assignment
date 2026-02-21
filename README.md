If your code isn't running or you see an "Install Kernel" error, follow these 5 steps in order:

1. Wait for the "Wake Up"
Look at the bottom blue bar of the window. If it says "Setting up Codespace" or "Installing Extensions," stop! Wait 60 seconds for the cloud to finish building.

2. Connect the "Brain" (Select Kernel)
Look at the top right corner of your notebook.

Click Select Kernel (or where it says "Python 3.x").

Choose Python Environments...

Select Python 3.12.1 (it may say "Global" or /usr/local/bin/python).

3. Run the "Emergency" Install
If your code says ModuleNotFoundError, force the installation manually:

Go to the Terminal at the bottom (Press Ctrl + `  if you don't see it).

Paste this command and hit Enter:

Bash
**pip install pandas scikit-learn matplotlib seaborn ipykernel**


Wait for the text to stop moving and the command prompt to reappear.

4. Refresh & Run
5. 
Click the Restart button (the curved arrow ↻) at the top of the notebook.

Click Run All.

Look for the green checkmarks  next to your code.

5. Ignore the ".venv" Pop-up
If a box appears in the bottom right asking to "Create a virtual environment":

Click "Cancel" or "Don't Show Again."

You are already in a secure cloud container; you do not need an extra virtual environment.# Logistic-Regression-Assignment
