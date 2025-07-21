## preprocess-EEG

This repository contains code for the preprocessing and visualization of EEG signals, along with subject data provided for ease of experimentation.
 
 #
 
 >The step by step visualization and preprocessing steps include:
 >- Loading of subject data
 >- Removing unnecessary modalities and channels
 >- Setting up montage
 >- Artifact removal through ICA with visualization for excluding the ICA components
 >- High pass filtering for removal of slow drift
 >- PSD plot for checking powerline noise
 >- Temporal topomap plots 
 >- Topomap plots for each frequency band (alpha, beta, gamma, theta, delta)
 >- Difference of topo plots
