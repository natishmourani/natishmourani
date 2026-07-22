<!--
  natishmourani/natishmourani — profile README
  The visual is portfolio.svg. Everything below it exists because a GitHub
  README renders SVG through an <img> tag, which means links *inside* the SVG
  are not clickable and its text is not selectable or searchable. This file
  restores both.
-->

<!-- One image, no theme variants: the SVG carries its own dark ground,
     so it reads identically in GitHub light and dark mode. -->
<p align="center">
  <img src="./portfolio.svg" width="100%"
       alt="Natish Mourani — AI/ML Engineer, Karachi. A terminal types his name in C++, Python, Java, C#, JavaScript and SQL, followed by sections for whoami, projects, stack and contact.">
</p>

<p align="center">
  <a href="https://github.com/natishmourani/HireSense-Resume-Matcher"><b>HireSense</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/natishmourani/DiaPredict-AI"><b>DiaPredict AI</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/natishmourani/Smart-Proctor-System"><b>Smart Proctor</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/natishmourani/CPU-Scheduling-Simulator"><b>CPU Scheduling</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/natishmourani/Convex-Hull"><b>Convex Hull</b></a>
</p>

<p align="center">
  <a href="mailto:natishmourani@gmail.com">
    <img alt="Email" src="https://img.shields.io/badge/natishmourani%40gmail.com-12161C?style=flat-square&logo=gmail&logoColor=F0A202&labelColor=12161C"></a>
  <a href="https://www.linkedin.com/in/natish-mourani-566949375/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-12161C?style=flat-square&logo=linkedin&logoColor=9ECBFF&labelColor=12161C"></a>
  <a href="https://github.com/natishmourani?tab=repositories">
    <img alt="Repositories" src="https://img.shields.io/badge/All%20repositories-12161C?style=flat-square&logo=github&logoColor=E8ECF1&labelColor=12161C"></a>
</p>

---

<!--
  Plain-text layer. Search engines, screen readers and GitHub's own search
  cannot read text baked into an SVG. Collapsed so it doesn't compete with
  the visual, but fully indexable.
-->

<details>
<summary><b>0x001 &nbsp; whoami</b> — plain text</summary>

<br>

Computer Science undergraduate at Mohammad Ali Jinnah University, Karachi.
Building across machine learning and the full stack — Python · Flask · Scikit-learn · SQL Server · C++.
Drawn to problems where a model has to survive contact with a real product.

| | |
|---|---|
| **Focus** | Machine learning · AI applications · full-stack systems · algorithm design |
| **Status** | Open to internships · freelance · collaboration |
| **Education** | BS Computer Science, MAJU — 2023 / 2027 · CGPA 3.5 / 4.0 |
| **Honours** | Dean's Honour Roll — Spring 2024 |
| **Languages** | English · Urdu · Sindhi · Dhatki |

</details>

<details>
<summary><b>0x002 &nbsp; projects</b> — plain text</summary>

<br>

**[HireSense](https://github.com/natishmourani/HireSense-Resume-Matcher)** — AI resume screening and job matching
`Python · Flask · Sentence Transformers · Scikit-learn · Groq API`
Screens resumes against job descriptions using SentenceTransformer embeddings and cosine similarity, with explainable skill-based feedback and model comparison.

**[DiaPredict AI](https://github.com/natishmourani/DiaPredict-AI)** — diabetes risk prediction
`Python · Flask · Scikit-learn · Pandas · Matplotlib · Seaborn`
Trains Logistic Regression, KNN, Decision Tree and Random Forest on the Pima Indians dataset, auto-deploys the best by accuracy, and serves risk predictions from a dashboard.

**[Smart Proctor System](https://github.com/natishmourani/Smart-Proctor-System)** — computer-vision exam proctoring
`Python · OpenCV · YOLOv8 · MediaPipe`
Tracks face presence, head pose and objects in real time, flagging suspicious behaviour, capturing evidence and logging violations.

**[CPU Scheduling Simulator](https://github.com/natishmourani/CPU-Scheduling-Simulator)** — OS scheduling visualiser
`Python · Tkinter · Matplotlib`
Desktop simulator for FCFS, SJF, Priority and Round Robin, rendering a colour-coded Gantt chart with per-process waiting and turnaround metrics.

**[Convex Hull](https://github.com/natishmourani/Convex-Hull)** — computational geometry
`C++ · Python · Matplotlib`
QuickHull against Brute Force over 2D point sets — divide and conquer at O(n log n) average versus O(n³). Design & Analysis of Algorithms coursework.

</details>

<details>
<summary><b>0x003 &nbsp; stack</b> — plain text</summary>

<br>

Skills are claims, repos are evidence. Node size in the graph is the number of
repositories that prove a skill; amber means every repository uses it.

| Skill | Proven by | Count |
|---|---|---|
| Python | all six | 6/6 |
| Git · GitHub | all six | 6/6 |
| Flask | HireSense, DiaPredict, Private Work | 3/6 |
| Matplotlib · Seaborn | DiaPredict, CPU Scheduler, Convex Hull | 3/6 |
| Scikit-learn | HireSense, DiaPredict | 2/6 |
| Pandas · NumPy | HireSense, DiaPredict | 2/6 |
| Sentence Transformers | HireSense | 1/6 |
| OpenCV · YOLOv8 | Smart Proctor | 1/6 |
| MediaPipe | Smart Proctor | 1/6 |
| Tkinter | CPU Scheduler | 1/6 |
| C++ | Convex Hull | 1/6 |
| C# · ASP.NET Core | Private Work | 1/6 |
| SQL Server · MySQL | Private Work | 1/6 |

*Private Work = EduManage · SkillSwap Hub — university builds, not public.*

</details>


<details>
<summary><b>0x004 &nbsp; activity</b> — plain text</summary>

<br>

The only live part of this page. A GitHub Actions cron rewrites the `0x004`
section of `portfolio.svg` every six hours from two unauthenticated endpoints:

| Panel | Shows |
|---|---|
| Language by repository | Primary language across all public repos |
| Contribution velocity | Weekly totals over the last 26 weeks, peak marked |
| Headline figures | Repositories · contributions · active days · longest streak |
| Contribution calendar | 12-month heatmap, busiest day in amber |

Language mix is counted **by repository, not by bytes**. GitHub's byte counts
are dominated by Flask templates and notebook JSON, which would report this
account as roughly a third HTML — accurate but misleading about what actually
gets built.

It commits as `github-actions[bot]` rather than as me, so the refresh never
lands on the contribution graph it is reporting on. The rendered section carries
no timestamp, so a commit happens only when the underlying numbers actually
change — the regenerated-at stamp lives in the standalone
`0x004-activity.svg` title instead.

Source: `scripts/activity.py` · schedule: `.github/workflows/activity.yml`

</details>
<details>
<summary><b>0x005 &nbsp; contact</b> — plain text</summary>

<br>

- **Email** — [natishmourani@gmail.com](mailto:natishmourani@gmail.com)
- **LinkedIn** — [natish-mourani](https://www.linkedin.com/in/natish-mourani-566949375/)
- **GitHub** — [@natishmourani](https://github.com/natishmourani)
- **Location** — Karachi, Pakistan (PKT, UTC+5)

</details>

<!--
  ─────────────────────────────────────────────────────────────────────────
  SETUP

  1. Repository name must be exactly:  natishmourani
     (same as the username — that is what makes it a profile README)
  2. Put portfolio.svg and this README.md in the repository root.
  3. Commit to the default branch. GitHub renders it on your profile page.

  LIVE SECTION (0x004)

  - scripts/activity.py rewrites the activity section from GitHub's public
    contributions calendar. No token, no secrets, no API quota.
  - .github/workflows/activity.yml runs it every 6 hours and on demand.
  - Run it locally any time:   python3 scripts/activity.py
    Render without touching the portfolio:   python3 scripts/activity.py --dry-run
  - The splice is idempotent and validates XML before writing, so a failed
    fetch or a bad parse leaves portfolio.svg exactly as it was.

  MAINTENANCE

  - Adding a project: edit the SVG, then add it to BOTH link rows above and
    to the 0x002 plain-text block, or the two will drift out of sync.
  - The SVG is ~106 KB raw, ~12.5 KB gzipped, no external fonts or scripts.
  - Animations are CSS keyframes plus SMIL; both run inside an <img> tag.
    prefers-reduced-motion is respected.
  ─────────────────────────────────────────────────────────────────────────
-->
