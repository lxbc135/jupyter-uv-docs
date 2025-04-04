## VSCode Installation
We will use Visual Studio Code (VSCode) as Integrated Development Environment (IDE).

### Installing VSCode:

- Download installer from https://code.visualstudio.com/download
- Install it.

### Installing VSCode Extension for Python:
A VSCode Extension for Python can do syntax highlighting (colorization) for the Python code and help with debugging.

- Start VSCode
- Click **Extensions** button in the left sidebar, or press `Ctrl+Shift+X`
- Select **Python (Python language support)** by Microsoft. It will also include debugger support.

### Opening your project:

- Start VSCode
- Select **File > Open Folder**
- Select the project folder that you created

### Selecting Python interpreter

Let's select the Python interpreter for this project in VSCode:

- Select **View > Command Palette** or press `Ctrl+Shift+P`
- Select **Python: Select Interpreter**
- Select the Python from our `.\.venv` directory.

> **Note**: You can also go to the lower-right corner of the statusbar of VSCode, click `.venv/...`, and select the Python version from the virtual environment that we created earlier, `.\.venv\Scripts\python.exe` (this is Windows example).

Next time that you open the project, it should automatically select the same Python interpreter.

### Running Python program

To run the python file, press the ▷ ("Arrow") button in VSCode toolbar (in the upper right corner).

You can press ``Ctrl+` `` (Ctrl+Backtick) to toggle open the Terminal.
And you can run a python program like this:

```sh
python hello.py
```

### REPL (read–eval–print loop)

Entering `python` command without any option or argument will enter the REPL, which is an interactive programming environment where you can execute Python code interactively:

```
python
```

You can execute Python code there:

```sh
$ python
Python 3.13.1 (main, Dec  6 2024, 18:07:41) [MSC v.1942 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> print("Hello")
Hello
```

To exit the REPL (in Python 3.13 syntax):

```sh
>>> exit
```

In older Python versions, you may need to use the function call syntax:

```sh
>>> exit()
```
