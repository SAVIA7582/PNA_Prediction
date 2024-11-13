# Machine-Learning-based-PNA-Synthesis-Prediction
code for training and applying ML model to predict peptide nucleic acid sequence synthesis 

## Files

`Training.ipynb` : iPython notebook for training

`PNA_Prediction.ipynb`: iPython notebook for predicting unknown sequences

`my_model.pkl`:  best trained model for predicting 


## Install the required packages
```bash
conda create -n pna python==3.10.14
source activate pna
pip install numpy==1.24.3
pip install pandas==2.2.2
pip install scikit-learn==1.5.1
pip install ipykernel
python -m ipykernel install --name pna
```

# Usage

To run the ML model, navigate to the Anaconda interface and execute the provided Jupyter Notebook (`Training.ipynb`). Follow the step-by-step instructions within the notebook to perform the analysis.(Switch the kernel to `pna` in the installation guide)
