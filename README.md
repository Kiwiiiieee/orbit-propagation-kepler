# Orbit Propagation: Two-Body Problem and Kepler's Equation

*Individual project · AE 311 · Izmir University of Economics · Dec 2025 – Jan 2026*

![Relative radial error of the propagated orbit](figures/kepler.png)

## Engineering question
How accurate is numerical two-body integration compared with the analytical Kepler solution, and how does analytical Keplerian propagation compare with numerical integration for a real satellite?

## Approach
- Project 1: numerical solution of the radial and angular two-body equations for Mercury's orbit, compared with the analytical orbit.
- Project 2: Kepler's equation solved numerically and applied to the Moroccan satellite UM5-EOSAT using real TLE data; analytical Keplerian propagation compared with numerical two-body integration.
- Extension to a translunar Hohmann transfer (patched conics) and restricted three-body Earth–Moon dynamics.

## Results
- Quantified numerical error in conserved quantities (energy, angular momentum) and in position.
- Quantified the discrepancy between analytical and numerical propagation and its sensitivity to numerical accuracy and precision.

## Validation
Analytical benchmark comparison and conservation-law checks.

## Repository contents
- `notebooks/`: Wolfram Language Jupyter notebooks (outputs saved, so results display directly on GitHub)
- `report/`: written report (PDF)
- `figures/`: key figures

## How to run
The notebooks use the Wolfram Language kernel for Jupyter (WolframLanguageForJupyter, Wolfram Engine or Mathematica 14).

Project 2 imports a TLE file (NORAD 60555, UM5-EOSAT). To re-run, download a current TLE and update the file path in the notebook.

## Credits
This project was completed on a course notebook framework by **Prof. Fabrizio Pinto** (Izmir University of Economics), released under CC BY 4.0. The completed notebook, results and written report in this repository are my own work.

## License
CC BY 4.0, consistent with the original course material. Please credit both Prof. Fabrizio Pinto and Kaoutar Ammara.

---
Kaoutar Ammara · Aerospace Engineer · [GitHub](https://github.com/Kiwiiiieee) · [LinkedIn](https://linkedin.com/in/kaoutar-ammara)
