# HERA-RFI
## Hydrogen Epoch of Reionization Array Experiment:Effect of Radio Frequency Interference Excision on 21-cm Power Spectrum

### Abstract
The Epoch of Reionization (EoR) is an era in the history of the Universe when neutral hydrogen was ionised by radiation from the first stars and galaxies. Experiments such as the Hydrogen Epoch of Reionization Array (HERA) are dedicated to measure redshifted 21-cm emission of neutral hydrogen from this epoch. One of the biggest challenges of the experiment is mitigating foreground radiation from our Galaxy which is ~ 5 – 6 orders of magnitude brighter than the EoR signal. Primary objective of HERA is to measure the statistical power spectrum of the EoR signal rather than direct imaging. However, 21-cm power spectrum can be affected by fluctuations in visibilities due to sporadic removal of radio frequency interference (RFI) flagged data samples. RFI is any source of radio-frequency transmission other than the sky signal itself. In this project, we investigate the effect of excising RFI on the 21-cm power spectrum within the context of HERA experiment. We analyse techniques to mitigate the contaminating effects of interference which may affect EoR signal detection. In particular, we use a delay filter based on linear least-squares solver to fit a smooth model to flagged datasets and we shall present results of statistical power spectrum analysis for various simulated test cases which are relevant to the HERA experiment.

This repository consists of jupyter-notebooks of various simulations of point radio souces, foreground and RFI, test cases for least-square delay filter, and power spectrum analysis for each case.
