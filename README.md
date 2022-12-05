# AICDA - Artificial Intelligence for Cervical Disc Anthroplasty

Segmentation and identification of the vertebrae is often a prerequisite for automatic analysis of the spine, such as detection of vertebral fractures, assessment of spinal deformities, or computer-assisted surgical interventions. Automatic spine analysis can be performed with a large variety of tomographic scans, including dedicated spine scans but also scans of the neck, chest or abdomen that incidentally cover part of the spine. A generic vertebra segmentation algorithm therefore needs to be robust with respect to different image resolutions and different coverages of the spine. This especially means that no assumptions should be made about the number of visible vertebrae and their anatomical identity, i.e., to which section of the spine they belong. Vertebra segmentation is therefore essentially an instance segmentation problem with an a priori unknown number of instances (i.e. vertebrae). However, in contrast to generic instance segmentation the individual instances are not independent of each other. The instances are known to be located in close proximity to each other in the image, forming together the vertebral column. We develoed a technique for segmentation that explicitly incorporates this prior knowledge to locate instances, but that makes no further assumptions.

![Cervical Spine](https://github.com/Minhah-Saleem/Cervical-Spine-Segmentation/blob/main/cervical.png)

## Dataset:
VerSe is a large scale, multi-detector, multi-site, CT spine dataset consisting of 374 scans from 355 patients. The challenge was held in two iterations in conjunction with MICCAI 2019 and 2020. The tasks evaluated for include: vertebral labelling and segmentation.
[Link to dataset](https://paperswithcode.com/dataset/verse-1)

## Preprocessing:
Resampling to 1mm
Changing Orientation


## Results:

Achieved 92% dice score.
