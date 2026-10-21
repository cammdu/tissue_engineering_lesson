# Tissue engineering for soft and biohybrid robotics: a hands-on lesson

Beginner-friendly Jupyter notebooks on engineered tissue as a material and as an actuator.

| Notebook | Topic |
|---|---|
| `01_soft_materials_and_scaffolds.ipynb` | The tissue engineering triad; landmark biohybrid robots; stiffness of tissues vs. materials; tensile testing; designing a hydrogel to a target stiffness |
| `02_muscle_actuators_and_oxygen.ipynb` | Twitch, summation and tetanus; force-frequency curves; the oxygen diffusion limit; why many thin muscle strands beat one thick one |

Model parameters are illustrative orders of magnitude, not measured values.

## How to run
Open a notebook in [Google Colab](https://colab.research.google.com) via its GitHub URL and run cells with Shift+Enter. No data files are needed.

Locally:
```bash
python3 -m pip install -r requirements.txt
jupyter lab
```

## Key references
- Nawroth et al. (2012). A tissue-engineered jellyfish with biomimetic propulsion. *Nature Biotechnology*.
- Park et al. (2016). Phototactic guidance of a tissue-engineered soft-robotic ray. *Science*.
- Raman et al. (2016). Optogenetic skeletal muscle-powered adaptive biological machines. *PNAS*.
- Kawai et al. (2022). Living skin on a robot. *Matter*.
- Engler et al. (2006). Matrix elasticity directs stem cell lineage specification. *Cell*.
