<div align="center">

# Thiago Valentín Stilo Limarino

### Backend Developer · Python · Incoming Systems Engineering Student (UTN)

<p align="center">
  <a href="mailto:stilothiagovalentin@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-blue?style=flat-square&logo=gmail" alt="Email"></a>
  <a href="https://github.com/thiagostilo2121"><img src="https://img.shields.io/badge/GitHub-thiagostilo2121-black?style=flat-square&logo=github" alt="GitHub"></a>
  <a href="https://instagram.com/stilo.tvl"><img src="https://img.shields.io/badge/Instagram-stilo.tvl-E4405F?style=flat-square&logo=instagram" alt="Instagram"></a>
  <img src="https://img.shields.io/badge/Location-Buenos%20Aires%2C%20Argentina-green?style=flat-square" alt="Location">
</p>

<p align="center">
  <a href="https://hub.xerj.org/contributors/thiagostilo2121"><img src="https://hub.xerj.org/contributors/thiagostilo2121/badge.svg" alt="XERJ Corpus Hub contributor"></a>
</p>

<a href="README.md">Versión en español</a>

</div>

> **Open to:** my first backend developer role, remote. Part-time from February 2027, UTC-3.

## 📌 About me

Self-taught backend developer based in Buenos Aires, Argentina. I work mainly with Python, and I care about system design, APIs and databases.

I started programming at eight with games in PowerPoint, Roblox Studio and Scratch. At eleven I moved to Python and I have learned on my own since then, with personal projects as my main method of study.

I am interested in the context where software lives: which problem an organization needs to solve, which constraints it faces, and which technical and economic decisions make a solution viable.

## 🛠️ Technologies and tools

| Category | Tools |
| :--- | :--- |
| **Languages** | `Python` · `Rust` (learning) |
| **Backend** | `FastAPI` · `Pydantic` · `SQLAlchemy` · `SQLModel` |
| **Databases** | `PostgreSQL` · `SQLite` · `MySQL` |
| **Migrations** | `Alembic` |
| **Testing** | `pytest` |
| **CI/CD** | `GitHub Actions` |
| **Documentation** | `Markdown` · `Mermaid` |
| **Environment** | `Linux` · `Git` · `GitHub` |

> This list covers tools I have used in projects or study actively. It does not imply the same level of expertise in all of them.

## 🔬 Projects

### 🐏 [RAMTable](https://github.com/thiagostilo2121/ramtable_py): typed in-memory tables for Python

A library with no runtime dependencies. You declare a column schema and every row is validated on insert. Data lives in memory, with no SQL and no disk writes.

```bash
python -m pip install ramtable
```

```python
from ramtable import Table

people = Table(name="people", columns={"id": int, "name": str, "age": int})
people.rows.insert({"id": 1, "name": "Ada", "age": 36})

older = people.rows.filter({"age": {">": 30}})
print([row["name"] for row in older])
# ['Ada']
```

Available on PyPI (v0.5.0), with its own documentation and an MIT license. CI runs the test suite on Python 3.11 through 3.15, builds the wheel, and runs the quick-start example against the installed package.

[PyPI](https://pypi.org/project/ramtable/) · [Documentation](https://thiagostilo2121.github.io/ramtable_py/) · [Source](https://github.com/thiagostilo2121/ramtable_py) · [XERJ Corpus Hub](https://hub.xerj.org/corpus/thiagostilo2121--ramtable-py)

### 📚 XERJ Corpus Hub contribution

XERJ selected commit `f4d078b` in RAMTable, "add insert defaults for table columns", as a reference example for AI agents: 6 files and 543 lines across `tests` and `src/ramtable`. The hub indexes the whole repository at that commit, under the MIT license with attribution to the author.

[Corpus](https://hub.xerj.org/corpus/thiagostilo2121--ramtable-py) · [Contributor profile](https://hub.xerj.org/contributors/thiagostilo2121)

### 🪨 PetroLens: petrographic analysis assistant · in development

An application to assist the analysis of rock thin sections observed under a microscope. It combines image processing with petrological criteria to identify mineral phases and textural features, and to automate part of the counting and description work.

The design separates the application from the processing models, so analysis techniques can change without a rewrite of the rest of the system. The goal is to support the geologist's judgement, not replace it.

I learn petrology from my grandfather, [Carlos Oscar Limarino](https://www.researchgate.net/profile/Carlos-Limarino), PhD in Geological Sciences, CONICET senior researcher and UBA professor emeritus, with a career in Paleozoic sedimentology and stratigraphy. That is why I know the problem firsthand instead of from the outside.

The repository stays private while the project takes shape. I can walk through progress, screenshots and design decisions in a conversation.

### 🛒 [Pedilo API](https://github.com/thiagostilo2121/pedilo-api): order management backend · discontinued

Backend for an order platform aimed at small food businesses. I worked on authentication, persistence, order logic and the overall organization of the application.

It was my first time carrying a complete backend application with a concrete commercial purpose. The project did not continue, but it marked the move from isolated exercises to a product with users and real needs.

### 🌐 [OpenArg Backend](https://github.com/colossus-lab/openarg_backend): open source contribution

I wrote the backend's technical documentation: I restructured the existing content and added Mermaid diagrams for architecture and flow. Two commits landed in the repository in March 2026.

It was my first contribution to a codebase I did not write, inside a collaborative workflow. It forced me to read the system before writing about it.

[See contributions](https://github.com/colossus-lab/openarg_backend/commits?author=thiagostilo2121)

## 🤝 Complementary experience

- **Student delegate (4 years):** I represented students before school authorities and coordinated groups of more than 30 people.
- **Concejales del Futuro (2025, San Miguel, 2nd place):** a municipal program where student teams draft an ordinance to improve their school. Five people on my team, 30 schools competing, and a prize of 16 million pesos that we used to build a sports court.
- **Private tutoring (1 year):** Mathematics and Accounting for high school students, with 8 students and around 50 teaching hours.
- **Food venture:** with friends we built the brand, logo, Instagram account and a growth plan to sell small cakes. The project did not continue because the market already had established competitors. That is where I learned about pricing, promotion and competition.

## 🎓 Education and languages

- **High school:** orientation in Economics and Business Management. Strong academic record.
- **School honors:** Best Average, Best Classmate and provincial flag bearer.
- **Computer Technician:** training track within secondary education.
- **Higher education:** incoming student in Systems Engineering, Universidad Tecnológica Nacional (UTN).
- **Spanish:** native.
- **English:** B2 from a language institute, no international certification.

## 🎯 Professional goals

I want my first backend experience inside a team with established practices: code review, testing, deployment and work on a shared codebase.

In the medium term I want to add architecture and system design to that base. In the long term, I want to combine technology, analysis and business insight in products of my own.

---

<div align="center">

*I care about building technology, but above all about understanding the problems that make it necessary.*

</div>
