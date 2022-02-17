## Using VSCode IDE

**VSCode is an optimal IDE for Python** and other projects. Unlike PyCharm Community it can handle Python Notebooks (.ipynb files). It also helps with debugging and provides a Git graphical interface unlike Jupyter Notebook.

### Installing VSCode and selecting your environment

To use VSCode you first have to **install** it through its [website](https://code.visualstudio.com/) or install it from Anaconda (found under Home page).

After installation you can launch VSCode. When using Anaconda you can **select the environment** at the top of Anaconda Navigator as seen on the picture.
![Anaconda environment selection](/tutorials/imgs/img2.jpg)

A different method to select your Python interpreter is to Press `Ctrl+Shift+P` , select `>Python: Select Interpreter` and then select your environment. If you can not find your environment in the list then you can add it manually.

### Opening your project

If your project **already exists** on your disk then use `File -> Open Folder...`.

If your project **does not already exist on your disk** then you can use VSCode's built-in Source Control to clone the project. This can be accessed through either: 

 - on the left side of the VSCode window under Source Control menu.
 - with the `Ctrl+Shift+G` keybind.
 - or by pressing `Ctrl+Shift+P`, selecting `>Git: Clone` then entering the repository path (in this case `fucskonorbi/ComputerVisionSystemsHF`).

After this you can open your project.

### Version Control through VSCode

VSCode has built-in Git support. This can be opened on the left side of the VSCode window under Source Control menu or with the `Ctrl+Shift+G` keybind. Here you can stage your changes, add a commit message, pull, push, clone, checkout another branch, and do many other things. In order to push to the remote GitHub repository you need to have access, but this can be done easily by signing it GitHub through VSCode. To see additional help regarding Git and version control see [Version Control](/tutorials/git.md).