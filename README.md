TEKNOFEST 2022 UAV Competition
Welcome to the TEKNOFEST 2022 UAV Competition repository! This repository contains the resources, code, and documentation related to the participation in the TEKNOFEST 2022 UAV (Unmanned Aerial Vehicle) competition. It demonstrates the integration of state-of-the-art technologies such as YOLOv5 for object detection in UAV applications.

📂 Repository Structure
1. YOLO-V5
Contains configurations and implementations for YOLOv5.
Includes custom model training, dataset preparation, and inference scripts for UAV-based object detection.
2. .gitattributes
Specifies file attribute configurations for Git.
3. .gitignore
Defines ignored files to maintain a clean repository and avoid unnecessary uploads.
🚀 Key Features
YOLOv5 Integration: Utilized for real-time object detection and recognition.
Custom Dataset: Adapted to UAV-specific requirements for precision in aerial imagery.
Scalable Codebase: Optimized for deployment on UAVs with limited computational power.
🛠️ Installation
Clone the repository:

bash
Kodu kopyala
git clone https://github.com/cinarolog/TEKNOFEST-2022-UAV-COMPETITION.git
cd TEKNOFEST-2022-UAV-COMPETITION
Install required libraries:

bash
Kodu kopyala
pip install -r requirements.txt
Set up the YOLOv5 model:

Download the pretrained weights or train your custom model using provided scripts.
Run the UAV object detection script:

bash
Kodu kopyala
python detect.py --source your_video.mp4 --weights best.pt --conf 0.5
🤝 Contributions
Contributions are welcome! Feel free to fork this repository, propose improvements, or add new features. Submit a pull request to contribute to the development.

📜 License
This repository is licensed under the MIT License. See the LICENSE file for details.

📧 Contact
For inquiries or feedback:

Author: Muhammet ÇINAR
Email: mhmmtcnr81@gmail.com
Let's build innovative UAV solutions together! 🚁
