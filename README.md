# Zeppelin CAD Project

This project implements a **Python-based design environment** for a conceptual Zeppelin airship.  
It includes parametric modeling of components (engine, fins, envelope, gondola), a GUI executable,  
and supporting documentation from the class project.

---

## Repository Structure
- **`src/zeppelin/`** — Python source files for the design software.  
- **`notebooks/`** — Jupyter notebooks used for development, experiments, and plotting.  
- **`docs/`** — Final report, presentation slides, and user guide.  
- **`renders/`** — Figures, graphs, and visualizations generated from the project.  
- **`video/`** — Project presentation (also available on [YouTube](https://youtu.be/zmH3zRnvlFg)).  
- **`executables/`** — Compiled GUI application (`Zeppelin.CAD.exe`) — **ignored in Git**, but available via [Releases](../../releases).  

---

## Features
- Modular Python codebase:
  - `Engine.py`, `Envelope.py`, `Fins.py`, `Gondola.py` — Zeppelin components.  
  - `config.py` — Central configuration parameters.  
  - `main.py` — Entry point for running the project.  
- Jupyter notebooks for prototyping geometry and visualizations.  
- Executable GUI (`Zeppelin.CAD.exe`) for demonstration and end-user interaction.  
- Final report, slides, and user guide documenting the design process.  

---

## Documentation
- [User Guide](docs/Zep-CAD%20User%20Guide.pdf)  
- [Final Report](docs/zeppelin_cad_report.pdf)  
- [Presentation Slides](docs/presentation_Zep_CAD.pdf)  
- [Video Presentation](video/Zep_CAD_project_Video.mp4)  
  - Also available on YouTube: [Watch here](https://youtu.be/zmH3zRnvlFg)  

---

## Executable
The compiled application (`Zeppelin.CAD.exe`) is provided separately to avoid bloating the repository.  
Download it from the project’s [GitHub Releases](../../releases).  

---

## License
See [LICENSE](LICENSE).
