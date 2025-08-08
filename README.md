# 🌿 Plant Medicinal Identifier 💊

A web application that identifies plants using your camera and displays their medicinal properties, powered by TensorFlow.js and Google Teachable Machine.

<img width="891" height="702" alt="User Interface" src="https://github.com/user-attachments/assets/2b7d4267-b686-4e06-ac28-57eb639a04d3" />

## Features
📷 Real-time plant identification using webcam.
<p align="center">
<img width="305" height="466" alt="Camera Input" src="https://github.com/user-attachments/assets/a312a435-36e0-4294-a359-559e0cd47d7a" />
</p>
<br>
💊 Detailed medicinal uses for each plant.
<br>
<p align="center">
<img width="779" height="849" alt="Use Case" src="https://github.com/user-attachments/assets/d0a1bc6c-5d37-4ccf-95b4-aa262b9cd9ab" />
</p>
 <br>
⚠️ Color-coded safety precautions (red for toxic plants).
<br>
🌱 Clean, responsive interface.
<br>
🔄 Continuous prediction while camera is active.
<br>
<p align="center">
<img width="739" height="839" alt="Use Case_Wrong" src="https://github.com/user-attachments/assets/79a3febb-668e-4739-aba6-a4db3b3830f0" />
<img width="741" height="853" alt="USe Case_Fixed" src="https://github.com/user-attachments/assets/3bdbd5ef-d24c-4946-9acc-0a56db80fe68" />
</p>
<br>

## Supported Plants
1. Mango Tree
2. Neem Tree
3. Black Plum
4. Pomegranate
5. Tamarind Tree
6. Sacred Fig
7. Banyan Tree
8. Oleander *(toxic - red warning)*

## Technologies Used
- TensorFlow.js
- Teachable Machine Image Model
- HTML5/CSS3
- JavaScript (ES6)

## Setup Instructions

### 1. Prerequisites
- Modern browser (Chrome/Firefox recommended)
- Webcam access
- Internet connection (for model loading)

### 2. Quick Start
1. Clone the repository
[git clone] ([url](https://github.com/mars-127/plantMD.git))
2. Open index.html in browser
open index.html  # Or just double-click the file

### 3. Using Your Own Model
1. Train your model at [Teachable Machine]([url](https://teachablemachine.withgoogle.com/train/image))
2. Export as "TensorFlow.js" model
3. Replace in script.js:
> const modelURL = "YOUR_MODEL_URL/model.json";
> const metadataURL = "YOUR_MODEL_URL/metadata.json";

# File Structure
plant-identifier/ \
├── plantmedindex.html          # Main application\
├── script.js           # Core functionality\
├── styles.css          # Custom styling\
└── model/              # Teachable Machine model files\
    ├── model.json\
    ├── metadata.json\
    └── weights.bin\

# Troubleshooting
### Issue	Solution
1. Camera not starting	Allow camera permissions in browser
2. "tmImage not defined"	Check internet connection and CDN links
3. Low accuracy	Retrain model with more images
4. Blank predictions	Ensure proper lighting and focus

# Future Enhancements
- [ ] Add more plant species
- [ ] Mobile app version
- [ ] Offline capability
- [ ] Multi-language support

---

## License
MIT License - Free for educational and personal use
## Credits
Project idea brought about by Praveen Bhaskar B from EVidyaloka. Developed by Shreya Rawat using Google's Teachable Machine platform. 
