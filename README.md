# EARS33: Earth Surface Processes and Landforms
This is a geomorphology course taught at Dartmouth College. This repository contains data tutorial activities and associated files. It also contains a showcase of student coding projects. 

## Installing locally 
The 2022 notebooks can run on Colab, but I'm switching to Dartmouth's Jupyter Hub for Spring 2023. You can still download and run these notebooks locally, however:
1. If you don't have a Python distribution, I'd recommend installing `miniconda` but `Anaconda` works too. 
2. Download the files via `git clone https://github.com/jmdelvecchio/ears33.git`
3. Use Anaconda Prompt or however you're going about this coding world to install the `ears33` environment: `conda env create -f environment.yml` and then `conda activate ears33`
4. Run the Jupyter Notebooks, which I think I am just realizing that the environment file probably doesn't have notebook in it...whoops. You'll have to `conda install -c conda-forge notebook` or really `conda install -c conda-forge jupyterlab` these days I guess. 