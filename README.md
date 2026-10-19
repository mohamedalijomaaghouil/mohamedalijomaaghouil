# Mohamed Ali Jomaa Ghouil

**Élève ingénieur Robotique & Mécatronique** — double diplôme SIGMA Clermont (Clermont Auvergne INP) / ENISo

🔎 **Je recherche un stage de fin d'études (PFE) de 6 mois à partir du 7 mars 2027** en robotique, mécatronique ou automatique. Mobile partout en France.

<a href="https://www.linkedin.com/in/mohamed-ali-jomaa-ghouil/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:mohamedalijomaaghouil@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

---

## 🤖 Projets

### [ROBOTA-SUDOE — Commande en admittance d'un UR5e sous ROS 2](https://github.com/mohamedalijomaaghouil/robota-sudoe-ur5e-ros2)
*Stage, CiTIUS — Université de Saint-Jacques-de-Compostelle, Espagne (05/2026 – 09/2026)*

- Contrôleur en admittance en **C++** (125 Hz) sous **ROS 2 Jazzy** pour guider à la main un bras **Universal Robots UR5e**
- Intégration d'une pince **SCHUNK EGK 50** (nœud Python, socket TCP)
- Enregistrement et rejeu synchronisé bras + pince d'une démonstration de 242 s : erreur de suivi **0,37 mrad RMS**, erreur finale de pince 0,06 mm

### [ROBOTA-SUDOE — Capteur d'effort OnRobot HEX-E v2 (EtherCAT)](https://github.com/mohamedalijomaaghouil/robota-sudoe-hex-e-v2)
- Intégration du capteur 6 axes en **EtherCAT** et publication ROS 2
- Diagnostic d'une erreur de décodage dans les octets bruts (mesures ×100 trop faibles), puis correction du driver
- Calibration validée sur un jeu de données indépendant : erreur moyenne **2,77 N → 0,69 N**

### [Inspection robotisée de défauts — UR3e, ROS 2](https://github.com/mohamedalijomaaghouil/defect-detection-robotics)
*Projet en équipe de 3, semestres 7 et 8, SIGMA Clermont — projet européen REMAIN-SUDOE (2025 – 2026)*

Un UR3e équipé d'une caméra **Intel RealSense** photographie une chaussure sous plusieurs angles pour en détecter les défauts. **Ma partie :**
- Localisation 3D de la pièce dans l'image de profondeur : séparation du sol, filtrage morphologique et des contours (**OpenCV**), position et orientation, projection en 3D (nœud **ROS 2** en Python)
- Image de contrôle en temps réel (boîte englobante, distance, orientation) pour suivre l'inspection

### [FOLLOW-ME — Robot suiveur de personne](https://github.com/mohamedalijomaaghouil/follow-me-person-following-robot)
*Projet de 2e année, ENISo (2025)*

- Détection de la personne par estimation de pose (**MediaPipe**) et mesure de distance avec une caméra **Intel RealSense D435i**
- Démarrage et arrêt du suivi par geste de la main, distance de sécurité d'environ 2 m
- Commande des vitesses du robot par **Modbus TCP** · [Vidéo](https://youtu.be/bcdjbf4g2AU)

---

## 🛠️ Compétences

- **Robotique :** ROS 2, ros2_control, Universal Robots (UR5e, UR3e), KUKA, capteurs d'effort, vision
- **Programmation :** C++, Python (NumPy, Pandas, Matplotlib, OpenCV), Linux, Git
- **IA :** Machine Learning, Deep Learning avec PyTorch (cours en cours à SIGMA Clermont), certifications NVIDIA Deep Learning et Computer Vision
- **Simulation & CAO :** MATLAB/Simulink, Simscape, CATIA, SOLIDWORKS (certifié CSWA)
- **Automatisme :** automates programmables, EtherCAT, Modbus TCP
- **Langues :** français, anglais (C1, TOEIC 955), arabe, espagnol (A2)

## 🎓 Formation

- **SIGMA Clermont** — Diplôme d'ingénieur, Robotique, Mécanismes et Systèmes (2025 – 2027), rang 3/182 au semestre 7
- **ENISo** — Diplôme d'ingénieur, Mécatronique (2023 – 2025)
