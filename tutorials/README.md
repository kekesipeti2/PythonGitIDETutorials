## Tutorials

This page lists tutorials that are useful when starting out with coding Python, using IPython Notebooks, doing version control, etc.

There are **two paths** to running your scripts:

 1. Remotely on services like Google Colab. In this case head to the [Using Google Colab](/tutorials/colab.md) page.
 2. On your own machine. When choosing this option then you will first need to [Install Python](/tutorials/InstallingPython.md). Then you can use a couple of different softwares to run your scripts, and to use Git. The recommended methods and tutorials for it are listed below:
	- [Using VSCode](/tutorials/usingVSCode.md).
	 - [Using Jupyter Notebook](/tutorials/jupyternotebook.md).

To know what you need to "Version Control" exactly and how to do it head to the [Version Control](/tutorials/git.md) tutorial. Using Git can be done through VSCode's built-in Source Control panel (see above) or a Git software, eg. [GitExtensions](http://gitextensions.github.io/). 
For the latter you can find tutorials online, for example: [GitExtensions Tutorial](https://bytescout.com/blog/beginner-guide-to-git-on-windows-using-git-extensions) - you don't have to mess around with SSH keys, there is a GitHub menu on GitExtensions, which will help you authorize your GitHub.

### VERY IMPORTANT NOTE:
!wget and !unzip commands do not work by default on Windows (it is supposed to work on UNIX systems). Therefore you have to install GnuWin32's [unzip](https://sourceforge.net/projects/gnuwin32/files/unzip/5.51-1/unzip-5.51-1.exe/download?use_mirror=altushost-swe&download=) and [wget](https://sourceforge.net/projects/gnuwin32/files/wget/1.11.4-1/wget-1.11.4-1-src-setup.exe/download?use_mirror=jztkft) tools.