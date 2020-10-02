# OCT-seg-papers
Personal paper/code/dataset list on OCT segmentation

## Background
- 2018 Prevalences of segmentation errors and motion artifacts in OCT-angiography differ among retinal diseases \
https://link.springer.com/article/10.1007/s00417-018-4053-2 

- 2013 A Review of Algorithms for Segmentation of Optical Coherence Tomography from Retina \
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3785070/

## Deep Learning

- 2017 ReLayNet: retinal layer and fluid segmentation of macular optical coherence tomography using fully convolutional networks \
https://arxiv.org/abs/1704.02161 \
code: https://github.com/ai-med/relaynet_pytorch

- 2018 (Google DeepMind) Clinically applicable deep learning for diagnosis and referral in retinal disease \
https://rdcu.be/4sNU 

- 2019 Fully Convolutional Boundary Regression for Retina OCT Segmentation \
https://link.springer.com/chapter/10.1007/978-3-030-32239-7_14 \
preprocessing code: https://github.com/heyufan1995/oct_preprocess \
2D Unet, column wise softmax for boundary

- 2020 (Google DeepMind) Predicting conversion to wet age-related macular degeneration using deep learning \
https://rdcu.be/b4fgc 

## Conventional

- 2014 Probabilistic intra-retinal layer segmentation in 3-D OCT images using global shape regularization \
http://www.sciencedirect.com/science/article/pii/S1361841514000449. \
code: https://github.com/FabianRathke/octSegmentation \
2D and 3D, GR

- 2018 A Supervised Joint Multi-layer Segmentation Framework for Retinal Optical Coherence Tomography Images using Conditional Random Field \
https://www.sciencedirect.com/science/article/pii/S0169260717314645 \
code: https://github.com/arunava555/OCT-layer-segmentation \
CRF, code in Matlab

- Segmentation and analysis of retinal layers from individual OCT b-scans \
code: https://github.com/sarastokes/OCT-tools 

## Dataset
- Diabetic macular edema dataset \
http://people.duke.edu/~sf59/Chiu_BOE_2014_dataset.htm \
preprocessing code: https://github.com/heyufan1995/oct_preprocess

- Healthy and Multiple Sclerosis dataset \
http://iacl.ece.jhu.edu/index.php?title=Resources

- Retinal-OCT-Images \
https://github.com/lidaboo/Retinal-OCT-Images
