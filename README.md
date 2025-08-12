# 💎 PixelProof — Jewellery Security Protocol Scanner

**PixelProof** is an advanced AI-powered jewellery analysis system designed to **authenticate, inspect, and reconstruct** jewellery pieces with high precision.

It integrates the **[TripoSR](https://github.com/VAST-AI-Labs/TripoSR)** 3D reconstruction model to generate **high-quality 3D meshes and textures** from a single image, combined with our proprietary **Security Protocol Scanner** to assess **material authenticity, detect wear, and evaluate overall security grade**.

---

## 🚀 Features

- **Material Analysis** — Identify surface type, reflectivity, and gloss level.
- **Spectral Analysis** — Real-time color palette detection and harmony classification.
- **Damage & Wear Detection** — Detect dents, scratches, and signs of wear.
- **Authenticity Scoring** — Rates jewellery authenticity and security level.
- **3D Reconstruction** — High-quality 3D OBJ & GLB models generated using TripoSR.
- **Evidence Capture Protocol** — Securely capture and store images for verification.
- **Security Validation** — Pass/Fail security scan with protocol status.

---

## 📊 Example Outputs

- **Spectral Analysis & Material Breakdown**
- **Live Capture & Surface Inspection**
- **3D Reconstruction Results** — OBJ & GLB models with full textures

---

## ⚙️ How It Works

1. **Upload** a jewellery image or **capture live** via a connected camera.
2. **PixelProof** runs **TripoSR** to create a 3D mesh and texture map.
3. **Security Protocol Scanner** evaluates:
   - Surface authenticity
   - Dents & scratches
   - Material reflectivity
   - Color harmony & saturation
4. **Generates a full Security Scan Report** with:
   - Authenticity level
   - Protocol status
   - Security score

---

## 🛠 Installation

### 1️⃣ Clone this repository
```bash
git clone https://github.com/yourusername/PixelProof.git
cd PixelProof
2️⃣ Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Install TripoSR model
bash
Copy
Edit
git clone https://github.com/VAST-AI-Labs/TripoSR.git
cd TripoSR
pip install -r requirements.txt
cd ..
4️⃣ Install additional system dependencies
Make sure you have PyTorch installed (with CUDA for GPU acceleration):

bash
Copy
Edit
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
▶️ Running PixelProof Locally
bash
Copy
Edit
python gradio_app.py
This will launch the PixelProof Jewellery Scanner interface locally in your browser.

📂 Project Structure
bash
Copy
Edit
PixelProof/
│── gradio_app.py          # Main application
│── security_scanner.py    # Protocol scanning & analysis
│── triposr_integration.py # TripoSR model interface
│── requirements.txt       # Python dependencies
│── /outputs               # Generated reports & 3D models
│── README.md              # Project documentation
📜 License
This project integrates the TripoSR model for 3D reconstruction.
© 2025 PixelProof — All Rights Reserved.
