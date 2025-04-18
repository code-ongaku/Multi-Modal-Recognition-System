# Multi-Modal Recognition System

This project implements a basic multi-modal authentication system that integrates facial recognition and speaker recognition to verify users. By combining the strengths of both modalities, the system aims to provide a more robust and reliable approach to user authentication.

## Technologies Used:
- Python
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

- Speech differences were more distinct between two female users than between a male and female, likely due to accent variations.

- Facial similarities were higher among female subjects, slightly reducing face-matching reliability.

- Fusion led to a significant increase in accuracy, as one modality compensated for the limitations of the other.

