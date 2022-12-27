# Multimodal deep learning in neuroimaging

The articles related to Multimodal deep learning in neuroimaging are represented in the table. There are collection of articles related to classification task in psychiatry and neurology based on DL methods. In each article some neuroimaging data (sMRI, fMRI, PET, DTI, EEG, MEG, MultiOmics) are fused with eacgh other for improving model predictions. The source code of proposed method is attached if it available.


| Article  | Disease|  Data/Preprocessing    | Method | Fusion technique | Result | Code |
| ------------- | ------------- | ------------- | ------------- |------------- | ------------- |------------- |
| [Multimodal deep learning models for early detection of Alzheimer’s disease stage](https://www.nature.com/articles/s41598-020-74399-w)  | Alzheimer’s disease classification  |  **Data**: ADNI **Count**: 220 patients **Modality**: sMRI,Genetic, Clinical **Preprocessing**: ART toolbox, extract 3D areas of 21 brain regions (associated with Alzheimer’s disease),Features including the brain volumes, voxel intensities, and texture based features. We extract features such as energy, entropy, and 13 Haralick texture features| 3D CNN + Sparse Denoising autoencoders + Dense network  | Intermediate | 0.8% +- 0.03% acc (Control vs MCI) |
| [Multimodal deep learning for Alzheimer’s disease dementia assessment](https://www.nature.com/articles/s41467-022-31037-5?error=cookies_not_supported&code=2b41d5a6-dfac-4c95-b677-24284693af3a) | Content Cell  |**Data**: ADNI **Modality**: sMRI, Clinical, demographics, past medical history, neuropsychological testing, functional assessments  | 3D CNN + CatBoost  |Content Cell  | Content Cell  |
