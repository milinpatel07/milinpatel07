<div align="center">

<img src="assets/hero.svg" width="100%" alt="Milin Patel. PhD research on the safety and security of AI-based perception in automated driving. An animated LiDAR scene shows a runtime monitor reacting as a pedestrian detection becomes uncertain.">

<br>

<a href="https://scholar.google.com/citations?user=2pdr8QwAAAAJ"><img src="https://img.shields.io/badge/Google_Scholar-publications-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white&labelColor=0a1020" alt="Google Scholar"></a>
<a href="https://orcid.org/0000-0002-8357-6018"><img src="https://img.shields.io/badge/ORCID-0000--0002--8357--6018-a6ce39?style=for-the-badge&logo=orcid&logoColor=white&labelColor=0a1020" alt="ORCID 0000-0002-8357-6018"></a>
<a href="https://www.researchgate.net/profile/Milin-Patel"><img src="https://img.shields.io/badge/ResearchGate-profile-00ccbb?style=for-the-badge&logo=researchgate&logoColor=white&labelColor=0a1020" alt="ResearchGate"></a>
<a href="https://www.linkedin.com/in/milinpatel1996/"><img src="https://img.shields.io/badge/LinkedIn-profile-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0a1020" alt="LinkedIn"></a>

<br>

<sub><b><a href="#research">Research</a></b> · <b><a href="#publications">Publications</a></b> · <b><a href="#projects">Projects</a></b> · <b><a href="#education">Education</a></b> · <b><a href="#toolbox">Toolbox</a></b> · <b><a href="#contact">Contact</a></b></sub>

</div>

---

### Safety and security of AI-based perception

Automated driving systems depend on AI-based perception to detect pedestrians, vehicles and the road layout. These AI components learn their behaviour from data instead of following a written specification, so the established methods of safety engineering cover them only in part.

The research addresses three guiding questions, one for each stage of the lifecycle:

| | Guiding question |
|:--:|---|
| **Before release** | Is the performance of the AI-based perception sufficient, including under adverse conditions? |
| **At release** | Do the safety and cybersecurity claims combine into one consistent assurance case? |
| **After release** | Does the evidence remain valid in operation and after each update of the AI component? |

The work brings together **functional safety** (ISO 26262), **safety of the intended functionality, SOTIF** (ISO 21448), **cybersecurity** (ISO/SAE 21434) and **AI safety** (ISO/PAS 8800), and turns their requirements into evidence that engineers can produce and assessors can check.

---

## Research

<div align="center">
<img src="assets/lifecycle.svg" width="100%" alt="The safety lifecycle of an AI component: concept and requirements, data and design, verification and validation, release, operation, and updates.">
</div>

<br>

<div align="center">
<img src="assets/focus.svg" width="100%" alt="Research areas: perception safety, safety and security, uncertainty, education.">
</div>


---

## Publications

Peer-reviewed publications at international conferences and workshops on dependable systems and vehicle technology.

**Topics:** `assurance cases for AI` · `safety and cybersecurity co-engineering` · `SOTIF` · `uncertainty in LiDAR perception` · `runtime monitoring` · `standards analysis`

**Full list:** [Google Scholar](https://scholar.google.com/citations?user=2pdr8QwAAAAJ) · [ORCID](https://orcid.org/0000-0002-8357-6018) · [ResearchGate](https://www.researchgate.net/profile/Milin-Patel)

---

## Projects

<table>
<tr>
<td width="50%" valign="top">
<h3>🧩 Assurance case explorer</h3>
<p><b>Safety and cybersecurity in one assurance case</b></p>
<p>An interactive website that presents a structured assurance case for an AI component, goal by goal, across several standards.</p>
<p><a href="https://milinpatel07.github.io/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case/"><b>Explore the assurance case →</b></a><br><sub>assurance cases · GSN · Python</sub></p>
</td>
<td width="50%" valign="top">
<h3>🎯 Performance under triggering conditions</h3>
<p><b>Is the performance target still met in rain?</b></p>
<p>A statistical test that checks whether AI-based perception still meets its performance target when conditions change, explained without formulas.</p>
<p><a href="https://milinpatel07.github.io/lidar-performance-target-applicability/story.html"><b>Read the explanation →</b></a><br><sub>SOTIF · LiDAR · statistics</sub></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>🏫 How does a vehicle perceive?</h3>
<p><b>School workshop (in German)</b></p>
<p>Pupils observe an object detector in a street scene, then see it miss pedestrians in fog and fail under a manipulated image. No programming required.</p>
<p><a href="https://github.com/milinpatel07/campustage-2026-sicher-durch-zufall"><b>Open the workshop →</b></a><br><sub>outreach · Jupyter · Colab</sub></p>
</td>
<td width="50%" valign="top">
<h3>📄 Document chat</h3>
<p><b>Answers from uploaded documents only</b></p>
<p>A research tool that answers questions from uploaded documents, with page references and the exact source passages, so every answer can be checked.</p>
<p><a href="https://github.com/milinpatel07/doc-chat"><b>View the tool →</b></a><br><sub>retrieval-augmented generation · Streamlit</sub></p>
</td>
</tr>
</table>

---

## Education

Teaching material in which learners run a real object detector, observe where it fails, and work out the engineering response.

```mermaid
flowchart LR
    A["🏫 <b>School</b><br/><i>How does a vehicle perceive its surroundings?</i>"] --> B["🔬 <b>University</b><br/><i>Why does AI-based perception fail?</i>"]
    B --> C["🎓 <b>Engineering practice</b><br/><i>How is sufficient safety demonstrated?</i>"]
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
![GSN](https://img.shields.io/badge/GSN-assurance_cases-101a31?style=flat-square&labelColor=3ddc97)
![HARA, TARA, STPA](https://img.shields.io/badge/HARA_·_TARA_·_STPA-hazard_and_threat_analysis-101a31?style=flat-square&labelColor=3ddc97)

**Software and data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![CARLA](https://img.shields.io/badge/CARLA-simulation-555?style=flat-square)
![LiDAR](https://img.shields.io/badge/LiDAR-3D_object_detection-555?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

---

## Contact

Open to research collaboration, industry exchange and student projects on AI safety, SOTIF and assurance cases.

[LinkedIn](https://www.linkedin.com/in/milinpatel1996/) · [Google Scholar](https://scholar.google.com/citations?user=2pdr8QwAAAAJ) · [ORCID](https://orcid.org/0000-0002-8357-6018) · [ResearchGate](https://www.researchgate.net/profile/Milin-Patel)

<div align="center">
<sub>Animations are plain SVG and pause when reduced motion is requested.</sub>
</div>
