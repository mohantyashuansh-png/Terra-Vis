TERRA-VIS: Tactical Terrain Analysis System

Download Full Project
Due to file size limits, the full project (including the trained AI models and environment) is hosted on Google Drive.

>>[CLICK HERE TO DOWNLOAD FULL PROJECT & MODELS] ==>(https://drive.google.com/drive/folders/1UI7yNQPKdZ3H-NmgkZymSHGmzwSXhbHA?usp=sharing)

---
Setup & Installation

>> 1. Prerequisites
* Python 3.8 or higher
* NVIDIA GPU (Recommended for real-time inference)

>>2. Install Dependencies
Navigate to the project folder in your terminal and install the required libraries:

```bash
pip install -r requirements.txt
---

#How to Run:
start backend:
Run the following commands on termainal:
```bash
cd "desert seg"
python api/server.py --ckpt outputs/checkpoints/best_model.pth --variant b2
(wait until u see the server starts)
---
start frontend:
double click on index.html in root folder--Terra-Vis/index.html

