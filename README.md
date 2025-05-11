# Language Technology for Forensic and Investigative Linguistics

This is a project for this course, offered by the University of Helsinki in 2025. The notebook contains some simple stylometric analysis on the [Malmi - Nakamoto emails](https://mmalmi.github.io/satoshi/). I am not proficient at Forensic Linguistics and this analysis is done out of curiosity and I am in no way making any claims about anyone involved with the emails. 

## How to run
The `script.ipynb` file already contains the outputs and plots of the script, so you don't need to run it to see them.

To run, copy this project directory to your machine. Open the directory in your terminal and run `conda env create -f environment.yml`, then `conda activate LTfFIL`. This should activate a conda environment that you must use to run the script, you can use it as a kernel in VSCode. In the same directory, add two folders titled `Malmi` and `Nakamoto`. Move the emails into the folders, each email as their own `.txt` file. Then, copy the project [radialtree](https://github.com/koonimaru/radialtree) into this same project folder. Then, when opening the script file, you can run the cells and everything should work fine.

