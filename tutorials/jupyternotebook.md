## Using Jupyter Notebook

You can open and edit .ipynb files with Jupyter Notebook. This comes preinstalled with Anaconda. To launch Jupyter Notebook either:

 - Open Anaconda Navigator and Launch `Notebook`. (*Note*: in this case the default folder will be your user folder.)
 - Open Anaconda Prompt and type: 
	 - `jupyter notebook --notebook-dir=<your_notebook_dir>`
	 - Example: `jupyter notebbok --notebook-dir=C:/`

This will open a Jupyter Notebook page in your browser. Here you can navigate to your .ipynb file and open it. After making changes you can do [Version Control](/tutorials/git.md) with your favourite Git software.

**Notes:**

 - Jupyter Notebook will by default use your own machine's resources. If your resources are not sufficient use [Google Colab](/tutorials/colab.md).
 - The default environment for Jupyter Notebook will be the one you launch it from in the command prompt, or the one you select in Anaconda Navigator. Make sure to change this to the appropriate environment.
 - You can delete cell outputs by converting the cell to a Raw text, then back to a Code cell. A different shortcut is to click on the given cell, then do `Escape`->`R`->`Y`.
