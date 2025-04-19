# Multi-Modal Recognition System

This system is built as my Final Project in the course ENCM 509: Biometric Systems Design
The project implements a basic multi-modal authentication system that verifies users using facial recognition and speaker recognition. By combining the strengths of both modalities, the system aims to provide a more robust and reliable approach to user authentication.

## Technologies Used:
- OpenCV - image processing and facial feature extraction
- NumPy, Pandas – data manipulation and analysis
- Matplotlib – data visualization

## Key Features

### Facial Matching:
- Feature extraction using LBP (Local Binary Patterns)
- Matching based on Euclidean distance

### Speaker Verification:
- Feature extraction using MFCC (Mel-Frequency Cepstral Coefficients)
- Classification with GMM (Gaussian Mixture Models)

### Modality Fusion:
- Simple decision-level fusion strategy to combine outcomes
- Improved accuracy in detecting impostors


## Observations

- Speech differences were more noticeable between the two female users than between the male and female users, likely due to accent variations.

- Female subjects showed greater facial similarity compared to the male-female pair. This was likely influenced by features such as hair color, smiling with teeth, facial structure, and the presence of glasses.

- Fusion led to a significant increase in accuracy, as one modality compensated for the limitations of the other.


## Execution Instructions
Download the .ipynb file, the ATT dataset folder, and the speakers_audio_data folder into the same directory.

Open and run the .ipynb file.

If any required packages are missing, install them using your preferred package manager.
For example, in Jupyter Notebook, you can install a missing package in a cell by using ``` !pip install package-name ```
