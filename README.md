# Experiment 01: ECG Noise Removal and QRS Detection

**Course:** EC4414 / 19BM414 – MATLAB for Biomedical Engineers  
**Course Outcome:** CO1

## 1. Aim
To demonstrate removal of baseline wander and noise from an ECG-like waveform and identify candidate R peaks.

## 2. Software requirements
Base MATLAB.

## 3. Theory
ECG contains P, QRS and T components. Baseline wander is a low-frequency drift; high-frequency noise may arise from instrumentation or muscle activity. A moving-average estimate is used here as a simple baseline approximation.

## 4. Algorithm
1. Generate a synthetic ECG-like waveform with P-QRS-T components.
2. Add baseline wander, power-line interference and random noise.
3. Estimate baseline using a moving average and subtract it.
4. Smooth the corrected signal.
5. Find local maxima above a threshold while enforcing a refractory interval.

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
- Compare the noisy and filtered waveforms.
- Count detected candidate R peaks.
- If at least two peaks are found, calculate RR intervals and mean rate.

## 8. Result
The experiment is completed when the script runs, the output figure is generated, and the observations are recorded. Enter actual observations from your MATLAB run; do not copy illustrative values as measured results.

## 9. Review questions
1. Why is a refractory interval needed?
2. What are the limitations of moving-average baseline correction?
3. Why must a detector be validated before clinical use?

## 10. Limitations and responsible use
The supplied program is a teaching demonstration. Synthetic signals/images/data are not clinical evidence. Do not use these scripts for diagnosis, treatment decisions, or claims of clinical accuracy. For real patient data, obtain institutional approval, use de-identified data, and follow applicable data-governance requirements.
