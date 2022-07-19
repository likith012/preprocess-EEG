## preprocess-EEG

This repostiory contains the code for the preprocessing and visualiation of EEG siganls with subect data provided for ease of experimenting.
 
 #
 
 >The step by step visualization and preprocessing steps include are:
 >- Loading of subject data
 >- Removing unnecessary modalities and channels
 >- Setting up montage
 >- Artifact removal through ICA with visualization for excluding the ICA components
 >- High pass filtering for removal of slow drift
 >- PSD plot for checking powerline noise
 >- Temporal topomap plots 
 >- Topomap plots for each frequency band (alpha, beta, gamma, theta, delta)
 >- Difference of topo plots
