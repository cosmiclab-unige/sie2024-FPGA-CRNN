### Quick guide for the repo:
- **CRNN_LSTM_96_syn.keras** is the final model used for synthesis on Vivado, accuracy is 96%
- **Data_preparation.ipynb** is a script for preparing the dataset for training and testing
- **plot_model.ipynb** can be ignored
- **syn_worker*** and **trainer_worker*** are the scripts used for training and making the synthesis of the model.

### How to run the scripts
1. It is mandatory to have a Vivado HLS installation that complies with hls4ml requirements (versions 2018.2 to 2020.1), Vitis HLS (did not work) and other backends can be used, but they have not been tried for this implementation.
2. The system must be running Linux (Ubuntu 22.04 works) **_(a Docker is fine, if a Dockerfile is needed, please ask in the issues)_**
3. A Python 3.11 installation with pip
4. Install the requirements in requirements.txt using a venv
5. Run the Jupyter notebooks
