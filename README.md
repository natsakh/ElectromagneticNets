# ElectromagneticNets

Research code and Jupyter notebooks for computational electromagnetics, including physics-informed neural networks (PINNs) and analytical solutions for electromagnetic waves in time-varying media.

## Code accompanying papers

### Analytical benchmarks for initial value problems

**Physics-Informed Neural Networks for Electromagnetic Wave Propagation in Time-Varying Media: Analytical Benchmarks for Initial Value Problems**

Five notebooks accompanying the manuscript, using a first-order Maxwell system formulation and sinusoidal activation functions. PINN solutions are validated against analytical benchmarks.

**[Open notebooks →](./TimeVaryingMedia/PINNs/InitialValueProblems/AnalyticalBenchmarks/)**

### UkrMW 2026

**Physics-Informed Neural Networks for Temporal Electromagnetic Problems in Time-Varying Media**

N. Sakhnenko, *2026 IEEE 3rd Ukrainian Microwave Week (UkrMW)*, pp. 460–463, 2026.

Three notebooks accompanying the published conference paper, using a second-order differential equation formulation and tanh activation functions.

**[Open notebooks →](./TimeVaryingMedia/PINNs/InitialValueProblems/UkrMW_2026/)**

## Running the notebooks

All notebooks accompanying the two papers above can be run in Google Colab.

## Repository contents

- [TimeVaryingMedia/Analytics](./TimeVaryingMedia/Analytics/) — analytical solutions for electromagnetic problems in time-varying media.
- [TimeVaryingMedia/PINNs](./TimeVaryingMedia/PINNs/) — physics-informed neural networks for time-varying electromagnetic media.

## Citation

If you use the code or results in your research, please cite the corresponding paper.

For the UkrMW 2026 notebooks:

```bibtex
@inproceedings{sakhnenko2026temporal,
  author    = {Sakhnenko, N.},
  title     = {Physics-Informed Neural Networks for Temporal
               Electromagnetic Problems in Time-Varying Media},
  booktitle = {2026 IEEE 3rd Ukrainian Microwave Week (UkrMW)},
  pages     = {460--463},
  year      = {2026}
}
```

