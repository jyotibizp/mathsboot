# Maths & Physics Prerequisites for AI/ML

This repository hosts course materials for "Maths and Physics before diving into AI/ML". It provides a structured path across Mathematics, Physics, and Computer Science foundations needed to succeed in machine learning and modern AI.

## What you'll learn

- Mathematics: Linear Algebra, Probability & Statistics, Calculus, Optimization, Discrete Mathematics
- Physics (supportive): Vectors & Mechanics, Waves & Oscillations, Statistical Physics, Electricity & Magnetism, Quantum Basics
- Computer Science: Algorithms & Data Structures, Complexity Theory, Numerical Methods

See the detailed syllabus in `maths_physics_syllabus_before_ai_ml.MD`.

## Repository layout

- `0-intro/` — Welcome, setup guide, and tooling
- `1-mathematics/` — Lessons, exercises, and solutions by topic
- `2-physics/` — Lessons, exercises, and solutions by topic
- `3-computer-science/` — Lessons, exercises, and solutions by topic
- `assessments/` — Module check-ins and finals
- `reference-materials/` — Handy cheat sheets and quick references
- `submissions/` — Learner workspaces organized by name

## Getting started

1) Read: `0-intro/welcome.md` and `0-intro/setup-guide.md`

2) Set up Python (3.11+ recommended):
   - Create a virtual environment and install dependencies from `root_files/requirements.txt`:
     - Linux/macOS:
       - `python3 -m venv venv`
       - `source venv/bin/activate`
       - `pip install -r root_files/requirements.txt`
     - Windows (PowerShell):
       - `python -m venv venv`
       - `.\n+venv\Scripts\Activate.ps1`
       - `pip install -r root_files/requirements.txt`

3) Optional: Jupyter Lab
   - Local: `jupyter lab`
   - Docker: `docker compose -f root_files/docker-compose.yml up -d` then open `http://localhost:8888`

4) Start learning
   - Begin with `01-mathematics/linear-algebra/lessons/` and follow each lesson with its exercise. Check `solutions/` after attempting.

## Submissions

Place your work under `submissions/<your-name>/<track>/...` (e.g., `submissions/ajay/mathematics/linear-algebra/`). Include a short `README.md` in each project/exercise folder explaining your approach and assumptions.

## Assessments

Formative assessments live under `assessments/<track>/module-1/` and summative finals under `assessments/<track>/final/`.

## Contributing

Contributions are welcome. Keep content concise with worked examples and clear learning objectives. Follow the structure used in existing modules. 