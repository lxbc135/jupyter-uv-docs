## Virtual environment setup

Packages are libraries or executables that you can install and call. The standard package management tool is pip. When you install Python (including using uv), pip is automatically installed.

Usually when pip installs packages, all projects in your login share them. But we prefer to isolate a set of packages to each project instead. For that, we create a "virtual environment" in each project:

**Go to your project folder**:

```sh
cd <project-folder>
```

**Create virtual environment**:

```sh
uv venv
```

It will create a virtual environment folder .venv.  (On Mac and Linux, you will need the -a option on ls command to see the "dot" (.) files and directories.)  It will set the Python version in it to be the latest version, by default. (`uv venv` internally uses another tool `venv` to do the actual work.)

**To activate the virtual environment**:

**Mac or Linux**:

```sh
source .venv/bin/activate
```

**Windows (Command Prompt)**:

```sh
.venv\Scripts\activate
```

**Windows (PowerShell)**:

```sh
.venv\Scripts\activate.ps1
```

**To deactivate the virtual environment**:

```sh
deactivate
```

**Reference**: https://docs.python.org/3/library/venv.html
