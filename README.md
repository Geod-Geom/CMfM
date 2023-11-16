# CMfM - Crack Monitoring from Motion
<p align="justify"> 
<strong>Crack Monitoring from Motion (CMfM)</strong> integrates photogrammetric techniques with deep learning methods for the automatic detection and monitoring of cracks. CMfM uses a series of images collected by non-fixed cameras to monitor crack propagation over time. Unlike conventional techniques, CMfM does not require fixed artificial targets and overcomes the limitations of using a fixed camera of the 2D DIC. 
</p>
<p align="justify"> 
The approach employs <strong>Convolutional Neural Networks (CNNs)</strong> for automatically detecting the shape of the cracks and a skeletonization approach for delineating the centre line of the defects and for automatically selecting the points of interest around the cracked area. Then, it computes the change in the distance between the selected points on the left and right sides of the crack for estimating the crack width propagation over time. The proposed approach is based on homography estimation and template matching techniques. The workflow is shown below.
</p>

<p align="center"> 
<img 
  src="/Figures_for_README/CMfM_workflow.png"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; width: 800px"; center>
</p>

This work is part of the [TACK project](https://www.tackproject.xyz/).

## Contents  

- [Installation](#installation)
- [Usage](#usage)
- [Datasets](#datasets)
- [Citations](#citations)   
- [License](#license)   
<a name="headers"/>

## Installation
- Download Python 3
- Install the packages:

```
pip install -r requirements.txt
```

## Usage

For testing the code, please run the notebook in the notebook folder. The notebook will be uploaded soon.

## Datasets

Datasets related to the project:

- [Dataset 1](https://data.mendeley.com/datasets/dns97tfdjn/1)
- [Dataset 2](https://data.mendeley.com/datasets/z3yc9z84tk/2)

If you use the datasets in your research, please cite:
- *Sjölander, Andreas; Belloni, Valeria; Peterson, Viktor; Ledin, Jonatan* (2023). **Experimental dataset to assess the structural performance of cracked reinforced concrete using Digital Image Correlation techniques with fixed and moving cameras**. In: Data in Brief, Volume 51, https://doi.org/10.1016/j.dib.2023.109703
- *Sjölander, Andreas; Belloni, Valeria; Nascetti, Andrea* (2022), **Dataset to track concrete cracking using DIC with fixed and moving camera**, Mendeley Data, V1, doi: 10.17632/dns97tfdjn.1
- *Sjölander, Andreas; Belloni, Valeria; Peterson, Viktor; Ledin, Jonatan* (2023), **Dataset to assess the structural performance of cracked reinforced concrete using FEM, DIC and CMfM**, Mendeley Data, V2, doi: 10.17632/z3yc9z84tk.2

## Citations
 
If you use CMfM in your research, please cite the following paper:

- *Valeria Belloni and Andreas Sjölander and Roberta Ravanelli and Mattia Crespi and Andrea Nascetti* (2023). **Crack Monitoring from Motion (CMfM): Crack detection and measurement using cameras with non-fixed positions**. In: Automation in Construction, vol 156, https://doi.org/10.1016/j.autcon.2023.105072

For general information on the TACK project, please refer to:

- *Valeria Belloni and Andreas Sjölander and Roberta Ravanelli and Mattia Crespi and Andrea Nascetti* (2020). **TACK PROJECT: TUNNEL AND BRIDGE AUTOMATIC CRACK MONITORING USING DEEP LEARNING AND PHOTOGRAMMETRY**. In:Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci., XLIII-B4-2020, 741–745, https://doi.org/10.5194/isprs-archives-XLIII-B4-2020-741-2020

For general information on the use of standard Digital Image Correlation (DIC), please refer to:

- *Valeria Belloni and Roberta Ravanelli and Andrea Nascetti and Martina Di Rita and Dimitilla Mattei and Mattia Crespi* (2019). **py2DIC: A New Free and Open Source Software for Displacement and Strain Measurements in the Field of Experimental Mechanics**. In: Sensors 19, 19, 3823, https://doi.org/10.3390/s19183832
  
## License
Code is released for non-commercial and research purposes only. For commercial purposes, please contact the authors.
