# Machine Translation
A deep neural network that functions as part of a machine translation pipeline. The pipeline accepts English text as input and returns the French translation. The goal is to achieve the highest translation accuracy possible.

## Install
- Python 3
- NumPy
- TensorFlow 1.x
- Keras 2.x

## Building the Pipeline
Below is a summary of the various preprocessing and modeling steps. The high-level steps include:

1. **Preprocessing**: load and examine data, cleaning, tokenization, padding
2. **Modeling**: build, train, and test the model
3. **Prediction**: generate specific translations of English to French, and compare the output translations to the ground truth translations

## Results
The results from the final model:

Validation accuracy: 97.5%

Training time: 23 epochs
