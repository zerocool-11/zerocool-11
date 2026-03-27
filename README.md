# Hi, I'm Yash Kumar 👋
### Machine Learning Engineer · MLOps · Computer Vision · Robotics & AI

I build production ML systems end to end — from training and versioning models to containerising, deploying, and monitoring them in the real world. My background sits at the intersection of **MLOps infrastructure** and **robotics**, which is where I want to spend the next stage of my career.

I hold an **MSc in Robotics and Artificial Intelligence** from Cardiff Metropolitan University, and have hands-on experience with mobile robots (TurtleBot3, ROS) and social robots (NAO). Outside of robotics, I've shipped production systems across computer vision, NLP, IoT edge pipelines, and LLM evaluation.

---

## 🔧 What I Do

- **MLOps & Deployment** — End-to-end ML pipelines: experiment tracking with MLflow, containerisation with Docker, CI/CD via GitHub Actions, deployment to AWS (Lambda, Fargate, SageMaker, EC2)
- **Computer Vision** — Real-time inference systems using YOLOv4/v5, OpenPose, MediaPipe, FaceNet — deployed on live camera feeds in production
- **LLMs & NLP** — RAG pipelines with GPT-4o, LangChain, and vector databases (Pinecone); multilingual translation; topic modelling; LLM evaluation and failure mode analysis (Google)
- **IoT & Edge** — Edge-to-cloud pipelines using Raspberry Pi, serial communication, AWS IoT Core, Lambda, and GraphQL backends
- **Robotics** — ROS-based path planning with TurtleBot3, NAO robot application development, gesture-controlled drone using MediaPipe + DJI API

---

## 🚀 Selected Projects

### 🛡️ PPE Detection API — Full MLOps Pipeline
Real-time hard hat and safety vest detection from industrial CCTV feeds, with a complete CI/CD deployment pipeline.
- Trained YOLOv4 on a custom dataset · ~96% mAP@IoU0.5 · sub-100ms CPU inference
- MLflow for experiment tracking and model versioning · weights stored in S3
- GitHub Actions → Docker → AWS ECR → ECS Fargate · zero-downtime rolling deployment via ALB
- `Python` `YOLOv4` `MLflow` `Docker` `GitHub Actions` `AWS Fargate` `FastAPI`

---

### 🔍 Shoplifting Detection — Multi-Model CV Pipeline
Behaviour-based shoplifting detection from live CCTV using object detection + pose estimation + a scoring engine.
- YOLOv5 for person/bag/trolley detection on a custom dataset
- OpenPose for hand movement tracking — cropped bounding box regions fed to pose model for accuracy
- Cumulative scoring logic (backpack +30, aisle reach +50, bag interaction +50, trolley -50) — alerts at threshold 100
- Containerised with Docker · deployed on-premises on client machines
- `Python` `YOLOv5` `OpenPose` `Docker` `OpenCV`

---

### 🤖 AI-Enabled Drone Controller — Robotics POC
Closed-loop human-machine interface: control a DJI drone using only hand gestures and voice commands.
- MediaPipe hand keypoints → gesture classifier → drone commands (takeoff, land, directional movement)
- Google Speech-to-Text for voice command fallback
- Demonstrates the full control loop: sensor input → model inference → physical actuation
- `Python` `MediaPipe` `DJI API` `Google STT`

---

### 🗑️ Turn System — Smart Bin IoT Pipeline
Edge-to-cloud IoT pipeline for a smart bin system that rewards users for returning cups.
- Configured Raspberry Pi to communicate with bin hardware over serial (TTY) — lid state, battery, bin status
- Published state updates to AWS IoT Core via MQTT · Lambda triggered on incoming messages
- Python backend parsed IoT messages and updated bin state in GraphQL database
- `Raspberry Pi` `Serial/TTY` `AWS IoT Core` `AWS Lambda` `Python` `GraphQL`

---

### 🏥 CarePath — Healthcare Document Parsing API
Serverless API to parse and extract structured data from clinical healthcare records (CCDA, ADT).
- FastAPI endpoints for structured data extraction · MongoDB for persistence
- Containerised with Docker · deployed to AWS Lambda using Mangum (ASGI wrapper)
- Full DevOps cycle: local dev → Docker → Lambda
- `FastAPI` `Docker` `AWS Lambda` `MongoDB` `Python`

---

### 🧠 RAG Pipeline with GPT-4o and LangChain
Retrieval-Augmented Generation pipeline for document Q&A with conversational agents.
- GPT-4o + LangChain + LlamaIndex · Pinecone vector database for embedding storage and retrieval
- 40% reduction in document processing time · sub-100ms response latency
- FastAPI endpoints · deployed on AWS Lambda
- `Python` `GPT-4o` `LangChain` `Pinecone` `FastAPI` `AWS Lambda`

---

### 👤 Face Recognition API
Rebuilt a broken Siamese network solution from scratch using FaceNet with triplet loss.
- Learns a new face from just 2–3 sample images — no full model retraining needed
- REST API with FastAPI: enrolment endpoint + prediction endpoint
- Deployed on AWS Lambda · containerised with Docker
- `FaceNet` `Triplet Loss` `FastAPI` `Docker` `AWS Lambda`

---

### 🌐 Multilingual Translation API
Translation microservice for English ↔ Malay using Hugging Face M2M100 multilingual models.
- FastAPI endpoints for batch translation · tokenisation and language ID forcing for accurate output
- Containerised and deployed into client server environment
- `Python` `Hugging Face` `M2M100` `FastAPI` `Docker`

---

### 🔬 NAO Psychotherapist Robot *(MSc — Cardiff Metropolitan University)*
Psychotherapist assistant application built on the NAO humanoid social robot platform.
- NAOqi SDK for robot behaviour, speech, and movement control
- Added computer vision for interaction and adaptive response
- `NAO` `NAOqi SDK` `Python` `Computer Vision`

---

### 🐢 TurtleBot3 Path Planning with ROS *(MSc — Cardiff Metropolitan University)*
Mobile robot path planning using ROS and Python.
- ROS node communication, sensor data flow, and Python-based navigation control
- Hands-on experience with the ROS ecosystem directly applicable to robotics data pipelines
- `TurtleBot3` `ROS` `Python`

---

## 🛠️ Tech Stack

**MLOps & DevOps**

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![mlflow](https://img.shields.io/badge/mlflow-%23d9ead3.svg?style=for-the-badge&logo=numpy&logoColor=blue)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

**Cloud — AWS**

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

**ML & AI**

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![YAML](https://img.shields.io/badge/yaml-%23ffffff.svg?style=for-the-badge&logo=yaml&logoColor=151515)

**Robotics & Edge**

![Raspberry Pi](https://img.shields.io/badge/-RaspberryPi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)
![ROS](https://img.shields.io/badge/ros-%230A0FF9.svg?style=for-the-badge&logo=ros&logoColor=white)

**Databases**

![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

**Version Control**

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---

## 📊 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=zerocool-11&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=zerocool-11&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=zerocool-11&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---

## 🌐 Socials

[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/ai__nerd)
[![Medium](https://img.shields.io/badge/Medium-12100E?logo=medium&logoColor=white)](https://medium.com/@zerocool-11)
[![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/zeroday1202)
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?logo=YouTube&logoColor=white)](https://youtube.com/@ai__projects11)

---

[![](https://visitcount.itsvg.in/api?id=zerocool-11&icon=0&color=0)](https://visitcount.itsvg.in)
