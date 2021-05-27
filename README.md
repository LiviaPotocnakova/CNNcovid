# CNNcovid
This repository contains code of CNN used for COVID detection from CT scans and a trained model. It's a part of my bachelor thesis. 

### Contains: 
<ul>
  <li>file <strong>CNNcovid-source_code.ipynb</strong> - source code which includes: entire data preparation and datasets splitting, model building, training, testing with results and showcase of incorrectly classified cases.</li>
  <li>file <strong>mymodel.hdf5</strong> - model that has been trained and can be used for classification</li>
</ul>

### Usage:
<ol> 
  <li>In order to use the script and the model, you need to download the data from public repository: https://www.kaggle.com/plameneduardo/sarscov2-ctscan-dataset. Data is split into two folders - COVID and non-COVID</li>
  <li>Both folders need to be inside of another folder of your choice (e.g. our folder was called "original_dataset").</li>
  <li>Open the source code in a program that's able to work with ipynb files. We suggest Jupyter Notebook.
  <li>Download the script and change the to this folder path in a variable called "source_dir".</li>
  <li>Install any of the libraries you don't already have installed.</li>
</ol>
