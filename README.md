## Multiclass Semantic Segmentation of Urban Scenery: Can CBAM or Attention U-Net Unmask What Classical U-Net Cannot?

## Abstract
Understanding urban scenery is critical in a number of areas, the most common of which is autonomous driving. Semantic segmentation specifically is the appropriate
task in achieving this purpose as it would allow the conversion of urban scenes into specific regions, each belonging to a particular class (pedestrian, vehicle, traffic
sign, etc.). U-Net is a convolutional network that was proposed for biomedical image segmentation. The initial idea behind this paper was to conduct semantic
segmentation on the Cityscapes dataset using the classical U-Net, and attempt to ameliorate its performance either by incorporating a Convolutional Block Attention
Module (CBAM) or implementing the Attention U-Net architecture, proposed in Learning Where to Look for the Pancreas. The experiments show that the
three aforementioned network variations do not result in a significant performance improvement. This paper details the methodology and results supporting this
statement.

## Content
- Report
- 5-minute video presentation link: https://youtu.be/VWwxcjVEtTw
- Notebook 1: Preprocessing
- Notebook 2: Definition and trainining/validation of U-Net
- Notebook 3: Definition and trainining/validation of UNet-CBAM
- Notebook 4: Definition and trainining/validation of Attention U-Net
