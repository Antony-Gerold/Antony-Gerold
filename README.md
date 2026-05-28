<h1 align="center">Antony Gerold Arockiasamy</h1>

<p align="center">
  <b>Medical Imaging AI Engineer</b><br>
  MEng Computer Engineering · University of Guelph · Imaging AI Lab (Prof. Eran Ukwatta)<br>
  Building grounded clinical-query AI with BiomedParse · <b>Open to full-time roles from October 2026</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/antony-gerold">LinkedIn</a> ·
  <a href="https://github.com/Antony-Gerold">GitHub</a>
</p>

---

I build computer-vision systems across medical imaging, autonomous driving, robotics, and industrial inspection — segmentation foundation models, pathology retrieval, anomaly detection, pose estimation. Two years prior as a Deep Learning Engineer at Appasamy Associates (OCT retinal imaging). My work is driven by one mission: **making medical AI accessible to clinicians who can't afford commercial systems**, especially in resource-limited settings.

What sets my work apart: the biggest gains in my projects came from finding bugs in **data and labels**, not from swapping architectures — a mask-alignment fix in EndoSAM (+0.486 Dice), a label-noise filter in DoTA (692,412 detections relabeled). I care about clinically-grounded ML: verification, abstention, and explainability over leaderboard chasing.

---

## Featured Projects

### 🫁 Medical Imaging — Endometriosis MRI Segmentation
<a href="https://github.com/Antony-Gerold/endosam-pelvic-segmentation-showcase">
  <img src="https://raw.githubusercontent.com/Antony-Gerold/endosam-pelvic-segmentation-showcase/main/report/figures/fig_gallery.png" width="100%">
</a>

**EndoSAM** — MedSAM decoder fine-tuning for uterus / ovary / endometrioma segmentation. **0.857 / 0.783 / 0.744 Dice.** First MedSAM evaluation on UT-EndoMRI; first endometrioma result. → [Repo](https://github.com/Antony-Gerold/endosam-pelvic-segmentation-showcase)

---

### 🚗 Autonomous Driving — Traffic Anomaly Detection
<a href="https://github.com/Antony-Gerold/dota-traffic-anomaly-detection-showcase">
  <img src="https://raw.githubusercontent.com/Antony-Gerold/dota-traffic-anomaly-detection-showcase/main/report/figures/pipeline_master_diagram.png" width="100%">
</a>

**DoTA** — object-level dashcam anomaly detection on 4,677 videos. YOLOv8m + ByteTrack + LightGBM + DINOv2 fusion. **STAUC 0.4966**, beating the published FOL-Ensemble baseline. → [Repo](https://github.com/Antony-Gerold/dota-traffic-anomaly-detection-showcase)

---

### 🦾 Robotics — 6DOF Pose Estimation
<a href="https://github.com/Antony-Gerold/pose-estimation-6dof-showcase">
  <img src="https://raw.githubusercontent.com/Antony-Gerold/pose-estimation-6dof-showcase/main/report/figures/fig5_combined.png" width="100%">
</a>

**6DOF Pose** — classical RGB-D pose estimation on Rutgers APC (24 objects). PnP + depth fusion, **21/24 robot-grade**. A study in why fusing two weak modalities beats either alone. → [Repo](https://github.com/Antony-Gerold/pose-estimation-6dof-showcase)

---

### 🏭 Industrial Inspection — Serial Number Recognition
<a href="https://github.com/Antony-Gerold/cast-metal-serial-recognition-showcase">
  <img src="https://raw.githubusercontent.com/Antony-Gerold/cast-metal-serial-recognition-showcase/main/figures/project_journey.png" width="100%">
</a>

**Cast-Metal Serial Recognition** — identifying parts by stamped serial numbers where OCR scores 0 %. MSER + HOG + KNN, **96.3 % accuracy**. → [Repo](https://github.com/Antony-Gerold/cast-metal-serial-recognition-showcase)

---

### 🔬 Also: PathoSearch & BiomedParse *(private — walkthrough on request)*

- **PathoSearch** — open-source AI pathology retrieval over 9 organs (PLIP + KNN). Discovered scanner-fingerprint bias in PLIP embeddings; built a text-anchor fix (84 % bias reduction → 97.7 % cross-institution). Presented at GES@Guelph 2026.
- **BiomedParse Clinical Query** *(MEng capstone, ongoing)* — natural-language clinical-query interface over BiomedParse with verified spine and abstention. External validation **Dice 0.965** on Shenzhen X-ray + CHAOS CT/MRI.

---

## Stack

`Python` · `PyTorch` · `OpenCV` · `scikit-learn` · `LightGBM` · `Transformers` · `trimesh` · `FastAPI` · `LaTeX` · `Compute Canada (DRAC)`
