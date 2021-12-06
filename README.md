# Analyzing Gender Bias in Audio Deepfake Detection through One-Class VAE
- CMU Introduction to Deep Learning Fall 2021

## Setup
Place the 11785FP.ipynb file to your local Google Drive. Also, under your local Google Drive, create a folder named '11785FinalProject'.

To run the ipynb file, run as a Colab Pro with a high-memory runtime setting. To do so, select the Runtime > 'Change runtime type' dropdown menu, and then select High-RAM in the Runtime shape dropdown. 

## Dataset 
Install the ASVspoof 2019 LA dataset (LA.zip) from this [website](https://datashare.ed.ac.uk/handle/10283/3336). Place the LA.zip file under the '11785FinalProject' directory, and unzip the file:

```bash
unzip LA.zip -d /root
```
## Running the Model
Run the markdown cells of the ipynb file in the order such that all datasets are loaded to your Google Drive folder. The steps in the ipynb file is:
- Loading the Test and Validation Dataset using MelBankDataset Class
- Model of One-Class Variational Autoencoder (OC-VAE)
- Concatenating the Counterfactual Value to the Input Data 
- Training the Model
- Validation the Model
- Main Function to Train the Model with Hyperparameters (i.e. latent size, # of epochs)
- Generate the Plots
