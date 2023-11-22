# WMG_MoSeg

This repository contains the reannotated bounding box files for the KITTI MoSeg dataset, produced by the IV Sensors Group at WMG, The University of Warwick.

Three sets of criteria were defined for the labels:
| Criteria C1 | Criteria C2 | Criteria C3 |
|---|---|---|
|1.1 BB shall be no less than 15 pixels in width or height | 2.1 Object is annotated if human annotator can identify it | 3.1 Incorrect* BBs are removed from original KITTI MoSeg labels|
|1.2 BB shall contain all visible parts of the object, with an error lower or equal to 3 pixels | 2.2 BB shall contain all visible parts of the object, with an error lower or equal to 3 pixels | 3.2 Fully occluded BBs are removed from original KITTI MoSeg labels|
|1.3 BB shall not include any estimated or occluded parts of the object, unless criteria~1.2 is applicable | 2.3 BB shall not include any estimated or occluded parts of the object, unless criteria~2.2 is applicable | |
|1.4 BB must be added when more than 20\% of one side of the object is visible | | |

*Incorrect stands for BBs that clearly do not belong to any target objects

# Citing
Please cite the following article if you are using this dataset.
