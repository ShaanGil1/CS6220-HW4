# HW3 CS6220
# Installation
- Install conda from: https://www.anaconda.com/ <br>
- Extract all files into a folder <br>
- In the root of the folder run the following line using conda command line<br>
```
conda env create -f environment.yml
```
```
conda activate HW4
```
- Run the trees.ipynb <br>
- Run all cells and the models should run, make sure all the .csv are in the same folder when running<br>
- Some results will be pasted into a .csv file after completion, the rest will be displayed on the notebook file
# Files
- tree.ipynb : File that does everything, cleans the data, and then runs single decision tree + random forests, and then does random forests experiments
- Credit_card_label.csv : Labels for testing data
- Credit_card.csv : The used dataset which contains all the features for the data
- results.csv : Prints outs random forest experiments into a table
- environment.yml : env file that has all the used packages/versions

