
## Jupyter Notebook setup with uv

Create a project using uv as above.
In VSCode, select **File > Open Folder**, and select the project folder.
Press **Ctrl+Shift+P** to open Terminal.

**To add jupyter into the project**:

```sh
uv add jupyter
```

**Add additional packages**:

```sh
uv add pandas numpy matplotlib
```

**To launch Jupyter Notebook**:

```sh
uv run jupyter notebook
```

This will open Jupyter in your default browser.

**Note**: At this point, there is no Jupyter kernel created.
Click **Python 3 (ipykernel)**  in upper right corner to create a Jupyter kernel (which runs Python code in Jupyter notebook).

To try the notebook, type this code:

```python
import numpy
a = numpy.array([1, 2, 3])
a
```

It should show this:

```
array([1, 2, 3])
```

To save file, select **File > Save Notebook As**.
It should save the `.ipynb` file in the project directory.

To shutdown Jupyter Notebook, press `Ctrl+C` on the Terminal.

Next time, you can open the project folder in VSCode, again.
VSCode will automatically activate the virtual environment.
