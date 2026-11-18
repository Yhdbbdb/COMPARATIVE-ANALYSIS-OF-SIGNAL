# Comparative Analysis of Radar Signal Classification

This repository documents a comparison of machine learning and deep learning approaches to radar signal classification using MATLAB-simulated data.

## Study overview

The existing project description lists signal-to-noise ratio (SNR), pulse repetition frequency (PRF), pulse width, Doppler shift, center frequency, and bandwidth as features. It names RNN, CNN, SVM, Random Forest, ANN, XGBoost, and LightGBM as compared models.

## Reported results

These accuracy values are reported in the existing README; they have not been independently reproduced:

| Model | Reported accuracy |
| --- | --- |
| RNN | 97% |
| CNN | 95% |
| SVM | 75% |
| Random Forest | 65% |

The repository does not include the dataset, training code, model configurations, or evaluation outputs needed to verify these values. The available README does not specify dataset size, class definitions, split strategy, random seeds, or uncertainty estimates. These figures should not be interpreted as performance on real operational radar data.

## Available materials

- [Project PDF](149_2025329309-1.pdf)
- [Conference certificate](IPACT2025_certificate%2019.pdf)

The PDFs are listed in the repository; their contents and redistribution rights were not reviewed while preparing this README.

## Reproducibility

No runnable training or inference workflow is currently published. MATLAB is identified as the data simulation tool; the training framework and software versions are not specified.

To reproduce the study, the repository needs the signal generator and parameters, dataset schema and labels, preprocessing code, dependency versions, model architectures and hyperparameters, fixed train/validation/test splits, random seeds, and evaluation scripts. Include per-class metrics and confusion matrices, and document how related simulated samples are kept across splits to avoid data leakage.

## Repository status

This is currently a documentation repository, not a runnable software release. The published files are `README.md` and two PDFs.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Suggestions and reproducibility improvements are welcome through [issues](https://github.com/Yhdbbdb/COMPARATIVE-ANALYSIS-OF-SIGNAL/issues) and [pull requests](https://github.com/Yhdbbdb/COMPARATIVE-ANALYSIS-OF-SIGNAL/pulls).

## License

No license was visible in the repository during this review. A proposed MIT license is supplied separately for maintainer approval; it is not effective merely because it is drafted.
