<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a2540,55:0a66c2,100:00b4d8&height=190&section=header&text=Krishna%20Raju&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Software%20Developer%20%C2%B7%20Indo%20Tech%20Transformers%20Limited&descSize=17&descAlignY=58&animation=fadeIn" width="100%" alt="Krishna Raju, Software Developer at Indo Tech Transformers Limited"/>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=19&duration=3000&pause=1200&color=0A66C2&center=true&vCenter=true&width=640&height=40&lines=Building+software+for+transformer+manufacturing;Turning+manual+processes+into+reliable+apps;Dispatch+%C2%B7+Testing+%C2%B7+Inspection+%C2%B7+Automation" alt="Building software for transformer manufacturing"/>

<a href="mailto:Krishna.Raju@indo-tech.com"><img src="https://img.shields.io/badge/Email-0A66C2?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://www.indo-tech.com/"><img src="https://img.shields.io/badge/Indo_Tech_Transformers-0a2540?style=for-the-badge&logo=lightning&logoColor=00b4d8" alt="Indo Tech Transformers"/></a>
<a href="https://krishna-ittl.github.io/Candidate-Screener/"><img src="https://img.shields.io/badge/Live_Demo-Job_Lens-00b4d8?style=for-the-badge&logo=githubpages&logoColor=white" alt="Job Lens live demo"/></a>
<img src="https://img.shields.io/badge/Kanchipuram-India-1f2937?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Kanchipuram, India"/>

</div>

---

## About

I build the internal software that runs day-to-day operations at **Indo Tech Transformers**: dispatch, testing, inspection tracking, hardware automation and HR tools. My focus is replacing spreadsheet-driven, manual work with dependable applications that people on the shop floor use every shift.

```yaml
role:      Software Developer
company:   Indo Tech Transformers Limited
focus:     [manufacturing workflows, process automation, internal tools]
approach:  secure by default, tested, built with the people who use it
```

## Impact

<table align="center">
<tr>
<td align="center" width="25%"><h2>9</h2><sub><b>APPS IN PRODUCTION</b><br/>across manufacturing operations</sub></td>
<td align="center" width="25%"><h2>2 h → 5 min</h2><sub><b>TEST PLANNING</b><br/>per transformer</sub></td>
<td align="center" width="25%"><h2>30 min → 30 s</h2><sub><b>HARDWARE BOM</b><br/>from PDF to Excel</sub></td>
<td align="center" width="25%"><h2>128</h2><sub><b>AUTOMATED TESTS</b><br/>guarding dispatch</sub></td>
</tr>
</table>

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🚚 Dispatch Management System
Work order → packing → loading → vehicle gate pass, end to end. Five user roles, a dispatch calendar and automatic email escalations.

![](https://img.shields.io/badge/Production-16a34a?style=flat-square) ![](https://img.shields.io/badge/React-0a2540?style=flat-square&logo=react) ![](https://img.shields.io/badge/Supabase-0a2540?style=flat-square&logo=supabase) ![](https://img.shields.io/badge/PostgreSQL-0a2540?style=flat-square&logo=postgresql)

</td>
<td width="50%" valign="top">

### 🔍 [Job Lens](https://github.com/krishna-ITTL/Candidate-Screener)
Screens and ranks resumes against one consistent rubric, with ATS checks. Works fully offline or with an AI provider.

[![](https://img.shields.io/badge/Live_Demo-00b4d8?style=flat-square)](https://krishna-ittl.github.io/Candidate-Screener/) ![](https://img.shields.io/badge/TypeScript-0a2540?style=flat-square&logo=typescript) ![](https://img.shields.io/badge/React-0a2540?style=flat-square&logo=react)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧰 [RTCC & M.Box Tracker](https://github.com/krishna-ITTL/RTCC-and-M.BOX-PROJECT)
Inspection, testing and clearance tracking for RTCC panels and marshalling boxes, with automatic 48-hour follow-up emails.

![](https://img.shields.io/badge/In_Use-16a34a?style=flat-square) ![](https://img.shields.io/badge/React-0a2540?style=flat-square&logo=react) ![](https://img.shields.io/badge/Express-0a2540?style=flat-square&logo=express)

</td>
<td width="50%" valign="top">

### 🔩 [Fasteners Automation](https://github.com/krishna-ITTL/Fasteners-Project)
Drop in a hardware PDF and get a weighted fastener BOM as Excel and PDF. Hours of manual entry, removed.

![](https://img.shields.io/badge/In_Use-16a34a?style=flat-square) ![](https://img.shields.io/badge/Python-0a2540?style=flat-square&logo=python)

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br/>

| Project | Description | Stack |
|:--|:--|:--|
| [**Testing Data Acquisition**](https://github.com/krishna-ITTL/Testing-s-Data-Acquisition-) | Transformer test data capture with Excel export and QR tagging | React, Express, ExcelJS |
| [**Project Management System**](https://github.com/krishna-ITTL/Project-Management-System) | Projects, Gantt charts, milestones, tasks, daily reports and budgets | TypeScript, React, Express, Supabase |
| [**dMAT Practice**](https://github.com/krishna-ITTL/dmat-practice) · [Live](https://krishna-ittl.github.io/dmat-practice/) | Offline exam simulator with timed mock tests and weakness analysis | HTML, CSS, JavaScript |

</details>

<details>
<summary><b>How the dispatch workflow fits together</b></summary>
<br/>

```mermaid
flowchart LR
    A[Work Order] --> B[Packing]
    B --> C[Loading]
    C --> D[Vehicle Gate Pass]
    D --> E((Dispatched))
    B -. delay .-> F[Auto email escalation]
    C -. delay .-> F
```

</details>

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,ts,js,vite,tailwind,html,css&perline=7" alt="Frontend: React, TypeScript, JavaScript, Vite, Tailwind, HTML, CSS"/><br/>
  <img src="https://skillicons.dev/icons?i=nodejs,express,python,postgres,supabase,vitest,git,github&perline=8" alt="Backend and tooling: Node.js, Express, Python, PostgreSQL, Supabase, Vitest, Git, GitHub"/>
</p>

## GitHub Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=krishna-ITTL&theme=transparent&hide_border=true&ring=0A66C2&fire=00B4D8&currStreakLabel=0A66C2" alt="GitHub contribution streak"/>
</p>

<div align="center">

**Have a manual process slowing your team down? Let's talk.**

<a href="mailto:Krishna.Raju@indo-tech.com"><img src="https://img.shields.io/badge/Get_in_touch-0A66C2?style=for-the-badge&logo=maildotru&logoColor=white" alt="Get in touch"/></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00b4d8,45:0a66c2,100:0a2540&height=110&section=footer" width="100%" alt=""/>
