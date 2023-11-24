# CSCI-594-FALL23
There are two models: the baseline model and the model we are proposing. Additionally, experiments with the models were done to generate Monet-like images and Bob Ross-like images. 

Links to the dataset:
1. [Link to the Kaggle Competition with the Monet Dataset](https://www.kaggle.com/competitions/gan-getting-started)
2. [Link to the Bob Ross dataset](https://www.kaggle.com/datasets/residentmario/segmented-bob-ross-images)

Links to annotated custom datasets:
1. [Link to the Segmented Monet Dataset](https://www.kaggle.com/datasets/abatyr/segmented-monet-pictures)
2. [Link to the Segmented Photos (using Segformer, ADE20K)](https://www.kaggle.com/datasets/abatyr/segmented-photos-segformer-ade20k)

Files are:
- Baselines:
    1. [Baseline_monet_style](Baseline_monet_style.ipynb) => Implementation of the Baseline model to generate Monet-like images
    2. [Baseline-bob-ross_style](Baseline-bob-ross-style.ipynb) => Implementation of the Baseline model to generate Bob Ross-like images
- Our implementation:
    1. [SegCycleGAN_monet_style](SegCycleGAN_monet_style.ipynb) => Implementation of the CycleGAN with the segmented features to generate Monet-like images
    2. [SegCycleGAN-bob-ross_style](SegCycleGAN-bob-ross_style.ipynb) => Implementation of the CycleGAN with the segmented features to generate Bob Ross-like images
