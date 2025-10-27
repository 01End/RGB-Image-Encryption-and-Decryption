# RGB Image Encryption and Decryption

A Python-based project that encrypts and decrypts RGB images using pixel-level transformations. The workflow includes **confusion** (pixel shuffling), **diffusion** (Caesar cipher), and reversible decoding, with visual representations of each stage.

---

##  Features & Highlights

- **Encryption Techniques**:
  - **Confusion**: Randomly shuffles pixel positions to obscure spatial data.
  - **Diffusion**: Applies a Caesar cipher (key = 50) to each pixel’s value.
  - **Decoding**: Reverses the diffusion and confusion steps to fully reconstruct the original image.
- **Visualization**: Clearly displays each processing stage—original, encrypted, decrypted, and side-by-side comparisons—making the transformations transparent and educational.

---

##  Getting Started

To set up and explore the notebook yourself:

```bash
git clone https://github.com/01End/RGB-Image-Encryption-and-Decryption.git
cd RGB-Image-Encryption-and-Decryption
# Optionally, create and activate a virtual environment
pip install -r requirements.txt
