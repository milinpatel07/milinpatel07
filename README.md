<div align="center">

<img src="assets/hero.svg" width="100%" alt="Milin Patel, PhD researcher in automated driving, working on the safety and security of AI-based perception. An animated LiDAR scene shows a safety monitor reacting as a pedestrian detection becomes uncertain.">

<br>

<!-- Profile buttons: send me the links and I'll fill them in.
<a href="https://scholar.google.com/citations?user=YOUR-ID"><img src="https://img.shields.io/badge/Google_Scholar-publications-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white&labelColor=0a1020" alt="Google Scholar"></a>
<a href="https://orcid.org/0000-0000-0000-0000"><img src="https://img.shields.io/badge/ORCID-profile-a6ce39?style=for-the-badge&logo=orcid&logoColor=white&labelColor=0a1020" alt="ORCID"></a>
<a href="https://www.researchgate.net/profile/YOUR-NAME"><img src="https://img.shields.io/badge/ResearchGate-profile-00ccbb?style=for-the-badge&logo=researchgate&logoColor=white&labelColor=0a1020" alt="ResearchGate"></a>
<a href="https://www.linkedin.com/in/YOUR-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0a1020" alt="LinkedIn"></a>
-->

<sub><b><a href="#research">Research</a></b> · <b><a href="#publications">Publications</a></b> · <b><a href="#projects">Projects</a></b> · <b><a href="#teaching">Teaching</a></b> · <b><a href="#toolbox">Toolbox</a></b> · <b><a href="#contact">Contact</a></b></sub>

</div>

---

### Hi, I'm Milin 👋

I'm a PhD researcher working on **automated driving**. Cars increasingly rely on AI to see the road, and AI learns from data instead of following a written specification. That makes it powerful, and it also makes it hard to prove safe.

> **My work is about one question: how do we earn justified trust in AI that drives?**

I bring together **functional safety, safety of the intended functionality (SOTIF), cybersecurity and AI safety** so they work as one, and I build tools that turn those ideas into evidence engineers can use.

---

## Research

<div align="center">
<img src="assets/lifecycle.svg" width="100%" alt="The safety lifecycle of an AI component: concept and requirements, data and design, verification and validation, release, operation, and updates.">
</div>

<br>

<div align="center">
<img src="assets/focus.svg" width="100%" alt="Focus areas: perception safety, safety meets security, uncertainty, and teaching.">
</div>

<details>
<summary><b>What I look at in each phase</b> (click to expand)</summary>
<br>

| Phase | The question | My angle |
|---|---|---|
| Concept and requirements | What can go wrong? | Hazards, threats and the limits of what a sensor or model can do |
| Data and design | Is the data fit for purpose? | Data as a safety artefact, not just training material |
| Verification and validation | Does it meet its targets? | Testing perception under bad weather, noise and edge cases |
| Release | Is the case convincing? | Structured assurance arguments that cover safety and security together |
| Operation | Is it still safe out there? | Runtime monitoring and uncertainty as early warning signals |
| Updates | Does it hold after a change? | Keeping the evidence valid when models are retrained or updated |

</details>

---

## Publications

I publish at international conferences and workshops on **dependable systems** and **vehicle technology**. Recent topics:

`assurance cases for AI` · `safety and security co-engineering` · `SOTIF` · `uncertainty in LiDAR perception` · `runtime monitoring` · `standards analysis`
---

## Projects

<table>
<tr>
<td width="50%" valign="top">
<h3>🧩 Assurance explorer</h3>
<p><b>One argument across several standards</b></p>
<p>An interactive website that walks through a structured safety and security argument for an AI component, step by step.</p>
<p><a href="https://milinpatel07.github.io/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case/"><b>Explore →</b></a><br><sub>assurance cases · GSN · Python</sub></p>
</td>
<td width="50%" valign="top">
<h3>🎯 Performance under conditions</h3>
<p><b>Does it still work in the rain?</b></p>
<p>A statistical way to check whether a perception system still meets its targets when conditions change, explained without formulas.</p>
<p><a href="https://milinpatel07.github.io/lidar-performance-target-applicability/story.html"><b>Read the story →</b></a><br><sub>SOTIF · LiDAR · statistics</sub></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>🏫 How does a car see?</h3>
<p><b>A school workshop (in German)</b></p>
<p>Pupils watch an AI detect people in a street scene, then see it fail in fog and get fooled by an attack. No code needed.</p>
<p><a href="https://github.com/milinpatel07/campustage-2026-sicher-durch-zufall"><b>Open the workshop →</b></a><br><sub>outreach · Jupyter · Colab</sub></p>
</td>
<td width="50%" valign="top">
<h3>📄 Document chat</h3>
<p><b>Ask your own documents</b></p>
<p>Answers questions only from the files you upload, with page references and the exact passages, so every answer can be checked.</p>
<p><a href="https://github.com/milinpatel07/doc-chat"><b>See the tool →</b></a><br><sub>RAG · Streamlit · for any researcher</sub></p>
</td>
</tr>
</table>

---

## Teaching

I like making safety engineering tangible: you run a real detector, watch it fail, and then work out what a responsible engineer would do about it.

```mermaid
flowchart LR
    A["🏫 <b>School pupils</b><br/><i>How does a car see?</i>"] --> B["🔬 <b>Students</b><br/><i>Why does it fail?</i>"]
    B --> C["🎓 <b>Engineers</b><br/><i>How do we prove it is safe?</i>"]
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
![Assurance cases](https://img.shields.io/badge/GSN-assurance_cases-101a31?style=flat-square&labelColor=3ddc97)
![Hazard and threat analysis](https://img.shields.io/badge/HARA_·_TARA_·_STPA-analysis-101a31?style=flat-square&labelColor=3ddc97)

**Code and data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![CARLA](https://img.shields.io/badge/CARLA-simulation-555?style=flat-square)
![LiDAR](https://img.shields.io/badge/LiDAR-3D_perception-555?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

---

## Contact

Happy to talk about AI safety, SOTIF, assurance cases or teaching these topics. Research collaborations, industry questions and student projects are all welcome.

<div align="center">
<sub>The animations on this page are plain SVG and pause if your system asks for reduced motion.</sub>
</div>
