PixelProof — Jewellery Security Protocol Scanner
PixelProof is an advanced AI-powered jewellery analysis system designed to authenticate, inspect, and reconstruct jewellery pieces with high precision.
It uses the TripoSR 3D reconstruction model to generate accurate 3D meshes and textures from a single image, combined with our proprietary Security Protocol Scanner to assess material authenticity, detect wear and dents, and evaluate overall security grade.

🔍 Features
Material Analysis — Identify surface type, reflectivity, and gloss level.

Spectral Analysis — Real-time color palette detection and harmony classification.

Damage & Wear Detection — Detects dents, scratches, and signs of wear.

Authenticity Scoring — Rates jewellery authenticity and security level.

3D Reconstruction — High-quality 3D OBJ & GLB models generated using TripoSR.

Evidence Capture Protocol — Securely capture and store images for verification.

Security Validation — Pass/Fail security scan with protocol status.

📊 Example Analysis
Spectral Analysis & Material Breakdown

Live Capture & Surface Inspection


3D Reconstruction Results
OBJ & GLB models with full textures.

⚙️ How It Works
Upload a jewellery image or capture live via connected camera.

PixelProof runs TripoSR to create a 3D mesh and texture map.

The Security Protocol Scanner evaluates:

Surface authenticity

Dents & scratches

Material reflectivity

Color harmony & saturation

The system generates a full Security Scan Report with:

Authenticity level

Protocol status

Security score

🖥️ Running Locally
bash
Copy
Edit
python gradio_app.py
This will launch the PixelProof Jewellery Scanner interface locally.

📜 License
This project integrates the TripoSR model for 3D reconstruction.
© 2025 PixelProof — All Rights Reserved.
