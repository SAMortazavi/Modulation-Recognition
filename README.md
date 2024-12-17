# Modulation Recognition using Deep Learning

This repository hosts the implementations of **MultiScale Convolutional Neural Networks (CNNs)** and **Shallow CNNs** for **Automatic Modulation Recognition (AMC)**. These models are inspired by the paper: **"Combining neural networks for modulation recognition"**, published in *Digital Signal Processing* (DOI: [10.1016/j.dsp.2021.103264](https://doi.org/10.1016/j.dsp.2021.103264)).

Both models achieve state-of-the-art performance in recognizing digital and analog modulation modes. The **MultiScale** network is designed to handle high-order modulation signals efficiently, while the **Shallow** network is specialized in resolving specific misclassification challenges.

---

## Repository Structure

### MultiScale Network
- Implementation of the **MultiScale CNN**, incorporating separable convolution and attention mechanisms.
- [Repository Link](https://github.com/SAMortazavi/Modulation-Recognition/tree/master/MultiScale)

### Shallow Network
- Implementation of the **Shallow CNN**, designed to complement the MultiScale network for resolving specific classification challenges.
- [Repository Link](https://github.com/SAMortazavi/Modulation-Recognition/tree/master/Shallow)

---

## Key Features
- **MultiScale CNN**:
  - Handles 24 modulation modes with high accuracy (98.7% at 26 dB SNR).
  - Integrates separable convolution and attention mechanisms for efficient feature extraction.
  - Robust against high-order modulation complexities.

- **Shallow CNN**:
  - Focused on resolving misjudgments between closely related modulation modes (e.g., AM-SSB-WC and AM-SSB-SC).
  - Lightweight architecture with reduced computational overhead.

---
## References

1. **Original Paper:** [Combining neural networks for modulation recognition](https://doi.org/10.1016/j.dsp.2021.103264).
2. **Dataset:** [RadioML 2018.01A](https://www.deepsig.io/datasets).

---

## Contributing
Contributions, bug reports, and suggestions are welcome! Feel free to submit an issue or a pull request.

---
