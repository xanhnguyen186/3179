# Is Australia Ready for AI?

An interactive data-storytelling visualisation exploring Australia's position in the global AI shift — and what it means for students preparing for AI-driven study and careers. Built with **Vega-Lite**, **HTML**, and **CSS** as a single-page scrollytelling narrative.

🔗 **[View the live visualisation »](https://xanhnguyen186.github.io/AI-in-Australia-Visualisation/)**

---

## Overview

AI is transforming the world — so where does Australia stand, and what does it mean for the next generation entering the workforce?

This project answers that question through an interactive, scroll-driven narrative that moves from the global picture down to the individual student. It weaves seven datasets into one continuous story across three acts: **Is Australia ready for AI? · How are students using it? · Will AI create opportunities or take them away?**

The design goal was not just to chart data, but to build an argument — every visual advances a thesis: *AI is essential for students' study and career readiness, and Australia is emerging as a leader worth paying attention to.*

---

## The Story

**Act 1 — Is Australia Ready for AI?**
A choroparth of the IMF AI Preparedness Index (2023) and adoption rates (2025) shows Australia keeping pace with advanced economies in preparedness and moving to the top in adoption. A dumbbell chart and diverging bars then track how AI daily active users and adoption rates shifted across Australian industries (2023–2024), revealing where growth is accelerating versus saturating.

**Act 2 — How Are Students Using AI?**
A donut chart shows that 81.3% of high-school students already use AI for study. Interactive views break down which AI tools dominate by grade level, and a heatmap links AI use in exam preparation to student stress levels — showing AI reliance peaks under the highest exam pressure.

**Act 3 — Opportunities or Threat?**
Salary-range charts (filterable by industry and experience) show strong AI career prospects at every level, while an animated year-slider explores the tension between AI-driven revenue growth and job displacement. A skills word cloud closes the argument with what students need to stay competitive.

---

## Interactive Features

- **Scrollytelling layout** — the narrative unfolds as you scroll, pairing each chart with its interpretation.
- **Industry selectors** — filter AI usage and adoption trends by industry.
- **Grade and tool filters** — explore how AI tool preferences shift across school grades.
- **Salary explorer** — choose industry and experience level to see projected AI salary ranges.
- **Year slider** — animate how AI content volume and job displacement evolve over time.
- **Glassmorphism UI** — a custom CSS design system for a polished, modern feel.

---

## Tools

| Purpose | Tool |
|---------|------|
| Charts & interactivity | Vega-Lite |
| Layout & structure | HTML |
| Styling & design | CSS (glassmorphism) |
| Hosting | GitHub Pages |

---

## Key Insights

- **Australia is embracing AI, not just ready for it** — top-tier on the global adoption rate by 2025.
- **Education leads student uptake** — 81.3% of high-school students use AI tools for study, making it a mainstream learning aid.
- **Tool use matures with grade level** — students experiment across tools (ChatGPT, Gemini, Notion, QuillBot) as study needs deepen.
- **AI reliance peaks under exam stress** — usage is highest at the top stress levels, positioning AI as a pressure-relief study aid.
- **Strong career prospects, real risks** — AI offers rising salaries across experience levels, but industries with heavy AI use also see greater job displacement — making adaptability essential.

---

## Data Sources

- IMF — [AI Preparedness Index (AIPI)](https://www.imf.org/external/datamapper/datasets/AIPI)
- Kaggle — [AI tool usage among global high-school students](https://www.kaggle.com/datasets/dakshbhatnagar08/ai-tools-usage-among-global-high-school-students)
- Kaggle — [Global AI tool adoption across industries](https://www.kaggle.com/datasets/tfisthis/global-ai-tool-adoption-across-industries)
- Kaggle — [Teen mental health and habits](https://www.kaggle.com/datasets/dakshbhatnagar08/inside-teen-minds-global-mental-health-and-habits)
- Kaggle — [Global high-school student lifestyle and wellness](https://www.kaggle.com/datasets/dakshbhatnagar08/global-high-school-student-lifestyle-and-wellness)
- Kaggle — [Global AI job market and salary trends 2025](https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025)
- Kaggle — [Impact of AI on digital media 2020–2025](https://www.kaggle.com/datasets/atharvasoundankar/impact-of-ai-on-digital-media-2020-2025)

---

## How to Run Locally

1. Clone or download this repository.
2. Open `index.html` in a browser — the Vega-Lite charts load from the embedded specifications.
3. Or simply visit the [live version on GitHub Pages](https://xanhnguyen186.github.io/AI-in-Australia-Visualisation/).

---

*Visualisation by Nhu Xuan Anh Nguyen — an interactive data-storytelling project built with Vega-Lite, HTML, and CSS.*
