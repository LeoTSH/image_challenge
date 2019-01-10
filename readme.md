## Pytorch image classification project for flowers

### **Summary:**
This repo contains the notebook and files to create an application to classify images of flowers.

Dataset is based on 102 different flowers and was extracted from [Here](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html). A separate testset was downloaded from Google's Image Search with 8 to 10 images in each class.

### **Requirements:**
Please kindly ensure that the following packages are installed prior to running the notebook/application:

* [Anaconda](https://www.anaconda.com/download/)
* Pytorch: 0.4.1
* torchvision: .2.1

### **Project folder/files structure:**
```
├───.ipynb_checkpoints
├───assets
└───flower_data
    ├───test
    ├───train
    └───valid
├───cat_to_name.json
├───Image Classifier Project.ipynb
```

#### Folders:
* **flower_data:** Contains the training, validation and, testing dataset used for the project

#### Files:
* **cat_to_name.json:** Json file containing mapping of categories to actual flower names (Contains the state dict)
* **checkpoint.pth:** Pytorch model checkpoint file
* **Image Classifier Project.ipynb:** Notebook containing the codes to run the project

### **Usage:**
1. Clone or download the repo
2. Install the required packages (Skip if this step has been completed)
3. Start the notebook `jupyter notebook` and open **Image Classifier Project.ipynb**
4. Run the code cells sequentially to process the dataset, train and, evaluate the model

Note: The first code cell is used to download the test dataset from Google hence, it is only required to run it once and afterwhich, it can be commented away.

### **Credits:**
Codes used in this repo is adapted from notebooks, files and lessons from the [Udacity Pytorch Scholarship Challenge Nanodegree Program](https://www.udacity.com/facebook-pytorch-scholarship).

Original Markdown cells from the program have been left in the notebook to help facilitate understanding and navigation