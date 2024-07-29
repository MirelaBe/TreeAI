![image](https://github.com/user-attachments/assets/07acaf6b-405b-444c-b806-2a6c968f16af)



# Data call for tree species annotations and aerial RGB or RGBI imagery (TreeAI) 🌳🌲

Dear forest scientists,

As part of the COST action 3DForEcoTech and COST SNSF project, we aim to establish an international collaboration and create the first database for the detection of individual tree species. We are seeking *i) manual tree species canopy delineations* and *ii) aerial RGBI* (red, green, blue, and near infrared) or *RGB imagery* data for the delineated tree species from around the world. The TreeAI database will serve as the foundation for training a universal deep-learning model for monitoring tree species using fine-grained aerial data. We are also looking for (1) people with experience in deep learning for object detection or instance segmentation; and (2) people who are willing to contribute to the writing of the manuscripts.

**Output:** You will be given the opportunity to contribute as a co-author in a) the publication of a data manuscript (the data provided will only be published with your consent); b) a manuscript investigating different approaches to detecting individual tree species.

* The criteria for data submissions are as follows:
## Minimum data:
1.	RGBI (or RGB) imagery (at ≤ 10 cm, about 3.94 in, spatial resolution) of the site. 
2.	Ground truth tree data (n>100), including two minimum attributes:
- Geolocation of individual tree with manual delineation of the individual tree canopy (strongly preferred) AND/OR coordinates of the point of the individual tree canopy. 
- Individual tree species records. The data might originate from either forests or urban regions. 

### Data format: 
**Ground truth tree data:** For the delineation of the tree crowns a shapefile of the individual trees with the two minimum attributes. For GPS points of the center of the tree species a shapefile or an Excel file with the X and Y coordinates and the tree species. \
**RGBI images:** tiff file. An orthomosaic for the study region and each year is preferred, yet clips of the plots are also acceptable. Please specify the coordinate systems of the data and the acquisition date. \
**COCO format:** A JSON annotation file with the attributes and the image files (e.g., png, jpg, or tiff). 
Data transfer: Please use your preferred data transfer option or let us know your needs.

### Optional data:
We welcome ground truth tree data with more additional attributes, as this would facilitate further evaluations and developments of models in the future. They include, but are not limited to: 
1.	Time of the measurements of ground truth data (multi-temporal data are welcomed).
2.	Tree size: diameter at breast height (cm), tree height (m), and social status i.e. dominant and co-dominant.
3.	 Forest density: trees per unit area and basal area per unit area. 
4.	Individual tree species defoliation and mortality (percentage 0 = no defoliation, 100 = dead).
5.	Environmental and/or topographic measurements: climate, soil, elevation, slope, aspect and so forth.
6.	Stand age, regeneration conditions (i.e., presence or absence, numbers of saplings), and management operations.
For the plots with RGB/RGB-NIR images, the inclusion of high-resolution multispectral/hyperspectral images, high-resolution ground panorama photographs, UAV and/or terrestrial LiDAR point clouds data will be highly valuable. 

### Deadline for submission 31 October 2024
Our aim is to be an open collaborator for individual tree species monitoring researchers worldwide.

Contact **Zhongyu Xia**, zhongyu.xia[at]usys.ethz.ch or Dr. Mirela Beloiu Schwenke, mirela.beloiu[at]usys.ethz.ch, if you are interested in making a data contribution and your data match the criteria outlined or if you want to help with the DL part. All data will be handled safely and securely under a strict data policy and will not be given to third parties without permission. 
We look forward to hearing from you.

Zhongyu Xia, Mirela Beloiu Schwenke, Xinlian Liang, Stefano Puliti, and Martin Mokros \
(Principal Investigators COST SNSF project and 3DForEcoTech)

Example of delineated individual tree species:
![image](https://github.com/user-attachments/assets/8bbf79ca-6949-48dd-a6af-e0bb1b26c033) \
Fig.1 a) Tree species delineation on RGB imagery, the colors show different tree species; b) example of attribute table containing key information of the delineated trees, such as the Latin names of the species, DBH, and height.


