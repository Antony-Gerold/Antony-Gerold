<h1 align="center">Antony Gerold Arockiasamy</h1>

<p align="center">
  Medical Imaging AI · MEng Computer Engineering @ University of Guelph · Imaging AI Lab<br>
  Open to full-time roles from October 2026
</p>

<p align="center">
  <a href="https://antony-gerold.github.io">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/antonygerold">LinkedIn</a>
</p>

---

I didn't start out in AI. I came from mechanical engineering, but the first time I saw a defect-testing system catch a flaw the human eye would miss, I was hooked, and I started teaching myself image annotation in my own time.

That curiosity got me onto a medical R&D team working on retinal OCT scans of the macula. Looking at real datasets, a healthy eye next to a patient's, taught me the lesson I still carry: the defect data isn't something to clean away, it's the whole point. A model can't tell sick from healthy unless you actually show it both.

My MEng has felt like one project building on the last. Below are the ones I can share publicly. The full code is private for the coursework ones (academic-integrity policy), but I'm always happy to walk through any of them.

## Projects

**EndoSAM, endometriosis MRI segmentation** ([repo](https://github.com/Antony-Gerold/endosam-pelvic-segmentation-showcase))
MedSAM decoder fine-tuning for uterus, ovary and endometrioma on pelvic MRI. 0.857 / 0.783 / 0.744 Dice. First MedSAM evaluation on pelvic endometriosis MRI, and the first endometrioma segmentation result. The biggest gain came from finding a data-alignment bug, not the model.

**DoTA, traffic anomaly detection** ([repo](https://github.com/Antony-Gerold/dota-traffic-anomaly-detection-showcase))
Object-level dashcam anomaly detection on 4,677 videos. YOLOv8m + ByteTrack + LightGBM + DINOv2 fusion. STAUC 0.4966 vs 0.4850 for the published FOL-Ensemble baseline, with frame AUC tied (0.7272 vs 0.7300).

**6DOF pose estimation** ([repo](https://github.com/Antony-Gerold/pose-estimation-6dof-showcase))
Classical RGB-D object pose estimation on Rutgers APC, no deep learning. PnP + depth fusion reached 21/24 objects acceptable (up from 17/24 with depth only): RGB finds where the object is, depth finds how it is oriented.

**Cast-metal serial recognition** ([repo](https://github.com/Antony-Gerold/cast-metal-serial-recognition-showcase))
Identifying cast-metal parts by their stamped serial numbers. MSER auto-ROI + HOG + KNN, 96.3% accuracy (96.4% ± 0.6% GroupKFold) on 1,872 images across 10 part types.

**Also (private for now):** PathoSearch, an open-source pathology retrieval tool across 9 organs, and my capstone, a natural-language clinical query system built on BiomedParse (0.965 Dice on external validation), now being extended to ovarian imaging.

## Background

Before my MEng I spent two years as a Deep Learning Engineer at Appasamy Associates, working on retinal OCT imaging. My through-line is wanting to make medical AI useful for clinics that can't afford commercial systems.

## Tools I work with

Python, PyTorch, OpenCV, scikit-learn, LightGBM, Transformers, trimesh, FastAPI, Compute Canada.
