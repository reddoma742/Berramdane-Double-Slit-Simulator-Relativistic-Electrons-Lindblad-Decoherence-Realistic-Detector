# Berramdane-Double-Slit-Simulator-Relativistic-Electrons-Lindblad-Decoherence-Realistic-Detector
Full‑wave simulation of electron double‑slit experiment including relativistic de Broglie wavelength, Feynman path integral, Lindblad decoherence (observer effect), realistic detector (Johnson noise, dark counts), Wigner function, and complementarity V²+K² ≤ 1. Interactive Jupyter widgets. Ready to run.
# Berramdane Double-Slit Simulator

**Relativistic electrons + Lindblad decoherence + realistic detector + Wigner function**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

## Overview

A full‑wave, interactive simulation of the **electron double‑slit experiment** that combines:

- ✅ **Relativistic de Broglie wavelength** – correct for high‑energy electrons (`v` up to 0.5c).
- ✅ **Feynman path integral** – wave interference pattern for 2‑5 slits.
- ✅ **Lindblad decoherence** – mimics the **observer effect** (which‑path knowledge `K` destroys coherence).
- ✅ **Realistic detector** – finite efficiency, dark counts, Johnson‑Nyquist noise, and pixel PSF.
- ✅ **Wigner quasiprobability function** – visualise the quantum state (for 2 slits).
- ✅ **Complementarity** – automatically checks `V² + K² ≤ 1` (Bohr‑Einstein).
- ✅ **Jupyter widgets** – all parameters are tunable in real time.

## Physics at a glance

| Feature               | Implementation                                                                 |
|-----------------------|--------------------------------------------------------------------------------|
| Electron source      | Monochromatic velocity `v` (optional spectral width)                          |
| Slits                | `a` width, `d` separation, `N` slits (2,3,5)                                  |
| Decoherence          | Lindblad master equation (`γ_meas` or directly `K` slider)                    |
| Detector             | Efficiency `η`, dark count rate `DCR`, temperature `T` (Johnson noise)        |
| Visualisation        | Intensity pattern, density matrix, Wigner function, complementarity curve     |

## Requirements

- Python 3.8+
- `numpy`, `matplotlib`, `scipy`, `ipywidgets` (optional for GUI)
- Jupyter notebook / lab (recommended)

Install dependencies:

```bash
pip install numpy matplotlib scipy ipywidgets
