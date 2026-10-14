LIVE URL = https://ocean-police.onrender.com/?lat=20.4857&lon=73.5808&zoom=5.25&min_confidence=0.9&classes=1_2_3&date_range=2025-09-28_2026-09-28&quicklooks=1﻿# oil-detection-project-



 # 🛢️🌊 Oil Slick Detection System

<div align="center">

## 🚀 AI-Powered Oil Spill / Oil Slick Detection Platform

**Detect • Analyze • Visualize • Protect 🌊**

An intelligent computer-vision based system designed to detect and analyze potential oil slicks from images using Artificial Intelligence, Machine Learning and modern image-processing techniques.

</div>

---

## 🌊 About The Project

Oil spills are one of the most serious environmental threats to marine ecosystems. They can damage marine life, contaminate water resources, affect coastal regions and create long-term environmental and economic consequences.

The **Oil Slick Detection System** aims to provide an intelligent and automated solution for identifying potential oil slick regions from images.

Instead of depending entirely on manual inspection, the system uses an AI-driven pipeline to process images, analyze visual patterns and generate detection results.

The project is designed with a **modular, scalable and production-oriented architecture**, separating the frontend, backend, AI/ML models, data processing, testing, experimentation and deployment components.

### 🎯 Main Goal

> **Detect oil slicks faster, simplify analysis and support better environmental monitoring. 🌊🌱**

---

# ✨ Key Features

- 🛢️ **Automated Oil Slick Detection**
- 🤖 **AI / Machine Learning based analysis**
- 👁️ **Computer Vision based image processing**
- 🖼️ **Image upload and analysis**
- 🎯 **Oil slick region identification**
- 📊 **Detection result visualization**
- 🖥️ **Interactive frontend interface**
- ⚙️ **Backend API architecture**
- 🧠 **Dedicated ML/DL model layer**
- 📓 **Jupyter Notebook based experimentation**
- 🧪 **Testing infrastructure**
- 📈 **Project reports and analysis**
- 🐳 **Docker support**
- 🔐 **Environment configuration support**
- 🔄 **Modular and scalable architecture**
- 🌍 **Environmental monitoring oriented design**

---

# 🏗️ System Architecture

```text
                         🌊 OIL SLICK DETECTION SYSTEM
                                      │
                                      ▼
                         ┌────────────────────────┐
                         │       👤 USER          │
                         │   Upload / Input Image │
                         └────────────┬───────────┘
                                      │
                                      ▼
                         ┌────────────────────────┐
                         │      🖥️ FRONTEND       │
                         │                        │
                         │  • Image Upload        │
                         │  • Preview              │
                         │  • User Interaction     │
                         │  • Result Visualization │
                         └────────────┬───────────┘
                                      │
                                      ▼
                         ┌────────────────────────┐
                         │      ⚙️ BACKEND        │
                         │                        │
                         │  • API Handling         │
                         │  • Request Processing   │
                         │  • Model Communication  │
                         │  • Response Generation  │
                         └────────────┬───────────┘
                                      │
                                      ▼
                         ┌────────────────────────┐
                         │    🧹 PREPROCESSING     │
                         │                        │
                         │  • Image Validation     │
                         │  • Resizing              │
                         │  • Normalization         │
                         │  • Image Preparation     │
                         └────────────┬───────────┘
                                      │
                                      ▼
                         ┌────────────────────────┐
                         │       🧠 ML / DL        │
                         │         MODEL           │
                         │                        │
                         │  • Feature Analysis     │
                         │  • Pattern Recognition  │
                         │  • Model Inference      │
                         └────────────┬───────────┘
                                      │
                                      ▼
                         ┌────────────────────────┐
                         │     🛢️ DETECTION        │
                         │                        │
                         │  Oil Slick Identification│
                         │  / Classification       │
                         └────────────┬───────────┘
                                      │
                                      ▼
                         ┌────────────────────────┐
                         │     📊 RESULTS          │
                         │                        │
                         │  • Prediction           │
                         │  • Visualization        │
                         │  • Analysis              │
                         └────────────────────────┘🔄 Complete Project Workflow
🖼️ Input Image
       │
       ▼
📤 Image Upload
       │
       ▼
🧹 Image Preprocessing
       │
       ▼
🔍 Feature / Pattern Analysis
       │
       ▼
🧠 AI / ML Model Inference
       │
       ▼
🛢️ Oil Slick Detection
       │
       ▼
📊 Result Generation
       │
       ▼
🖼️ Visualization
       │
       ▼
🌊 Environmental Insight

🧩 Project Architecture
The project is organized into independent modules to make development, testing, maintenance and deployment easier.
Oil-slick-detection-SIH-main/
│
├── 📁 .github/
│   └── GitHub configuration and workflows
│
├── 📁 backend/
│   └── Backend services, APIs and application logic
│
├── 📁 frontend/
│   └── Frontend interface and user interaction
│
├── 📁 models/
│   └── Machine Learning / Deep Learning models
│
├── 📁 notebooks/
│   └── Data analysis, experimentation and research
│
├── 📁 reports/
│   └── Project reports and experiment documentation
│
├── 📁 scripts/
│   └── Utility and automation scripts
│
├── 📁 src/
│   └── Core source code and detection pipeline
│
├── 📁 tests/
│   └── Automated tests and validation
│
├── 📄 .env.example
│   └── Environment variable template
│
├── 📄 .gitignore
│   └── Ignored files and directories
│
├── 📄 DATA_LICENSES.md
│   └── Dataset and licensing information
│
├── 📄 DECISIONS.md
│   └── Technical decisions and architecture notes
│
├── 📄 Dockerfile
│   └── Docker container configuration
│
├── 📄 IMPLEMENTATION_PROMPT.md
│   └── Project implementation documentation
│
├── 📄 LICENSE
│   └── Project license
│
├── 📄 OCEAN_POLICE_BLUEPRINT.md
│   └── System/project blueprint
│
├── 📄 PROGRESS.md
│   └── Development progress
│
└── 📄 README.md
    └── Project documentation

🖥️ Frontend Layer
The frontend provides the user-facing interface of the application.
Responsibilities
- 📤 Upload images
- 🖼️ Preview uploaded images
- 🔄 Communicate with backend APIs
- 📊 Display detection results
- 🎯 Present prediction information
- 🎨 Provide an easy-to-use interface
The frontend acts as the primary interaction layer between the user and the AI detection system.
⚙️ Backend Layer
The backend works as the core application and communication layer.
Responsibilities
- 🔌 API management
- 📥 Receiving image inputs
- 🧹 Processing requests
- 🧠 Communicating with ML models
- 📤 Returning prediction results
- ⚠️ Input validation and error handling
- 🔄 Connecting frontend with AI services
🧠 AI / Machine Learning Layer
The AI layer is responsible for analyzing image data and identifying patterns associated with oil slicks.
The general AI pipeline includes:
Input Image
     ↓
Image Preprocessing
     ↓
Feature Extraction / Representation
     ↓
Model Inference
     ↓
Prediction
     ↓
Oil Slick Detection

Depending on the implemented model, this layer can support different computer-vision approaches such as classification, segmentation or object/local-region detection.
🧹 Image Processing Pipeline
Before an image is analyzed, it can pass through preprocessing stages such as:
- 📐 Image resizing
- 🎨 Format conversion
- ⚖️ Normalization
- 🧹 Noise handling
- 🔍 Input validation
- 🧠 Model-specific preprocessing
This ensures that the input is prepared in a format suitable for the AI model.
📊 Detection & Visualization
After model inference, the application generates a result that can be presented through the frontend.
Possible outputs include:
- 🛢️ Oil slick detected / not detected
- 🎯 Detected regions
- 📊 Prediction information
- 🖼️ Annotated images
- 📈 Model confidence / analysis information
The visualization layer makes AI predictions easier for users to understand.
📓 Research & Experimentation
The notebooks/ directory provides a dedicated environment for experimentation.
It can be used for:
- 📊 Exploratory Data Analysis
- 🧹 Data preprocessing
- 🔬 Feature analysis
- 🧠 Model experimentation
- 📈 Performance evaluation
- 🧪 Testing different approaches
- 📉 Error analysis
This separation allows research work to remain organized without affecting the main application pipeline.
🧪 Testing
The tests/ directory contains testing and validation components.
Testing helps ensure:
- ✅ Backend reliability
- ✅ API correctness
- ✅ Input validation
- ✅ Model integration
- ✅ Detection pipeline stability
- ✅ Application reliability
Example:
pytest

📁 Reports & Documentation
The reports/ directory is used to maintain project-related analysis and documentation.
It can contain:
- 📊 Experiment results
- 📈 Model performance analysis
- 🧪 Testing reports
- 📝 Technical documentation
- 🔍 Research findings
🛠️ Technology Stack
Category	Technology
🐍 Programming	Python
🤖 AI / ML	Machine Learning / Deep Learning
👁️ Computer Vision	Image Processing
🖥️ Frontend	Web-based Frontend
⚙️ Backend	Python Backend / API
📓 Research	Jupyter Notebook
🐳 Deployment	Docker
🔧 Version Control	Git
☁️ Repository	GitHub
🧪 Testing	Automated Testing
