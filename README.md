# 🔍 AI-Powered Smart Parking Slot Detection

An AI-based real-time parking space detection system that leverages **Computer Vision** and a **custom-trained SVC classifier** to monitor and identify available parking slots from live video streams. Ideal for deployment in smart cities, malls, and autonomous surveillance systems.

![Parking Detection](https://github.com/user-attachments/assets/a76854b9-c656-483f-90a3-cb9fd5233d31)

---

## ⚡ Key Highlights

- 🎥 Real-time video feed analysis using OpenCV  
- 🧠 Intelligent parking slot classification via custom-trained SVC model  
- 🖼️ Parking slot segmentation using binary mask overlays  
- 📊 Instant display of available vs. occupied slots  
- 🔧 Modular architecture for scalability in urban infrastructure

---

## 🧰 Tech Stack

- **Python 3** 🐍  
- **OpenCV** 🎞️  
- **NumPy** 🔢  
- **Scikit-learn (SVC)** 🤖  
- **Scikit-image** 🖼️  
- **Matplotlib** 📈  

---

## 🗃️ Folder Structure

```bash
├── Data/                # Raw input video and binary slot mask
├── Train classifier/    # Classifier training scripts and model .pkl file
├── main.py              # Main pipeline for real-time inference
├── utils.py             # Utility functions (mask processing, classification, etc.)
├── requirements.txt     # Python dependencies

```

---
## ⚙️ How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rathod-0007/AI-Based-Parking-Lot-Detection_ComputerVision.git
   cd AI-Based-Parking-Lot-Detection_ComputerVision
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare your input video and mask:**
   - Add your video to Data/
   - Use a binary mask image (PNG) to mark parking slot regions

   
2. **Run detection:**
   ```bash
   python main.py
   ```
---

## 🚀 Future Enhancements

- 📱 **Mobile-friendly dashboard for real-time monitoring**  
- 🧩 **YOLOv8 or Deep Learning–based hybrid detection**  
- 🚘 **Edge deployment on devices like NVIDIA Jetson Nano**  
- 📡 **IoT-powered live slot availability display system**  
- 🔄 **Automated binary mask generation using CV algorithms**  

---

## 👨‍💻 Author

Developed and maintained by:

**Rathod Pavan Kumar Naik**  
🎓 IIIT Nagpur | B.Tech in Computer Science  
🌐 GitHub: [rathod-0007](https://github.com/rathod-0007)  
🔗 LinkedIn: [Rathod Pavan Kumar](https://www.linkedin.com/in/rathod-pavan-kumar/)  
📞 Phone: [+91 9618882298](tel:+919618882298)

---

## 📄 License
This project is open-source and available under the MIT License
