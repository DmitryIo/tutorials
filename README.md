# SOTAML School tutorials
This is the tutorials repository of the SOTA Machine Learning School.

## The list of tutorials available currently (links to be updated):
1. Natalia Khanzhina and Roman Lebedev (Day 1)-- The pipeline of typical CV task solving with frameworks comparison
2. Arip Asadulaev and Petr Kuznetsov (Day 2) -- GANs for Image Generation
3. Arip Asadulaev and Petr Kuznetsov (Day 2) -- Optimal Transport task

# How to run 
All the tutorials are created to work with Google Colaboratory, thus no additional software packages installing is required.
1. Go to https://colab.research.google.com/github/sotamls-itmo/tutorials
2. [If required] log in to your GitHub account via the pop-up window
3. Choose the notebook from the list to open. You will see the following window
![Notebook](/img/notebook.png)
4. [If required] log in to your Google account
5. Before running, make sure that the device you are using is configured correctly. To check it go to **'Edit -> Notebook settings'** in the menu  and switch **'Hardware accelerator'** to **'GPU'** or **'TPU'** depending on the tutorial instructions.
![Device](/img/gpu.png)
6. In the next window, click **'RUN ANYWAY'** and click **YES** for **'Reset all runtimes'**
![Run anyway](/img/run.png)
# How to save notebooks
You can save the notebooks on your local machine using one of following options:
- In the notebook menu via **File->Save a copy in Drive** or **File->Download.ipynb**
- On your local machine' terminal via bash `!pip install --upgrade git+https://github.com/sotamls-itmo/tutorials.git#subdirectory=<name of tutorial subdirectory>`
