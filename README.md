# Muhammad Fahad Hassan

**AI/ML Engineer** · Computer Vision · Robotics & Autonomous Systems · Medical AI

MS in AI & Autonomous Systems &nbsp;|&nbsp; Islamabad, Pakistan &nbsp;|&nbsp; muhammadfahadhassan01@gmail.com

I'm an engineer who spent a year running production network infrastructure for 10,000+ users, then pivoted fully into AI. That background — real systems, real uptime requirements, real debugging under pressure — shapes how I build: I care about things that actually work, not just things that train.

Right now I'm focused on **computer vision for healthcare** and **autonomous navigation**, with deployed projects in both areas.

---

## Deployed Projects

### 🩺 PsoriScan AI &nbsp;·&nbsp; [Live Demo](https://huggingface.co/spaces/MFH-001/PsoriScan-AI) &nbsp;·&nbsp; [Repo](https://github.com/mfh-001/PsoriScan-AI)
Automated psoriasis plaque segmentation and PASI-inspired severity scoring from dermoscopic images. U-Net with EfficientNet-B3 encoder achieves **Dice 0.9479** on validation. Severity classifier takes both visual features and computed coverage % as inputs, designed to mirror how dermatologists actually assess severity. Deployed on Hugging Face Spaces with input validation, heatmap overlay, and a PASI-proxy scoring breakdown.

`PyTorch` `segmentation-models-pytorch` `EfficientNet` `OpenCV` `Streamlit` `ISIC 2018` `HAM10000`

### 🔬 MediScan AI &nbsp;·&nbsp; [Live Demo](https://huggingface.co/spaces/MFH-001/MediScan-AI) &nbsp;·&nbsp; [Repo](https://github.com/mfh-001/AI-Medical-Assistant)
Multimodal medical diagnostic tool combining U-Net skin lesion segmentation (Dice 0.90, Jaccard 0.85) with a RAG-inspired Llama 3.2 3B Instruct conversational layer. Solved catastrophic forgetting during BioGPT fine-tuning by switching to instruction-tuned Llama with a structured medical knowledge base. Deployed with fuzzy query matching for clinical misspelling tolerance.

`PyTorch` `Llama 3.2` `PEFT/LoRA` `BitsAndBytes` `Streamlit` `HAM10000`


### 🗺️ Visual SLAM vs GPS &nbsp;·&nbsp; [Repo](https://github.com/mfh-001/ORB-SLAM3-GPS-Comparison)
Monocular SLAM navigation pipeline comparing ORB-SLAM3 trajectory against mobile GPS ground truth. **26.3 cm mean alignment error** over full test sequences. Camera calibrated with OpenCV chessboard method; Umeyama similarity transformation applied for SLAM-to-UTM coordinate alignment. Full temporal synchronisation via timestamp interpolation.

`ORB-SLAM3` `C++` `OpenCV` `NumPy` `SciPy` `pyproj` `Ubuntu`


### 🤖 Autonomous Vacuum & Air Quality Robot &nbsp;·&nbsp; [Repo](https://github.com/mfh-001/ROS2-Visual-Navigation-Coordinate-Transformation)
Hardware robot with ultrasonic sensor navigation (95% accuracy across 100 sqm), real-time DHT22 environmental monitoring, mobile app remote control, and ML-based decision logic for zone-targeted cleaning. Data accuracy within ±2%.

`ROS2` `Arduino` `Sensor Fusion` `ML decision logic`

---

## Skills

| Area | Tools |
|---|---|
| ML & Computer Vision | PyTorch · TensorFlow · U-Net · EfficientNet · LoRA/PEFT · Image segmentation · Sensor fusion |
| Robotics | ROS2 · ORB-SLAM3 · Coordinate transforms · SLAM · Autonomous navigation |
| Deployment | Streamlit · Hugging Face Spaces · Docker · AWS · Terraform · CI/CD |
| Infrastructure | TCP/IP · VLANs · VPNs (L2/L3) · MPLS · GPON/FTTH · Cisco · Juniper · SolarWinds |
| Languages | Python · C++ · MATLAB |

---

## Background

Before AI, I spent a year as an **Operations Engineer at an ISP**, managing network operations for 10,000+ subscribers across GPON infrastructure, maintaining 99% uptime SLA, and handling escalated Cisco/Juniper configurations and L2/L3 VPN circuits. 

That infrastructure experience is why I'm drawn to problems where the gap between "works in a notebook" and "works reliably" actually matters.

---
*Can be contacted at muhammadfahadhassan01@gmail.com*
