# Deliverable_4_2
The main repository for all Deliverable 4.2 content

# For ESRS that want to generate a local version of the website
1. create and activate a conda environment
2. install dependencies (jupyter-book, matplotlib, numpy)
3. create a folder somewhere
4. open conda prompt and navigate to the aforementioned folder
5. create a JupyterBook something like ```jupyter-book create NameOfBook``` - this should create a folder called NameOfBook and I believe some dummy files
6. copy the cloned repository into this folder (using conda prompt or manually)
7. build the JupyterBook via ```jupyter-book build NameOfBook/``` - this should then create and populate a _build folder.
8. Within the _build folder is another folder called html, within which you should find all the html pages, which you can then view on your local machine.

Otherwise take a look at this [video](https://www.youtube.com/watch?v=lZ2FHTkyaMU&t=13s).
