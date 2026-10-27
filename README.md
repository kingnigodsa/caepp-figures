# Carrier-assisted entanglement purification: code for the figures

This repository contains the code that reproduces the numerical figures of

J. Kim, K. Mohan, S. W. Yun, and J. Bae, "Carrier-Assisted Entanglement Purification," *IEEE Journal on Selected Areas in Communications*, vol. 44, pp. 5311–5326, 2026, [doi:10.1109/JSAC.2026.3710152](https://doi.org/10.1109/JSAC.2026.3710152), [arXiv:2509.07514](https://arxiv.org/abs/2509.07514).

## Contents

- `CAEPP_figures.ipynb` computes and plots Figs. 2, 3, 4, 6, 7, 8, and 11 of the published version. It states the model behind each figure and refers to the equations of the paper. A supplementary figure shows the effect of noisy CNOT gates, which Sec. VI-C of the paper discusses without a figure.
- `requirements.txt` lists the Python packages that the notebook needs.

## How to run

Install Python 3 with NumPy and Matplotlib, for example with `pip install -r requirements.txt`.
Open the notebook in Jupyter or Google Colab and run all cells.
The notebook runs in under a minute and saves each figure as a 600-dpi PNG file, for example `fig2a.png`.
It was tested with Python 3.13, NumPy 2.5.3, and Matplotlib 3.11.2.

## Citation

If you use this code, please cite the paper above. Citation metadata is in `CITATION.cff`.

## License

MIT License, see `LICENSE`.
