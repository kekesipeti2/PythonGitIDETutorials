## Using Google Colab

[Google Colab](https://research.google.com/colaboratory/) gives you a place where you can run your Python scripts and .ipynb files. It provides you with a remote machine (when there isn't heavy load on the server 😅) for a certain time. Colab comes preinstalled with both PyTorch and TensorFlow and a couple other useful packages. You can also mount your Google Drive to save/load stuff there, link your GitHub to clone a repository and do many other things.

You can execute command prompt commands by using an exclamation mark (!) before your commands. This way you can for example check what GPU you have on the remote machine by using `!nvidia-smi`.

**IMPORTANT NOTE:**
By default Google Colab does not give you GPU or TPU resources. To demand these resources select `Futtatókörnyezet` -> `Futtatókörnyezet módosítása` -> `Hardveres gyorsítás: GPU` or `TPU`

Other Notes:

 - Google Colab only runs as long your machine and browser are running aswell (when using the Free version).
 - Google Colab very often has too few GPU/TPU resources. In this case you can not use these.
 - Google Colab's memory is not persistent. Therefore save every result to your Google Drive that you want to use later.
 - Google Colab can terminate your runtime when you leave it alone for too long/your code block runs for an extended period of time (~6 hours is the limit).
