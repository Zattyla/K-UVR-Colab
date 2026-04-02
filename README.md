# 🌊 UVR Elite Audio Separator
A standalone, high-performance Google Colab notebook for studio-grade vocal and instrumental separation.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/{YOUR_USER}/{YOUR_REPO}/blob/main/UVR_Elite_Separator.ipynb)

## 💡 Why use this?
Most RVC notebooks fail because of library conflicts between audio separation and voice conversion. This **UVR-Only** environment uses **NumPy 2.0+** and the latest `audio-separator` engine to ensure:
- 0% Dependency Errors.
- Maximum GPU Efficiency.
- Access to multiple MDX-Net models.

## 🛠️ Features
- **Multi-Model Support:** Includes Kim_Vocal_2, Voc_FT, and Inst_HQ_3.
- **Automatic De-reverb:** One-click removal of room acoustics for dryer, better RVC inputs.
- **High-Speed Processing:** Optimized for T4 GPUs on Google Colab.
- **Clean Workspace:** Automated folder management for Inputs and Outputs.

## 📂 Folder Structure
- `/inputs`: Upload your raw MP3/WAV files here.
- `/outputs`: Find your processed Vocals, Instrumentals, and De-reverbed tracks here.
- `/models`: Pre-loaded ONNX models for instant use.

## 🚀 Quick Start
1. Open the notebook in **Google Colab**.
2. Run the **Setup** and **Model Download** cells.
3. Upload your song to the `inputs` folder.
4. Select your model and run the **Inference** cell.

## 🤝 Credits
- Powered by [audio-separator](https://github.com/nomad-software/audio-separator).
- Models by [Anjok07](https://github.com/Anjok07/ultimatevocalremoverui).

---
**Maintained by:** [nwletter](https://github.com/Zattyla)
