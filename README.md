# Fine-tune_MedSAM
The repository provides code for the fine-tuning process of the MedSAM Model (Segment Anything in Medical Images).

**This notebook is for the process of fine-tuning the MedSAM Model (Segment Anything in Medical Images) using our custom dataset**.

**MedSAM paper:** https://arxiv.org/pdf/2304.12306
**<br>SAM paper:** https://arxiv.org/pdf/2304.02643.pdf​

**MedSAM repository:** https://github.com/bowang-lab/MedSAM
**<br>MedSAM model in Hugging Face:** https://huggingface.co/flaviagiammarino/medsam-vit-base

**Link to the dataset used in this process:** https://drive.google.com/file/d/1m7tMpE9qEcQGQjL_BdMD-Mvgmc44hG1Y/view?usp=drive_link

**Data description**
<br>Image type: 3D (CT Images); Format: NifTI (.nii.gz)
<br>eight: 512px; Width: 512px; Depth: not fixed

This code has taken referance from these notebooks but completely modified to work for our custom dataset.
https://github.com/bnsreenu/python_for_microscopists/blob/master/331_fine_tune_SAM_mito.ipynb
https://github.com/NielsRogge/Transformers-Tutorials/blob/master/SAM/Fine_tune_SAM_(segment_anything)_on_a_custom_dataset.ipynb
