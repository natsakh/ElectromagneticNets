# Initial Value Problems

Physics-informed neural networks (PINNs) for electromagnetic initial value problems in time-varying media, validated against analytical solutions.

All notebooks can be run in Google Colab.

## Analytical benchmarks

[AnalyticalBenchmarks](./AnalyticalBenchmarks/) contains five notebooks accompanying the manuscript:

*Physics-Informed Neural Networks for Electromagnetic Wave Propagation in Time-Varying Media: Analytical Benchmarks for Initial Value Problems.*

The notebooks use a first-order Maxwell system formulation and sinusoidal activation functions.

## UkrMW 2026

[UkrMW_2026](./UkrMW_2026/) contains three notebooks accompanying the published conference paper:

N. Sakhnenko, “Physics-Informed Neural Networks for Temporal Electromagnetic Problems in Time-Varying Media,” 2026 IEEE 3rd Ukrainian Microwave Week (UkrMW), pp. 460–463, 2026.

These benchmarks use a second-order differential equation formulation and tanh activation functions.

## Citation

If you use these notebooks in your research, please cite the corresponding paper.

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
