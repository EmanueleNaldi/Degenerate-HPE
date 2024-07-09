# Degenerate-HPE

This repository contains the experimental source code to reproduce the numerical experiments in:

* M. M. Alves, D. A. Lorenz, E. Naldi. A general framework for inexact splitting algorithms with relative errors and applications to Chambolle-Pock and Davis-Yin methods (2024). [ArXiv preprint](https://arxiv.org/abs/2407.05893)

To reproduce the results of the numerical experiments in Section 4.1, run:
```bash
study_InexactCP_vs_CP_vs_CV.ipynb
```

To reproduce the results of the numerical experiments in Section 4.2, run:
```bash
study_InexactDY_vs_DY_vs_FB.ipynb
```

If you find this code useful, please cite the above-mentioned paper:
```BibTeX
@misc{alves2024generalframeworkinexactsplitting,
      title={A general framework for inexact splitting algorithms with relative errors and applications to Chambolle-Pock and Davis-Yin methods}, 
      author={M. Marques Alves and Dirk A. Lorenz and Emanuele Naldi},
      year={2024},
      eprint={2407.05893},
      archivePrefix={arXiv},
      primaryClass={math.OC},
      url={https://arxiv.org/abs/2407.05893}, 
}
```

## Requirements

Please make sure to have the following Python modules installed, most of which should be standard.

* [numpy>=1.20.1](https://pypi.org/project/numpy/)
* [scipy>=1.6.2](https://pypi.org/project/scipy/)
* [matplotlib>=3.3.4](https://pypi.org/project/matplotlib/)

## Acknowledgments  

* All data used for numerical experiments in this project have been created artificially by the authors.

## License  
This project is licensed under the GPLv3 license - see [LICENSE](LICENSE) for details.
