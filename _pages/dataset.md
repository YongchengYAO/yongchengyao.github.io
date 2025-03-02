---
layout: archive
title: "Dataset"
permalink: /dataset/
author_profile: true
---

{% include base_path %}

Dataset Release
------


**OAIZIB-CM**:  507 Knee MR images and segmentation masks, derived from the OAIZIB dataset [[Hugging Face (recommended)](https://huggingface.co/datasets/YongchengYAO/OAIZIB-CM), [Google Drive](https://drive.google.com/drive/folders/13_afAKSH7ZMOI_Nk2gfoihbJKwafw1l9), [Zenodo](https://zenodo.org/records/14934086)]




Redistribution/Modification of Open-access Dataset
------

Since Hugging Face is an excellent platform for sharing models and datasets, along with convenient APIs for downloading and uploading data, I have made several open-access datasets available on 🤗 [YongchengYAO](https://huggingface.co/YongchengYAO), ensuring they comply with the original dataset licenses. Only datasets with licenses that allow redistribution or modification have been released.

Example:

```bash
#!/bin/bash
# $HF_TOKEN is your Hugging Face token
pip install --upgrade huggingface-hub[cli]
huggingface-cli login --token $HF_TOKEN
```

```python
# python
from huggingface_hub import snapshot_download
snapshot_download(repo_id="YongchengYAO/OAIZIB-CM", repo_type='dataset', local_dir="/your/local/folder")
```

### Highlight

- [**Ceph-Biometrics-400**](https://huggingface.co/datasets/YongchengYAO/Ceph-Biometrics-400): 400 head and neck X-ray scans and 19 landmarks for each image, derived from [this data](https://figshare.com/s/37ec464af8e81ae6ebbf)

  <img align="centre" width="600" src="/_pages/dataset.assets/HF-Ceph-Biometrics-400.png" style="margin-right: 15px" /> 
  
- [**FeTA24-Biometrics**](https://huggingface.co/datasets/YongchengYAO/FeTA24-Biometrics): 65 T2-weighted brain MR scans, 7-class segmentation masks, and 5 biometric measurements

  <img align="centre" width="600" src="/_pages/dataset.assets/HF-FeTA24-Biometrics.png" style="margin-right: 15px" /> 

