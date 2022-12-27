# Multimodal deep learning in neuroimaging

The articles related to Multimodal deep learning in neuroimaging are represented in the table. There are collection of articles related to classification task in psychiatry and neurology based on DL methods. In each article some neuroimaging data (sMRI, fMRI, PET, DTI, EEG, MEG, MultiOmics) are fused with eacgh other for improving model predictions. The source code of proposed method is attached if it available.


| Article  | Disease|  Data/Preprocessing    | Method | Fusion technique | Result | Code |
| ------------- | ------------- | ------------- | ------------- |------------- | ------------- |------------- |
| [Multimodal deep learning models for early detection of Alzheimer’s disease stage](https://www.nature.com/articles/s41598-020-74399-w)  | Alzheimer’s disease classification  |  **Data**: ADNI **Count**: 220 patients **Modality**: sMRI,Genetic, Clinical **Preprocessing**: ART toolbox, extract 3D areas of 21 brain regions (associated with Alzheimer’s disease),Features including the brain volumes, voxel intensities, and texture based features. We extract features such as energy, entropy, and 13 Haralick texture features| 3D CNN + Sparse Denoising autoencoders + Dense network  | Intermediate | 0.8% +- 0.03% acc (Control vs MCI) |
| [Multimodal deep learning for Alzheimer’s disease dementia assessment](https://www.nature.com/articles/s41467-022-31037-5?error=cookies_not_supported&code=2b41d5a6-dfac-4c95-b677-24284693af3a) | Alzheimer’s disease classification  |**Data**: ADNI **Modality**: sMRI, Clinical, demographics, past medical history, neuropsychological testing, functional assessments  | 3D CNN + CatBoost  |? | 0.804 ± 0.011 acc (Control vs MCI)   |[code](https://github.com/vkola-lab/ncomms2022)
|[ Combining Neuroimaging and Omics Datasets for Disease Classification Using Graph Neural Networks](https://www.frontiersin.org/articles/10.3389/fnins.2022.866666/full) | Parkinson's disease (PD) classification | Data: PPMI Modality: fMRI, DTI, multi-omics (RNA Expression, Single Nucleotide Polymorphism (SNP), DNA Methylation and non-coding RNA) Preprocessing: fmriPrep  | CycleGAN on structural and functional connectomes to generate missing imaging modalities,
JOIN-GCLA (Joining Omics and Imaging Networks via Graph Convolutional Layers and Attention)|Early| - | - |
