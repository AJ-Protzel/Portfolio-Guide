# Adrien's Portfolio 🗺

Welcome to my portfolio 👋🏼 — a collection of projects spanning data engineering, pipeline automation, analytics, and software engineering.

## Table of Contents 📚
- [Data Engineering](#data-engineering)
- [Data Analysis & Visualization](#data-analysis--visualization)
- [Software Engineering](#software-engineering)
- [Computer Graphics](#computer-graphics)
- [Coursework](#coursework)

## Data Engineering
| Project Link | Date | Tools | Project Description |
|---|---|---|---|
| 🎯 [Apply Engine](https://github.com/AJ-Protzel/apply-engine) | Aug 2026 | Python, PostgreSQL/Supabase, GitHub Actions, pytest | A job-application pipeline that sources, filters, and ranks postings from nine public ATS APIs, then stops at the submit button. Ingests on a daily schedule into Postgres, normalizes and dedupes across sources, and passes every posting through a filter layer built as pure functions with 49 tests. Each rejection records the rule that caused it, so over-strict filters surface as a number rather than a hunch. Scoring runs on two axes — role fit and whether the job compounds a résumé — and both thresholds are config, not code. |
| 💰 [Transaction Pipeline](https://github.com/AJ-Protzel/Transaction-Pipeline) | Apr 2025 | Python, pandas, tkinter, tkinterdnd2 | An end-to-end pipeline that imports, merges, cleans, and categorizes bank and credit-card statement exports from multiple institutions. Organizes raw CSVs by bank and card type, normalizes inconsistent headers, strips malformed rows, and maps transaction descriptions to standardized categories, emitting a single clean CSV and JSON. Unmapped descriptions trigger a prompt so new keyword rules can be added to config for future runs. |

## Data Analysis & Visualization
| Project Link | Date | Tools | Project Description |
|---|---|---|---|
| 👩🏻‍⚕️ [Bellabeat Case Study](https://github.com/AJ-Protzel/Bellabeat-Case-Study) | Jan 2025 | Python, Excel | Analyzed Fitbit usage data from 30 users to uncover trends in activity, sleep, and device-wear patterns that could inform Bellabeat's marketing strategy. Cleaned and normalized minute-level and daily CSV data in Python, then identified mid-week activity peaks, the relationship between sleep duration and step count, and coverage gaps caused by weekend non-wear behavior. |
| 💡 [Data Professional Survey Breakdown](https://github.com/AJ-Protzel/Data-Professional-Survey-Breakdown) | Jan 2025 | Power BI, Excel | Analyzed a survey of data professionals to surface trends in salaries, language preferences, job satisfaction, and barriers to entering the field. Cleaned and transformed the raw survey data in Power Query, then built an interactive dashboard covering demographic breakdowns, tool usage, and compensation. |
| 🧬 [NYC Covid Analysis](https://github.com/AJ-Protzel/NYC-Covid) | Mar 2023 | R, RStudio, Shiny | Analyzed NYC Department of Health COVID-19 data to visualize the pandemic's impact on cases, deaths, and hospitalizations over time. Cleaned and transformed daily count data in R, then built an interactive Shiny app to explore distinct infection waves and breakdowns by age, gender, and borough. |

## Software Engineering
| Project Link | Date | Tools | Project Description |
|---|---|---|---|
| 💻 [SpeedScore — Software Engineering Methods](https://github.com/AJ-Protzel/Spring-2026-CS561-Software-Engineering_Methods) | May 2026 | JavaScript, HTML/CSS, Playwright, Node.js, Git | Five labs building features on SpeedScore, a single-page speedgolf app, using professional team workflows: feature branches, merge-conflict resolution, issue-driven development, and code review across a shared codebase. Expanded Playwright coverage for accessibility and keyboard navigation, and produced formal inspection reports against structured review checklists. |

## Computer Graphics
| Project Link | Date | Tools | Project Description |
|---|---|---|---|
| 🎨 [GLSL Shader Projects](https://github.com/AJ-Protzel/Winter-2026-CS557-Computer-Graphics-Shaders) | Mar 2026 | GLSL, C++, OpenGL | Eight shader projects progressing from per-fragment ADS lighting to noise-displaced surfaces, refraction with adjustable index-of-refraction, an image-warping "magic lens," time-animated textures, geometry-stage effects, and a final 32-step ray march with a movable light. |

## Coursework
Graduate coursework at Oregon State University, kept as a record of what each course covered. Some courses were written-assignment only, so those repositories hold reports rather than code.

| Course | Focus |
|---|---|
| [CS 540 — Database Management Systems](https://github.com/AJ-Protzel/Spring-2025-CS540-Database-Management-Systems) | Relational algebra, a C++ binary storage manager, hash indexing, query optimization, concurrency control |
| [CS 512 — Data Science Tools & Programming](https://github.com/AJ-Protzel/Winter-2025-CS512-Data-Science-Tools-Programming) | pandas, SQL/SQLite, PySpark, end-to-end data wrangling |
| [CS 550 — Intro to Computer Graphics](https://github.com/AJ-Protzel/Fall-2025-CS550-Intro-to-Computer-Graphics) | C++ and OpenGL fundamentals |
| [CS 565 — Human-Computer Interaction](https://github.com/AJ-Protzel/Spring-2025-CS565-Human-Computer-Interaction) | User research, journey mapping, heuristic evaluation, paper prototyping, usability testing |
