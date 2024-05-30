Model Inversion and Part Classification
This repository contains Jupyter notebook scripts for performing model inversion attacks and part classification using PyTorch. The notebooks are organized based on different split layer settings for the part classifier model.

Introduction
Model inversion is a type of attack where an adversary attempts to reconstruct sensitive input data based on the output of a machine learning model. In this project, we explore model inversion attacks in the context of a part classifier model trained on casting images.

Notebooks
The repository includes the following notebooks:

Model_Inversion_split_layer_2.ipynb: Notebook implementing the part classifier model with a split layer setting of 2.
Model_Inversion_split_layer_3.ipynb: Notebook implementing the part classifier model with a split layer setting of 3.
Model_Inversion_split_layer_4.ipynb: Notebook implementing the part classifier model with a split layer setting of 4.
Model_Inversion_split_layer_6.ipynb: Notebook implementing the part classifier model with a split layer setting of 6.
Model_Inversion_split_layer_8.ipynb: Notebook implementing the part classifier model with a split layer setting of 8.
Each notebook explores the impact of different split layer settings on model performance and vulnerability to model inversion attacks.

Dependencies
The scripts require the following dependencies:

Python 3.x
PyTorch
NumPy
Matplotlib
torchvision
torchsummary
PIL
You can install the required packages using pip:

bash
Copy code
pip install torch numpy matplotlib torchvision torchsummary Pillow
Usage
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/model-inversion-and-part-classification.git
Navigate to the cloned directory:
bash
Copy code
cd model-inversion-and-part-classification
Open the desired notebook using Jupyter Notebook or JupyterLab:
bash
Copy code
jupyter notebook Part_Classification_Split_Layer_2.ipynb
Run the cells in the notebook to execute the code and observe the results.
Acknowledgments
The casting dataset used in this project is sourced from kaggle, but you can choose your own dataset with some adjustments and keeping in mind that this models is suited for binary classification.
Parts of the code may be adapted from various online tutorials, forums, and research papers. Proper citations are provided within the notebooks.
