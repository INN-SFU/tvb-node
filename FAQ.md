# Frequently Asked Questions (FAQ)

## Can I create TVB models without individualized MRI data?
It is possible to model datasets that lack individualized MRI (e.g., M/EEG data) or datasets without diffusion MRI. Some approaches include:
- Population-averaged structural connectomes: using age-matched average structural connectivity matrices from openly available datasets.
- Alternative constraints: every individual's model receives the same structural connectivity, but the models are informed by other imaging such as [PET](https://www.frontiersin.org/journals/computational-neuroscience/articles/10.3389/fncom.2019.00054/full), or known features like lesions.

The approach you take will depend on the research questions you want to address.

## Can I apply TVB to MEG or EEG data?
[This tutorial](https://thevirtualbrain.org/tvb/zwei/newswire-educase/single/42189-learn-neural-masses-as-source-models-for-eeg-and-meg) covers the selection of neural mass models for MEG and EEG modelling. The workflow for our TVB-node workshop focuses on fMRI, but similar modelling principles apply to MEG and EEG. If you're looking to work with M/EEG models following this workshop, some notable steps will be to:
1. Determine which MEG or EEG features you want to fit the models to, and
2. Ensuring that your neural mass model can reproduce those features.
