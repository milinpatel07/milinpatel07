<div align="center">

<img src="assets/hero.svg" width="100%" alt="Milin Patel, PhD candidate at Hochschule Kempten, working on AI safety and security for automated driving. An animated LiDAR scene shows a runtime monitor reacting as detectors disagree about a pedestrian.">

<br>

<a href="https://doi.org/10.1007/978-3-032-35506-5_55"><img src="https://img.shields.io/badge/WAISE_2026-Springer_LNCS-5ad1f0?style=for-the-badge&labelColor=0a1020" alt="WAISE 2026 paper, Springer LNCS"></a>
<a href="https://milinpatel07.github.io/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case/"><img src="https://img.shields.io/badge/Integrated_GSN_argument-explore-3ddc97?style=for-the-badge&labelColor=0a1020" alt="Explore the integrated GSN argument"></a>
<a href="https://milinpatel07.github.io/lidar-performance-target-applicability/story.html"><img src="https://img.shields.io/badge/The_idea_in_2_minutes-read-ffb547?style=for-the-badge&labelColor=0a1020" alt="Read the applicability test story"></a>
<!-- Add your profiles here once you send the IDs:
<a href="https://orcid.org/0000-0000-0000-0000"><img src="https://img.shields.io/badge/ORCID-0000--0000--0000--0000-a6ce39?style=for-the-badge&logo=orcid&logoColor=white&labelColor=0a1020" alt="ORCID"></a>
<a href="https://www.researchgate.net/profile/YOUR-NAME"><img src="https://img.shields.io/badge/ResearchGate-profile-00ccbb?style=for-the-badge&logo=researchgate&logoColor=white&labelColor=0a1020" alt="ResearchGate"></a>
<a href="https://www.linkedin.com/in/YOUR-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0a1020" alt="LinkedIn"></a>
-->

<sub><b><a href="#research">Research</a></b> · <b><a href="#publications">Publications</a></b> · <b><a href="#projects">Projects</a></b> · <b><a href="#teaching-and-outreach">Teaching</a></b> · <b><a href="#toolbox">Toolbox</a></b> · <b><a href="#contact">Contact</a></b></sub>

</div>

---

### Hi, I'm Milin

I'm a PhD candidate at the **Institute for Driver Assistance and Connected Mobility (IFM), Hochschule Kempten**, supervised by Prof. Dr. Rolf Jung.

An automated vehicle has to *see* before it can drive, and today that seeing is done by neural networks that learned from data rather than following a specification. My research asks a practical question:

> **How do you show that a learned perception system is safe and secure enough to release, and keep showing it after the model is updated?**

The standards that apply (ISO 26262, ISO 21448, ISO/SAE 21434 and ISO/PAS 8800) each answer part of that question in their own terms. I work on joining them into one lifecycle and one argument, and on producing the evidence that argument needs, from hazard analysis to monitoring in the field.

---

## Research

<div align="center">
<img src="assets/lifecycle.svg" width="100%" alt="The six-phase lifecycle assurance model: concept and requirements, design and training, verification and validation, integration and deployment, operation and monitoring, modification and re-assurance.">
</div>

<br>

My dissertation, ***Lifecycle Assurance Framework for Highly Automated Driving with AI Components in Compliance with Safety and Cybersecurity Standards (LAF-HAD)***, follows one LiDAR-based 3D object detector through six phases. For each phase it states the activities, the evidence they produce and the clause that asks for them.

<div align="center">
<img src="assets/highlights.svg" width="100%" alt="Research at a glance: four standards in one argument; nine goals in the integrated GSN argument; seven decision points and five findings; three audiences taught.">
</div>

<details>
<summary><b>How each project fits the lifecycle</b> (click to expand)</summary>
<br>

| Phase | Question it answers | Where I work on it |
|---|---|---|
| 1 · Concept and requirements | What can go wrong, and how bad is it? | Hazard analysis (HARA) and threat analysis (TARA) for a pedestrian emergency-braking function, in my teaching material |
| 2 · Design and training | Is the data fit for purpose? | Data lifecycle in the framework |
| 3 · Verification and validation | Does the detector meet its targets, also in rain, fog or at range? | **SOTIF perception benchmark**: 14 sensor-degradation types. **[Applicability test](https://github.com/milinpatel07/lidar-performance-target-applicability)**: does a threshold still hold under a triggering condition? |
| 4 · Integration and deployment | Is the safety and security argument complete? | **[Integrated GSN argument](https://github.com/milinpatel07/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case)** across four standards |
| 5 · Operation and monitoring | Is it still safe on the road? | **Runtime uncertainty monitor**: ensemble disagreement mapped to Monitor, Alert, Degraded, Fallback and minimal-risk manoeuvre |
| 6 · Modification and re-assurance | Does the argument survive an over-the-air update? | Re-assurance after model updates, an open gap between the standards |

</details>

---

## Publications

**2026**

- **Integrating Cybersecurity Into the AI Safety Assurance Argument: A GSN Pattern for AI-Based Perception Components in Highly Automated Driving.**<br>
  M. Patel, R. Jung. *SAFECOMP 2026 Workshops (WAISE)*, LNCS, Springer, pp. 763–779.<br>
  [`DOI`](https://doi.org/10.1007/978-3-032-35506-5_55) · [`Website`](https://milinpatel07.github.io/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case/) · [`Code`](https://github.com/milinpatel07/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case) · [`Archive`](https://doi.org/10.5281/zenodo.22091825)
- **Operational Safety and Cybersecurity Assurance of AI-Based Perception in Highly Automated Driving.**<br>
  M. Patel, R. Jung. *SAFECOMP 2026*, to appear.

**Submitted**

- **Uncertainty Evaluation to Support Safety of the Intended Functionality Analysis for Determining the Applicability of Performance Targets Across Triggering Conditions in ML-Based LiDAR Object Detection.**<br>
  M. Patel, R. Jung. Submitted, 2026.<br>
  [`Story`](https://milinpatel07.github.io/lidar-performance-target-applicability/story.html) · [`Code`](https://github.com/milinpatel07/lidar-performance-target-applicability) · [`Archive`](https://doi.org/10.5281/zenodo.23495356)

<details>
<summary><b>Earlier work, 2024 to 2025</b></summary>
<br>

- **A Systematic Literature Review on Safety of the Intended Functionality for Automated Driving Systems.**<br>
  M. Patel, R. Jung, M. Khatun. *SAE Technical Paper* 2025-01-5030, 2025. [`DOI`](https://doi.org/10.4271/2025-01-5030)
- **Uncertainty Representation in a SOTIF-Related Use Case with Dempster–Shafer Theory for LiDAR Sensor-Based Object Detection.**<br>
  M. Patel, R. Jung. *arXiv* 2503.02087, 2025. [`arXiv`](https://arxiv.org/abs/2503.02087)
- **Simulation-Based Performance Evaluation of 3D Object Detection Methods with Deep Learning for a LiDAR Point Cloud Dataset in a SOTIF-related Use Case.**<br>
  M. Patel, R. Jung. *Proceedings of the 10th International Conference on Vehicle Technology and Intelligent Transport Systems (VEHITS)*, pp. 415–426, 2024.

</details>

---

## Projects

<table>
<tr>
<td width="50%" valign="top">
<h3>🧩 Assurance gaps</h3>
<p><b>One GSN argument across four standards</b></p>
<p>Combines ISO 26262, ISO 21448, ISO/SAE 21434 and ISO/PAS 8800 claims for one AI perception component and shows where the standards leave the engineer to decide.</p>
<p><a href="https://milinpatel07.github.io/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case/argument.html"><b>Explore the argument →</b></a><br><sub><a href="https://github.com/milinpatel07/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case">Repository</a> · GSN · safety case · Python</sub></p>
</td>
<td width="50%" valign="top">
<h3>🎯 Performance-target applicability</h3>
<p><b>Does a threshold still hold in the rain?</b></p>
<p>A statistical test for ISO 21448: keep an uncertainty threshold chosen in one condition and check, with recorded data, whether it still meets its target under a triggering condition.</p>
<p><a href="https://milinpatel07.github.io/lidar-performance-target-applicability/story.html"><b>The idea in two minutes →</b></a><br><sub><a href="https://github.com/milinpatel07/lidar-performance-target-applicability">Repository</a> · SOTIF · LiDAR · statistics</sub></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>🏫 Sicher durch Zufall?</h3>
<p><b>A school workshop for grade 11 (in German)</b></p>
<p>Pupils count the people in a street scene, then watch an AI do it, lose them in fog and get fooled by an attack. No code needed: sliders and buttons in Colab.</p>
<p><a href="https://github.com/milinpatel07/campustage-2026-sicher-durch-zufall"><b>Open the workshop →</b></a><br><sub>Campustage 2026 · Jupyter · outreach</sub></p>
</td>
<td width="50%" valign="top">
<h3>📄 Document chat</h3>
<p><b>Answers only from your own documents</b></p>
<p>Ask questions about your PDFs and get answers with page references and the exact passages they came from. If the documents don't contain the answer, it says so.</p>
<p><a href="https://github.com/milinpatel07/doc-chat"><b>See the tool →</b></a><br><sub>RAG · Streamlit · ChromaDB · for any researcher</sub></p>
</td>
</tr>
</table>

<details>
<summary><b>In preparation, not public yet</b></summary>
<br>

| Project | What it is |
|---|---|
| 🎓 **Autonomous Driving: AI Safety and Security** | An open course in eight modules, from perception to the safety case, built around one pedestrian emergency-braking example, with notebooks that run on a CPU |
| 🔬 **AI Perception Safety Workshop** | Hands-on: a real detector loses pedestrians in fog and under attack, and you work out which standard applies to each cause |
| 📡 **Runtime Uncertainty Monitoring** | Deep ensembles of a LiDAR detector; their disagreement becomes a runtime signal with a graded response |
| 🌫️ **SOTIF Perception Benchmark** | 3D detection under 14 types of sensor degradation, with each failure placed in one of the four ISO 21448 areas |

</details>

---

## Teaching and outreach

The same story at three depths: a detector that misses a pedestrian, why it happened, and what the standards ask you to do about it.

```mermaid
flowchart LR
    A["🏫 <b>Grade 11 pupils</b><br/>Campustage workshop<br/><i>How does a car see?</i>"] --> B["🔬 <b>Students</b><br/>Perception safety workshop<br/><i>Fog, attacks and three standards</i>"]
    B --> C["🎓 <b>Engineers and researchers</b><br/>Eight-module course<br/><i>From HARA to the safety case</i>"]
    classDef s fill:#101a31,stroke:#5ad1f0,color:#eef3fa,stroke-width:1.5px
    class A,B,C s
```

---

## Toolbox

**Standards and methods**

![ISO 26262](https://img.shields.io/badge/ISO_26262-functional_safety-101a31?style=flat-square&labelColor=5ad1f0)
![ISO 21448](https://img.shields.io/badge/ISO_21448-SOTIF-101a31?style=flat-square&labelColor=5ad1f0)
![ISO/SAE 21434](https://img.shields.io/badge/ISO%2FSAE_21434-cybersecurity-101a31?style=flat-square&labelColor=5ad1f0)
![ISO/PAS 8800](https://img.shields.io/badge/ISO%2FPAS_8800-AI_safety-101a31?style=flat-square&labelColor=5ad1f0)
![UNECE R155/R156](https://img.shields.io/badge/UNECE-R155_%2F_R156-101a31?style=flat-square&labelColor=8aa0c0)
![EU AI Act](https://img.shields.io/badge/EU-AI_Act-101a31?style=flat-square&labelColor=8aa0c0)
![GSN](https://img.shields.io/badge/GSN-safety_cases-101a31?style=flat-square&labelColor=3ddc97)
![HARA · TARA · STPA](https://img.shields.io/badge/HARA_·_TARA_·_STPA-analysis-101a31?style=flat-square&labelColor=3ddc97)

**Code and data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenPCDet](https://img.shields.io/badge/OpenPCDet-3D_detection-555?style=flat-square)
![CARLA](https://img.shields.io/badge/CARLA-simulation-555?style=flat-square)
![KITTI · nuScenes](https://img.shields.io/badge/KITTI_·_nuScenes-datasets-555?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

---

## Contact

I'm glad to talk about AI safety assurance, SOTIF, safety cases, runtime monitoring, or teaching these topics. Collaborations, industry questions and student projects are all welcome.

- 🏛️ Institute for Driver Assistance and Connected Mobility (IFM), Hochschule Kempten
- 💬 Open an issue on any of my public repositories

<div align="center">
<sub>The animations on this page are plain SVG and stop if your system asks for reduced motion.</sub>
</div>
