# 🌿 Plant Medicinal Identifier 💊

A light weight web application that identifies plants using your camera and displays their medicinal properties, powered by TensorFlow.js and Google Teachable Machine cloud model. 

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
🚀 No backend/server required <br>
🔗 Uses Teachable Machine's hosted model

## Supported Plants
1. Mango Tree
2. Neem Tree
3. Black Plum
4. Pomegranate
5. Tamarind Tree
6. Sacred Fig
7. Banyan Tree
8. Oleander *(toxic - red warning)*

## How to Use
1. **Download** `plantmedindex.html`
2. **Open it** in Chrome/Firefox
3. **Allow camera access** when prompted

## No Setup Required!
The app automatically loads:
- TensorFlow.js from CDN
- Teachable Machine library from CDN
- Your trained model from Google's servers

## For Custom Models
1. Train at [Teachable Machine](https://teachablemachine.withgoogle.com/)
2. Export as "TensorFlow.js (cloud)"
3. Replace this line in `plantmedindex.html`:
```html
<script>
  const modelURL = "https://teachablemachine.withgoogle.com/models/YOUR_MODEL_ID/";
</script>
```

# Troubleshooting
### Issue	Solution
1. Camera not starting:	Allow camera permissions in browser
2. "tmImage not defined":	Check internet connection and CDN links
3. Low accuracy:	Retrain model with more images
4. Blank predictions:	Ensure proper lighting and focus

# Future Enhancements
- [ ] Add more plant species
- [ ] Mobile app version
- [ ] Multi-language support

---

## License
MIT License - Free for educational and personal use
## Credits
Project idea brought about by Praveen Bhaskar B from EVidyaloka. Developed by Shreya Rawat using Google's Teachable Machine platform. 
