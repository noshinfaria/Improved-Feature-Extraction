<h1 align="center">Leveraging Multi-Feature Fusion for Fingerprint Verification Using Siamese Networks</h1>
Project Overview

This project implements a hybrid fingerprint verification system using a combination of SIFT (Scale-Invariant Feature Transform) and CNN (Convolutional Neural Networks) features, processed through a Siamese Network. The system aims to improve the robustness and accuracy of fingerprint verification, especially in noisy or low-quality images.

The core idea behind this research is to fuse local features captured by SIFT and global features captured by CNN, allowing the verification system to leverage the strengths of both approaches for improved accuracy.
Key Features:

    Fingerprint Preprocessing: Includes techniques like Contrast Limited Adaptive Histogram Equalization (CLAHE) and normalization for image enhancement.
    Feature Extraction:
        SIFT is used to capture local, invariant features such as ridge endings and bifurcations.
        CNN (VGG19) is used to extract global, high-level features that capture the overall structure of the fingerprint.
    Feature Fusion: Combines local features from SIFT and global features from CNN for a more comprehensive representation of the fingerprint.
    Siamese Network: Utilizes a Siamese network to compare two fingerprint images and output a similarity score to determine if they belong to the same individual.


This will:

    Preprocess the fingerprint images.
    Extract features using both SIFT and CNN.
    Train the Siamese network on the extracted features.
    Evaluate the model's performance on the dataset.

Results

    True Acceptance Rate (TAR): ~98.5% for the SIFT-CNN hybrid approach.
    False Acceptance Rate (FAR): ~0% for the SIFT-CNN hybrid approach.
    Equal Error Rate (EER): ~1.2% for the SIFT-CNN approach, outperforming CNN-based extraction.

The SIFT-CNN hybrid approach outperforms the CNN-only method in fingerprint verification tasks, especially in noisy or low-quality images.
