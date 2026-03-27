# Detect anomalous ECG signals using an unsupervised dense autoencoders
This project builds a dense autoencoder model trained only on normal ECG data, which can detect abnormal heartbeats without requiring labeled anomalous samples.

## Getting Started
### Dependencies
- **OS:** Windows 11 Pro / Ubuntu 20.04 / macOS 11+ (tested)
- **Python:** 3.10+
- **Python packages:** Installed via `requirements.txt`

  
### Required libraries:
- Pandas >= 2.3.3
- Numpy >= 2.3.4
- TensorFlow >= 2.10
- matplotlib >= 3.10.7
- seaborn >= 0.13.2
- scipy >= 1.16.3
- Keras >= 3.13.2
- Scikit-learn >= 1.7.2
- Jupyter

## Installing
1. **Clone the repository:**
```bash
   git clone https://github.com/sonythapaa/Anamoly-Detection-with-Autoencoders
   cd autoencoder-anomaly-detection
```
2. **Install all Python dependencies:**
```bash
   pip install -r requirements.txt
```
3. **Ensure the dataset ecg.csv is in the same folder as the notebook.**      
   No modifications to folder structure are needed.
   The dataset `ecg.csv` used in this project is taken from [kaggle dataset](https://www.kaggle.com/datasets/devavratatripathy/ecg-dataset)


## Executing Program

### 1. Run Locally(on your PC)
Open the Jupyter Notebook:
```bash
  jupyter notebook autoencoder_anomaly_detection.ipynb
```
### 2. Run on Google Colab (Recommended for Best Performance)

Open Google Colab [here](https://colab.research.google.com/).

Upload the notebook `autoencoder_anomaly_detection.ipynb` to Google Colab.  

**Enable GPU:**

Go to **Runtime -> change runtime type -> Hardware accelerator -> GPU**


## Disclaimer
This project is intended for **educational and research purposes only**.  
The autoencoder model detects anomalies in ECG signals for demonstration and learning purposes.  
It **should not be used for medical diagnosis, treatment, or any clinical decision-making**.  


## License
This project is licensed under MIT License - see `LICENSE.md` for details
