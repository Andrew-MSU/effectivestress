# Interactive Mohr Circle and Failure Envelope

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18775515.svg)](https://doi.org/10.5281/zenodo.18775515)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Andrew-MSU/effectivestress/blob/main/Mohr_Circle_Effective_Shear_Stress.ipynb)

A Jupyter/Colab notebook (`Mohr_Circle_Effective_Shear_Stress.ipynb`) for exploring stress states with Mohr circles. It covers total versus effective stress and the Coulomb failure envelope, and shows the physical orientation of fault planes that could fail.

## Features

- **Interactive sliders** for σ1, σ3, pore-fluid pressure (Pf) and the friction coefficient (μ).
- **Total and effective stress circles** that show how pore pressure shifts the stress state.
- **A linear Coulomb failure envelope** based on μ.
- **Hydrofracture detection**, which highlights conditions for tensile failure.
- **Unstable orientations**, which marks where the effective circle crosses the envelope and reports the minimum and maximum dips of unstable planes.
- **A physical block diagram** showing the principal stresses and any unstable faults or tensile fractures.
- **The optimal fault plane** for frictional sliding under the Coulomb criterion.

## How to use

1. Open the notebook in Colab with the badge above. You can also run it locally with `matplotlib`, `numpy` and `ipywidgets` installed.
2. Run the code cell that defines `plot_mohr_and_physical` and calls `ipywidgets.interact`.
3. Move the sliders. Both plots update live.

## Citation

Laskowski, A. (2026). *Andrew-MSU/effectivestress: Effective Stress and the Mohr Circle Diagram* (v1.0.0). Zenodo. https://doi.org/10.5281/zenodo.18775515

## License

MIT (see `LICENSE`).
