# OCT-seg-papers
Personal paper/code/dataset list on OCT segmentation

## Background
- 2018 Prevalences of segmentation errors and motion artifacts in OCT-angiography differ among retinal diseases \
https://link.springer.com/article/10.1007/s00417-018-4053-2 

- 2013 A Review of Algorithms for Segmentation of Optical Coherence Tomography from Retina \
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3785070/

## Deep Learning

- 2021 (MGU-Net) Multi-scale GCN-assisted two-stage network for joint segmentation of retinal layers and discs in peripapillary OCT images \
https://www.osapublishing.org/boe/fulltext.cfm?uri=boe-12-4-2204&id=449401 \
code: https://github.com/Jiaxuan-Li/MGU-Net \
dataset: http://www.yuyeling.com/project/mgu-net/

- 2021 Deep learning based joint segmentation and characterization of multi-class retinal fluid lesions on OCT scans for clinical use in anti-VEGF therapy \
https://doi.org/10.1016/j.compbiomed.2021.104727 \
recurrent ASPP based deep encoder-decoder network, Dice loss function

- 2019 Fully Convolutional Boundary Regression for Retina OCT Segmentation \
https://link.springer.com/chapter/10.1007/978-3-030-32239-7_14 \
preprocessing code: https://github.com/heyufan1995/oct_preprocess \
2D Unet, column wise softmax for boundary

- 2020 (Google DeepMind) Predicting conversion to wet age-related macular degeneration using deep learning \
https://rdcu.be/b4fgc 

- 2018 (Google DeepMind) Clinically applicable deep learning for diagnosis and referral in retinal disease \
https://rdcu.be/4sNU 
9 neighboring B-scans for central B-scan segmentation

- 2017 ReLayNet: retinal layer and fluid segmentation of macular optical coherence tomography using fully convolutional networks \
https://arxiv.org/abs/1704.02161 \
code: https://github.com/ai-med/relaynet_pytorch

- 2017 Automatic segmentation of nine retinal layer boundaries in OCT images of non-exudative AMD patients using deep learning and graph search \
https://www.osapublishing.org/DirectPDFAccess/C104984E-97A7-91AD-422CBA1DAF54A23D_363511/boe-8-5-2732.pdf?da=1&id=363511&seq=0&mobile=no


- AI challenge Unet DME segmentation \
https://github.com/ShawnBIT/AI-Challenger-Retinal-Edema-Segmentation


- caffe code: https://github.com/SJD095/OCT-Segmentation

## Conventional

- 2018 A Supervised Joint Multi-layer Segmentation Framework for Retinal Optical Coherence Tomography Images using Conditional Random Field \
https://www.sciencedirect.com/science/article/pii/S0169260717314645 \
code: https://github.com/arunava555/OCT-layer-segmentation \
CRF, code in Matlab


- Segmentation and analysis of retinal layers from individual OCT b-scans \
code: https://github.com/sarastokes/OCT-tools 


- 2014 Probabilistic intra-retinal layer segmentation in 3-D OCT images using global shape regularization \
http://www.sciencedirect.com/science/article/pii/S1361841514000449 \
code: https://github.com/FabianRathke/octSegmentation \
(working version https://github.com/yiqian-wang/octSegmentation) \
probabilistic graphical model, 9 boundaries, 2D and 3D

## Dataset

- 2021 (MGU-Net) Multi-scale GCN-assisted two-stage network for joint segmentation of retinal layers and discs in peripapillary OCT images \
dataset: http://www.yuyeling.com/project/mgu-net/

- 2019 RETOUCH: the retinal OCT fluid detection and segmentation benchmark and challenge
https://ieeexplore.ieee.org/document/8653407 \
https://retouch.grand-challenge.org 

- 2019 OCTID: Optical coherence tomography image database
https://arxiv.org/ftp/arxiv/papers/1812/1812.07056.pdf \

- 2018 Identifying medical diagnoses and treatable diseases by image-based deep learning
https://www.sciencedirect.com/science/article/pii/S0092867418301545 \


- 2014 Diabetic macular edema dataset \
http://people.duke.edu/~sf59/Chiu_BOE_2014_dataset.htm \
preprocessing code: https://github.com/heyufan1995/oct_preprocess

- Healthy and Multiple Sclerosis dataset \
http://iacl.ece.jhu.edu/index.php?title=Resources

- Retinal-OCT-Images \
https://github.com/lidaboo/Retinal-OCT-Images

## Other Resources

- OCT converter \
https://github.com/marksgraham/OCT-Converter

- Heidelberg .vol Reader \
https://github.com/ayl/heyexReader

- LibOCTData \ 
https://github.com/neurodial/LibOctData