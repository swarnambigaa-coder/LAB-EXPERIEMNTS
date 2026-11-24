# Experiment 02: EEG Frequency Band Analysis

**Course:** EC4414 / 19BM414 – MATLAB for Biomedical Engineers  
**Course Outcome:** CO1

## 1. Aim
To inspect an EEG-like signal in the time and frequency domains and estimate power in conventional frequency bands.

## 2. Software requirements
Base MATLAB.

## 3. Theory
The Fourier transform represents a signal as frequency components. This experiment uses a single-sided power spectrum and numerical integration over conventional teaching bands: delta, theta, alpha, beta and gamma.

## 4. Algorithm
1. Generate a synthetic EEG-like mixture with known frequency components.
2. Compute the FFT and single-sided power spectrum.
3. Define frequency limits for each band.
4. Integrate spectral power within each band and display a table.

## 5. Files in this folder
- `code/Experiment_XX.m` – MATLAB implementation.
- `figures/Experiment_XX_reference.png` – explanatory reference figure.
- `results/` – generated outputs; the MATLAB script saves its result here.

## 6. Procedure
1. Open MATLAB.
2. Set the Current Folder to this experiment's `code` folder.
3. Run the script `Experiment_XX.m`.
4. Inspect the figure and any command-window output.
5. Record the observations in your laboratory record.

## 7. Expected observations
- Observe the time-domain EEG-like waveform.
- Identify prominent spectral peaks.
- Compare the estimated band powers.

## 8. Result
The experiment is completed when the script runs, the output figure is generated, and the observations are recorded. Enter actual observations from your MATLAB run; do not copy illustrative values as measured results.

## 9. Review questions
1. What does the FFT reveal that the time plot does not?
2. How does sampling frequency limit the highest observable frequency?
3. Why can EEG band boundaries vary by reference?

## 10. Limitations and responsible use
The supplied program is a teaching demonstration. Synthetic signals/images/data are not clinical evidence. Do not use these scripts for diagnosis, treatment decisions, or claims of clinical accuracy. For real patient data, obtain institutional approval, use de-identified data, and follow applicable data-governance requirements.
