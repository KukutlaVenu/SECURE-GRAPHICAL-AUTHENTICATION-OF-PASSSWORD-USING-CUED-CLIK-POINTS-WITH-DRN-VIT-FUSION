# 🔐 Secure Graphical Authentication of Password Using Cued Click Points with DRN-ViT Fusion

This project implements a secure and user-friendly authentication system using **Graphical Passwords** based on **Cued Click Points (CCP)** and a **hybrid Deep Learning model (DRN + ViT)**. It aims to provide an alternative to traditional text-based passwords by leveraging the human brain's strong visual memory capabilities.

## 🚀 Features

- 🎯 Graphical password system using Cued Click Points (CCP)
- 🧠 Hybrid Deep Learning Model using **Deep Residual Networks (DRN)** and **Vision Transformers (ViT)**
- 🔒 Strong encryption and hashing for security
- 💬 User-friendly GUI built with **PyQt5**
- 🔄 Secure login and registration flow
- 📊 Metrics tracking (Accuracy, Precision, Recall, F1-Score)

---

## 🧩 Technologies Used

- **Python 3**
- **PyQt5** – For GUI
- **OpenCV** – Image processing
- **Torch & torchvision** – Deep Learning models
- **SQLite** – Local database
- **Encryption** – Password and coordinate security

---

## 🧠 Deep Learning Architecture

- **DRN (Deep Residual Network)** – Focuses on local features like edges and texture.
- **ViT (Vision Transformer)** – Focuses on global contextual dependencies in image sequences.
- **Fusion Layer** – Combines both models’ outputs to authenticate user input.

---

## 🛡️ Security Measures

- 🔐 Click point encryption and password hashing with salt
- 📍 10-pixel tolerance radius for usability
- 🧾 Failed login tracking
- 🔁 Optional backup question for recovery

---

## 🧪 Testing

- Registration & login verified through GUI
- Click patterns tested for distortion tolerance
- Evaluation metrics: Accuracy, F1-score, Standard Deviation across multiple models

---

## 📸 Screenshots

> Add screenshots of your registration, login, and model performance charts here.

---

## 📂 Project Structure

```
📁 Graphical-password-authentication/
│
├── 📂 dataset/                    # Image dataset used for CCP
├── 📂 models/                     # Pretrained DRN and ViT models
├── 📜 main.py                     # Main launcher for GUI
├── 📜 train.py                    # Deep learning training script
├── 📜 authenticate.py             # Login logic with model
├── 📜 utils.py                    # Helper functions (encryption, preprocessing, etc.)
├── 📜 database.db                 # SQLite database for user data
└── 📜 README.md                   # This file
```

---

## 📈 Results

| Model       | Accuracy | F1-Score |
|-------------|----------|----------|
| DRN         | 91.5%    | 89.3%    |
| ViT         | 90.1%    | 87.6%    |
| DRN + ViT   | **96.2%**| **94.8%**|

---

## 🔮 Future Scope

- Integration with biometric features (fingerprint or face)
- Dynamic tolerance area using user behavior
- Cloud deployment for real-world use
- REST API interface for cross-platform support

---

## 📜 License

This project is licensed under the MIT License. Feel free to modify and use it.

---

## 🌟 Star the repo if you like the project!
