from pathlib import Path
from textwrap import dedent

code = r'''from pathlib import Path

# ============================================================
# GITHUB PROFILE CONFIG
# Change these values once and the whole profile updates.
# ============================================================

USERNAME = "Sarvagyabirla"
NAME = "Sarvagya Birla"
LINKEDIN = "https://www.linkedin.com/in/sarvagyabirla"
AERIS_REPO = f"https://github.com/{USERNAME}/Aeris-AI-Assistant"
GESTURE_REPO = f"https://github.com/{USERNAME}/SmartGestureOS"

ROOT = Path(__file__).resolve().parent


def build_readme() -> str:
    """Return the complete GitHub profile README."""

    return f"""<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,30:0F172A,55:312E81,78:7C3AED,100:06B6D4&height=235&section=header&text=SARVAGYA%20BIRLA&fontSize=52&fontColor=F8FAFC&fontAlignY=35&desc=AI%20%2F%20ML%20%E2%80%A2%20PYTHON%20%E2%80%A2%20COMPUTER%20VISION%20%E2%80%A2%20AI%20AGENTS&descSize=16&descAlignY=57&animation=twinkling" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2200&pause=700&color=22D3EE&center=true&vCenter=true&repeat=true&width=900&lines=Building+AI+systems+that+perceive%2C+reason+and+act.;Python+%C3%97+Computer+Vision+%C3%97+AI+Agents;Turning+ideas+into+working+intelligent+systems.;Build+%E2%86%92+Test+%E2%86%92+Debug+%E2%86%92+Improve+%E2%86%92+Ship" alt="Animated introduction" />

### `AI / ML Engineer in Progress`

**B.Tech CSE (AI & ML) student building practical AI, computer vision and automation systems.**

[![GitHub](https://img.shields.io/badge/GitHub-{USERNAME}-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/{USERNAME})
[![LinkedIn](https://img.shields.io/badge/LinkedIn-{NAME.replace(" ", "%20")}-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)]({LINKEDIN})
![Open to Work](https://img.shields.io/badge/Open%20To-AI%2FML%20Internships-7C3AED?style=for-the-badge)
![Views](https://komarev.com/ghpvc/?username={USERNAME}&label=PROFILE+VIEWS&color=0891B2&style=for-the-badge)

</div>

---

## 👨‍💻 About Me

```yaml
name: {NAME}
degree: B.Tech Computer Science & Engineering
specialization: Artificial Intelligence & Machine Learning
year: 3rd Year
primary_language: Python

focus:
  - Artificial Intelligence
  - Machine Learning
  - Computer Vision
  - AI Agents
  - Intelligent Automation

currently_learning:
  - Data Structures & Algorithms
  - Machine Learning
  - Deep Learning
  - Agentic AI

target: AI / ML Internship → AI / ML Engineer
```

> I am most interested in **applied AI engineering**, where perception, reasoning and automation work together to solve real-world problems.

<div align="center">

### `DATA / VOICE / VISION → PERCEPTION → REASONING → ACTION → IMPACT`

**Build AI that can understand → decide → act.**

</div>

---

## ⚡ Engineering Focus

<table>
<tr>
<td width="25%" align="center">

### 🐍 Python
Problem Solving<br>
DSA<br>
Clean Code<br>
Engineering

</td>
<td width="25%" align="center">

### 🧠 AI / ML
Machine Learning<br>
Deep Learning<br>
Generative AI<br>
Model Building

</td>
<td width="25%" align="center">

### 👁️ Vision
OpenCV<br>
MediaPipe<br>
Real-Time CV<br>
HCI

</td>
<td width="25%" align="center">

### 🤖 Agents
Tool Use<br>
Reasoning<br>
Automation<br>
Workflows

</td>
</tr>
</table>

<div align="center">

`PYTHON` → `DSA` → `ML` → `DEEP LEARNING` → `COMPUTER VISION` → `AI AGENTS`

</div>

---

# 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

## 🤖 AERIS

### `Local-First Cognitive Desktop AI Assistant`

Windows-focused AI assistant that converts natural-language requests into controlled computer actions through reasoning, permissions and tool execution.

**Core areas**

`Voice` `Wake Word` `AI Reasoning` `Desktop Automation`  
`Browser Actions` `File Operations` `Offline Commands`

**Stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_AI-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows11&logoColor=white)

[![View Project](https://img.shields.io/badge/VIEW%20PROJECT-AERIS-7C3AED?style=for-the-badge&logo=github&logoColor=white)]({AERIS_REPO})

</td>
<td width="50%" valign="top">

## ✋ SmartGestureOS

### `Real-Time Computer Vision Desktop Controller`

Touchless HCI system that maps webcam-based hand gestures to desktop controls in real time.

**Core areas**

`Cursor` `Click` `Drag & Drop` `Scrolling`  
`Volume` `Brightness` `Screenshot` `Drawing`

**Stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)

[![View Project](https://img.shields.io/badge/VIEW%20PROJECT-SmartGestureOS-0891B2?style=for-the-badge&logo=github&logoColor=white)]({GESTURE_REPO})

</td>
</tr>
</table>

---

## 🧩 Tech Stack

<div align="center">

### Languages & Tools

<img src="https://skillicons.dev/icons?i=python,cpp,git,github,vscode&theme=dark" alt="Languages and tools" />

<br><br>

### AI / Data / Vision

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-312E81?style=for-the-badge)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-0891B2?style=for-the-badge)
![Generative AI](https://img.shields.io/badge/Generative%20AI-7C3AED?style=for-the-badge)
![AI Agents](https://img.shields.io/badge/AI%20Agents-6D28D9?style=for-the-badge)

<br>

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

</div>

---

## 🏆 Selected Credentials

<details>
<summary><b>View certifications & training</b></summary>

<br>

- **Oracle Cloud Infrastructure 2025 Certified Generative AI Professional**
- **Python for Machine Learning Training — SINE, IIT Bombay** · `96%`
- **Google Cloud Platform for Machine Learning Essential Training**
- **Career Essentials in Generative AI — Microsoft & LinkedIn**
- Additional learning in `AI` · `Responsible AI` · `AI Ethics` · `Microsoft Copilot`

</details>

---

## ⚙️ Engineering Mindset

<div align="center">

```text
PROBLEM → RESEARCH → ARCHITECT → BUILD → TEST
                     ↓
ITERATE ← SHIP ← DOCUMENT ← OPTIMIZE ← DEBUG
```

> **Build things difficult enough to expose what still needs to be learned.**

</div>

---

## 🎯 Current Mission

<div align="center">

`Python` → `DSA` → `Machine Learning` → `Deep Learning` → `Computer Vision` → `Agentic AI` → **`AI / ML Internship`**

</div>

---

## 📊 GitHub Activity

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username={USERNAME}&show_icons=true&hide_border=true&bg_color=00000000&title_color=A78BFA&text_color=CBD5E1&icon_color=22D3EE&ring_color=7C3AED&include_all_commits=true" alt="GitHub stats" />
<img width="49%" src="https://streak-stats.demolab.com?user={USERNAME}&hide_border=true&background=00000000&ring=7C3AED&fire=22D3EE&currStreakLabel=A78BFA&sideLabels=94A3B8&dates=64748B&currStreakNum=F8FAFC&sideNums=F8FAFC" alt="GitHub streak" />

<br><br>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username={USERNAME}&bg_color=00000000&color=A78BFA&line=22D3EE&point=F8FAFC&area=true&hide_border=true" alt="Contribution graph" />

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/{USERNAME}/{USERNAME}/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/{USERNAME}/{USERNAME}/output/github-snake.svg">
  <img width="100%" alt="GitHub contribution snake" src="https://raw.githubusercontent.com/{USERNAME}/{USERNAME}/output/github-snake-dark.svg">
</picture>

</div>

---

## 🤝 Let's Build Something Intelligent

<div align="center">

### Open to **AI / ML Internship Opportunities**

I am looking for opportunities where I can **learn fast, contribute to real engineering work and build systems that matter.**

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)]({LINKEDIN})
[![GitHub](https://img.shields.io/badge/Follow%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/{USERNAME})

### `while (learning) {{ build(); test(); improve(); ship(); }}`

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0891B2,28:7C3AED,55:312E81,80:0F172A,100:020617&height=120&section=footer" />
"""


def build_snake_workflow() -> str:
    """Return the GitHub Actions workflow used to generate the contribution snake."""

    return """name: Generate Contribution Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches: [main]
    paths:
      - ".github/workflows/snake.yml"

permissions:
  contents: write

concurrency:
  group: contribution-snake
  cancel-in-progress: true

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: Generate contribution snake
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg?palette=github-light&color_snake=%237C3AED
            dist/github-snake-dark.svg?palette=github-dark&color_snake=%2322D3EE

      - name: Publish to output branch
        uses: peaceiris/actions-gh-pages@v4
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_branch: output
          publish_dir: ./dist
"""


def write_file(path: Path, content: str) -> None:
    path.parent.mkdir(parents=True, exist_ok=True)
    path.write_text(content.strip() + "\n", encoding="utf-8")
    print(f"✓ {path.relative_to(ROOT)}")


def main() -> None:
    print("Generating GitHub profile...\n")

    write_file(ROOT / "README.md", build_readme())
    write_file(ROOT / ".github" / "workflows" / "snake.yml", build_snake_workflow())

    print("\nDone. Commit README.md and .github/workflows/snake.yml")


if __name__ == "__main__":
    main()
'''

out = Path("/mnt/data/github_profile_generator_improved.py")
out.write_text(code, encoding="utf-8")

# Validate Python syntax without executing the generator.
compile(code, str(out), "exec")

print(f"Created: {out}")
print(f"Lines: {len(code.splitlines())}")
print("Syntax check: PASS")
