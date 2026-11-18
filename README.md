# NeuroFusion Lab (research prototype)

Browser prototype that combines a clinician's assessment, an fMRI slice, EEG (8, 16 or 32 channels; dummy, file or live device) and blood markers into one structured result, with an EEG trial assessment (participant-split cross-validation, accuracy, sensitivity, specificity, AUC).

**All data are synthetic. This is a methods demonstration, not a medical device, and must not be used for diagnosis.**

Live page: https://fadin2006.github.io/neurofusion-lab/

- Single file: `index.html` (no build step, no server code).
- Live EEG (Web Bluetooth for Muse headsets, Web Serial for CSV streams) works in Chrome or Edge over HTTPS, which GitHub Pages provides.

Author: M Fahrudin Muna
