<h1 align="center">Mollah Md Saif</h1>
<p align="center">
  Adjunct Lecturer, Department of Computer Science and Engineering, BRAC University<br/>
  Dhaka, Bangladesh
</p>

<p align="center">
  <a href="https://nekosaif.com"><img src="https://img.shields.io/badge/Website-nekosaif.com-1f6feb?style=flat-square&logo=googlechrome&logoColor=white"/></a>
  <a href="https://cse.nekosaif.com"><img src="https://img.shields.io/badge/Teaching-cse.nekosaif.com-1f6feb?style=flat-square&logo=googleclassroom&logoColor=white"/></a>
  <a href="https://linkedin.com/in/nekosaif"><img src="https://img.shields.io/badge/LinkedIn-nekosaif-0a66c2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:mollahmdsaif@gmail.com"><img src="https://img.shields.io/badge/Email-mollahmdsaif%40gmail.com-d14836?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://doi.org/10.1109/icra55743.2025.11127865"><img src="https://img.shields.io/badge/ICRA-2025-2ea043?style=flat-square&logo=ieee&logoColor=white"/></a>
</p>

## About

I build robots that work out where they are and how to move through crowded places, and I teach computer science at BRAC University in Dhaka.

Since August 2026 I have been an Adjunct Lecturer in the CSE department, running lab sections for data structures, algorithms and operating systems. Before that I spent a year as a full-time Research Assistant in robotics at the same university, working on perception and autonomy for places without much infrastructure. I have been part of BRACU Mongol Tori, the university rover team, since 2021, first as a contributor, then team lead, and now as technical advisor.

Most of my code is Python and C++ on ROS. Lately a fair amount of it is also LLM tooling.

## Teaching

Current term at BRAC University. Lab sections for:

| Course | Title |
| --- | --- |
| [CSE220](https://cse.bracu.ac.bd/course/view/CSE220) | Data Structure |
| [CSE221](https://cse.bracu.ac.bd/course/view/CSE221) | Algorithm Analysis and Design |
| [CSE321](https://cse.bracu.ac.bd/course/view/CSE321) | Operating Systems |

Routine, office hours, appointment booking and course policies are at [cse.nekosaif.com](https://cse.nekosaif.com). Students can book a slot there.

## Experience

| When | Role | Where |
| --- | --- | --- |
| Aug 2026 to present | Adjunct Lecturer | Department of CSE, BRAC University |
| Mar 2026 to present | Research Assistant, part-time (Samsung R&D Institute Bangladesh project) | BRAC University |
| Jul 2024 to present | Technical Advisor | BRACU Mongol Tori |
| Sep 2025 to Jul 2026 | Research Assistant (Robotics), full-time | BRAC University |
| Sep 2025 to Feb 2026 | Research Assistant, part-time | BRAC Skills Development Programme, BRAC University |
| Jul 2022 to Jun 2023 | Team Lead | BRACU Mongol Tori |
| Jul 2022 to Oct 2022 | Undergraduate Research Assistant | Laboratory of Space System Engineering and Technology |
| Nov 2021 to Apr 2022 | Student Instructor | BRAC University Computer Club |

The robotics RA role covered supervising undergraduate theses, building and benchmarking perception and navigation pipelines, and getting results ready for publication and field trials. The Samsung project is about mobile object tracking, video annotation pipelines and scene graph generation for dynamic FPS allocation. The Skills Development Programme work was a RAG-based job recommendation system, a CV parsing service with OCR, and a job scraping pipeline for the Bangladesh IT market.

## Research

My work sits where sensing meets decision. One sensor gives an incomplete and often wrong picture of the world. Several sensors disagree with each other. The problem I care about is building a picture that stays usable while they argue, in spaces that are busy and will not hold still.

Themes: autonomous navigation in crowded spaces, multi-sensor data fusion, and field robotics platforms that survive being used outdoors.

### Publication

Ananna, N. S., **Saif, Mollah Md**, Noor, M., Awishi, I. T., Rhaman, Md. Khalilur, Alam, Md. Golam Rabiul. *Autonomous Navigation in Crowded Space Using Multi-Sensory Data Fusion.* 2025 IEEE International Conference on Robotics and Automation (ICRA), Atlanta, USA. [DOI: 10.1109/icra55743.2025.11127865](https://doi.org/10.1109/icra55743.2025.11127865)

## Projects

| Project | What it is | Stack | When |
| --- | --- | --- | --- |
| Resilient autonomous navigation in hyper-congested urban environments | Hybrid imitation + reinforcement learning driving stack for Dhaka traffic. TransFuser fusion of LiDAR and camera, split computing over multi-RAT 5G, drive-by-wire EV, and the Dhaka-Dense Dataset (D3). | TransFuser, LiDAR, SAGE, MPTCP, SAM, VLM | Sep 2025 to present |
| [autonomous_nav](https://github.com/nekosaif/autonomous_nav) | ROS navigation with YOLOv8 detection, laser-based obstacle avoidance and target tracking, on top of move_base. | ROS Noetic/Humble, YOLOv8, Python | 2025 |
| Multi-Agent Pathfinder for fog robots | Multi-robot path planning on a fog robotics architecture. Modified CBS planner, YOLOv8 and AR-tag perception, DQN/PPO exploration. | ROS, Gazebo, ESP32, MARL | Nov 2023 to Mar 2024 |
| [secure-llm](https://github.com/nekosaif/secure-llm) | Self-hostable LLM inference where prompts and responses stay unreadable to anyone with disk, log or network access to the server. X25519 handshake, ChaCha20-Poly1305 envelope, OpenAI-shaped SDK and CLI. | llama.cpp, FastAPI, Python | 2026 |
| [rag-chatbot-custom-finetuned-model](https://github.com/nekosaif/rag-chatbot-custom-finetuned-model) | Fully local RAG chatbot with multi-user sessions, FAISS retrieval, DeepSeek R1 distilled model and a LoRA fine-tuning pipeline. | FAISS, LoRA, Python | 2025 |
| [langchain-chatbot-api](https://github.com/nekosaif/langchain-chatbot-api) | FAQ chatbot backend with FAISS retrieval, packaged in Docker and deployed on Render. | FastAPI, LangChain, OpenAI GPT | Jan 2025 |
| [flask-chatbot-demo](https://github.com/nekosaif/flask-chatbot-demo) | Small web frontend for the FAQ chatbot above. | Flask, Tailwind CSS, Heroku | Feb 2025 |
| [patient_entry_setup](https://github.com/nekosaif/patient_entry_setup) | Silent installer for PatientEntry medical software and its many dependencies, packaged as a WinRAR SFX. | PowerShell, SQL, Batch | Jul to Sep 2024 |
| BIRDS-X APRS payload | Automatic Packet Reporting System payload for a 2U CubeSat on the BIRDS open-source bus, from feasibility study to tested engineering model. | Embedded C, RF | Dec 2022 to Dec 2023 |
| Eshon-Sat | On-board computer module for a 1U CubeSat training kit. | C/C++ | Mar to Nov 2022 |
| [rover_inverse_kinematics](https://github.com/nekosaif/rover_inverse_kinematics) | 3-DOF arm inverse kinematics with Arduino firmware and a Python UI. | Arduino, Python | 2022 |
| [rover_control](https://github.com/nekosaif/rover_control) | ROS joystick setup and control notes for the rover. | ROS, Python | 2022 |

More on [nekosaif.com/projects](https://nekosaif.com/projects).

## Tools I use

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
</p>

| Area | Tools |
| --- | --- |
| Languages | Python, C/C++, Java, R, SQL, Bash, PowerShell |
| Deep learning and vision | PyTorch, TensorFlow, Keras, OpenCV, YOLO v5/v8/v11, Mask R-CNN, U-Net, Detectron2, SAM, DINO, Tesseract, PaddleOCR |
| LLMs | LangChain, LlamaIndex, RAG, FAISS, Pinecone, ChromaDB, Hugging Face, llama.cpp, LoRA fine-tuning |
| Reinforcement learning | DQN, PPO, multi-agent RL |
| Robotics | ROS, Gazebo, CBS path planning, inverse kinematics, sensor fusion, RTK-GPS |
| Embedded | Arduino, Raspberry Pi, ESP32, FreeRTOS, embedded C/C++ |
| MLOps and infra | Docker, CI/CD, AWS (EC2, S3, SageMaker), W&B, MLflow, model quantization, systemd |
| Hardware | PCB design in Autodesk Eagle, power electronics, CubeSat and APRS payloads |

## Awards

- 8th place, University Rover Challenge 2025. The Mars Society, Utah, USA.
- 16th place, University Rover Challenge 2023. The Mars Society, Utah, USA.
- 9th place, International Rover Challenge 2023. Space Robotics Society, Bengaluru, India.
- National Round Champion and Crew Award, KIBO Robot Programming Challenge 2022. JAXA, Tokyo, Japan.
- 21st place, International Rover Design Challenge 2022. Space Robotics Society.
- Champion, AUST Rover Challenge 2022. AUST Robotics Club, Dhaka.

## Education

BSc in Computer Science, BRAC University, 2020 to 2024. CGPA 3.65 / 4.00. VC's List for Academic Excellence in seven semesters, Dean's List in one.

Certificates: IBM Data Science Professional Certificate (2025), Deep Learning Specialization from DeepLearning.AI (2024), Electronics System and PCB Design from IEEE AESS (2022).

## GitHub

<p align="center">
  <a href="https://github.com/nekosaif">
    <img height="165" src="https://github-readme-stats.vercel.app/api?username=nekosaif&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&title_color=1f6feb&icon_color=1f6feb&text_color=c9d1d9&bg_color=0d1117"/>
  </a>
  <a href="https://github.com/nekosaif">
    <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nekosaif&layout=compact&langs_count=8&hide_border=true&title_color=1f6feb&text_color=c9d1d9&bg_color=0d1117"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/nekosaif">
    <img src="https://streak-stats.demolab.com?user=nekosaif&hide_border=true&background=0d1117&stroke=0d1117&ring=1f6feb&fire=1f6feb&currStreakLabel=1f6feb&sideLabels=c9d1d9&currStreakNum=c9d1d9&dates=c9d1d9&sideNums=c9d1d9"/>
  </a>
</p>
