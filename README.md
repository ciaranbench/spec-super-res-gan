# spec-super-res-gan

The numpy files `noisy_data.npy` and `denoised_data.npy` can be downloaded from this [Google Drive link](https://drive.google.com/drive/folders/1owS0jEbU93z9XDw_owVr5Fti1AVfQzL0?usp=sharing).

# TO DO:
- Expand implementation of classical denoising techniques and evaluation (see denoising notebook) (CB)
- Code/train denoisining autoencoder - relevant paper should be in the project overleaf. \cite{abdolghader2021unsupervised} perhaps do single sample and multi sample version. Add this to eval notebook
- Implement cycleGAN in pytorch (MA)
- compare k means with fixed group size on clean, noisy, and adapted spectra as an eval metric
- apply for conference funding from clirpath
Misc
- Train on baselined spectra ?
- Train a supervised net for comparison ?
