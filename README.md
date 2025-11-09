# VisionCart-Product-Computer-Vision
VisionCart is an AR-based computer vision system that uses YOLOv8 and MongoDB to detect, track, and remember objects in real time. It enables interactive inventory management by allowing users to add items via webcam and stores them persistently across sessions.

# 🤖 VisionCart

**VisionCart** is a YOLOv8-powered Computer Vision system designed to empower **warehouse robots** to automatically **scan, identify, and add items to digital carts**, enabling faster and more efficient **customer order fulfillment**.

---

## 🚀 Overview
VisionCart combines the accuracy of **YOLOv8 object detection** with the reliability of **MongoDB-based memory**, creating a real-time perception system that not only detects items but also remembers and tracks them intelligently across sessions.  
It’s the foundation for intelligent automation in modern logistics and e-commerce.

---

## 🧠 Key Features
- **Autonomous Scanning:** Real-time object detection through YOLOv8 integrated with OpenCV.  
- **Smart Memory:** Persistent item tracking and recognition powered by MongoDB.  
- **Digital Cart Integration:** Seamless item addition and retrieval for automated warehouse workflows.  
- **High Accuracy & Speed:** Optimized for real-time inference on edge or robotic systems.  
- **Modular Architecture:** Flexible to deploy in AR interfaces or robotic systems.

---

## 🧩 System Components
| Component | Technology |
|------------|-------------|
| Object Detection | YOLOv8 (Ultralytics) |
| Computer Vision | OpenCV |
| Database | MongoDB |
| Language | Python |
| Environment | Jupyter Notebook / Colab |

---

## ⚙️ How It Works
1. The robot’s camera captures a continuous video feed.  
2. YOLOv8 detects objects frame-by-frame in real time.  
3. Detected items are logged into MongoDB, forming a persistent inventory record.  
4. When an item reappears, it’s recognized as **already added** to the digital cart.  
5. The result — efficient, autonomous item handling and faster order processing.

---

## 🧾 Included Files
| File | Description |
|------|--------------|
| `VisionCart_Product_CV_Project.ipynb` | Main implementation notebook |
| `Research Report of VisionCart Product CV Project.pdf` | Research report and results |
| `VisionCart Product Computer Vision System Design.pdf` | System architecture and design overview |

---

## 🔮 Future Enhancements
- Integration with robotic arm systems for physical item picking  
- YOLO-NAS upgrade for better small-object detection  
- Improved occlusion and lighting robustness  
- Warehouse simulation testing for large-scale automation  

---

## 👨‍💻 Author
**Ujjwal Dubey**  
AI Product Manager & Researcher

---

⭐ *If you found VisionCart interesting, consider starring the repository!*
