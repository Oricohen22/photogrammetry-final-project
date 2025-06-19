

---

 📸 Photogrammetry Final Project

Welcome to the Photogrammetry Final Project!
This project uses **COLMAP**, **Structure-from-Motion (SfM)**, and **Multi-View Stereo (MVS)** techniques to generate a 3D model from images.

---

 📂 Large Files Notice

⚠️ **Important:**
The `database.db` file is **larger than 100 MB** and is therefore not stored directly in this repository due to GitHub's file size limitations.

You can download it here:
[📥 Download `database.db` from Google Drive](https://drive.google.com/uc?id=10h7Nq5h07e025Bqn0pB_RhpNohMoSMOY&export=download)

---

 🛠️ How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/Oricohen22/photogrammetry-final-project.git
   cd photogrammetry-final-project
   ```

2. Download `database.db` manually from the link above, and place it in the project root directory.

3. Alternatively, you can automatically download it using Python:

   ```python
   import os
   import gdown

   if not os.path.exists("database.db"):
       url = "https://drive.google.com/uc?id=10h7Nq5h07e025Bqn0pB_RhpNohMoSMOY&export=download"
       gdown.download(url, "database.db", quiet=False)
   ```

---

## 📦 Repository Content

* Project source code
* COLMAP configuration files
* `database.db` file (external download only)

---

## 📑 License

This is an **academic project** for educational purposes only.

