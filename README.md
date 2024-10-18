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

### Expertise with DL: Data Science Competition 
We will organize a data science competition for tree species identification between February and June 2025. Please express your interest in participating in the data science competition by October 30 and we will send you more information.
### Countries with open RGBI imagery: 
We have compiled a list of countries and regions that provide high-resolution images for free (Fig. 1). This will help us to apply the model to larger areas and assess the distribution of tree species and changes in species composition over time. If you know of regions where high-resolution images are available, please let us know.

### Deadline for submission 30 October 2024
Our aim is to be an open collaborator for individual tree species monitoring researchers worldwide.

Contact **Zhongyu Xia**, zhongyu.xia[at]usys.ethz.ch or Dr. Mirela Beloiu Schwenke, mirela.beloiu[at]usys.ethz.ch, if you are interested in making a data contribution and your data match the criteria outlined or if you want to help with the DL part. All data will be handled safely and securely under a strict data policy and will not be given to third parties without permission. 
We look forward to hearing from you.

Mirela Beloiu Schwenke, Zhongyu Xia, Verena Griess, Xinlian Liang, Stefano Puliti, and Martin Mokros \
(Principal Investigators COST SNSF project and 3DForEcoTech) \
https://3dforecotech.eu/activities/tree-species-annotations-and-aerial-rgb-or-rgbi-imagery/ 

Example of delineated individual tree species:
![image](https://github.com/user-attachments/assets/5e1ac390-f4ba-4122-afc9-0faa5309432a)  \
Fig.1 a) Tree species delineation on RGB imagery, the colors show different tree species; b) example of attribute table containing key information of the delineated trees, such as the Latin names of the species, DBH, and height.

![image](https://github.com/user-attachments/assets/62049778-000c-4069-81f2-afe1c58b853b)
Fig.2 a) Regions with tree species delineation and the countries with high-resolution RGB/I imagery.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Mandarin translation:

尊敬的广大林业研究者，
作为COST action 3DForEcoTech和COST SNSF项目 的一员，我们正在发起一项邀请以呼吁国际间的数据合作，并建立一个单棵树种识别（individual tree species identification）的数据库（TreeAI）。我们正在寻找来自全球的符合如下特征的数据：1）包含单棵树树种信息和人工划分单棵树冠范围的空间数据文件；2）相对应的高分辨率遥感影像（RGB或RGBI图像）。TreeAI 数据库将作为利用高分辨率航空数据识别和监测树种的深度学习模型的训练基础。除数据之外，我们同时也期待学术上的合作伙伴：1）有基于深度学习的对象检测或实例分割相关经验的学者；2）有意愿参与撰写出版物的学者。
您将有机会参与出版数据报告（您的数据只有在您同意的情况下才会发表）以及相关的科研论文。

数据要求至少符合以下两点：
1.	RGB或RGBI航空遥感影像（地面采样距离GSD小于或等于10 cm）。
2.	地面实测树种数据（大于100棵），数据至少包含以下两个属性：
a.	单棵树的空间位置信息：人工划分的单棵树树冠范围，若缺失单棵树树冠范围，代表树冠中心点的坐标也可。
b.	与树冠/点相对应的树种拉丁名。
数据格式：
1.	RGB或RGBI图像：研究区域已被拼接和校正的正射影像图，栅格文件（.tiff）。请注明数据的坐标系和采集日期。
2.	地面实测树种数据：属性列表（至少）包含上述两种属性的空间数据文件（shapefile），JSON格式数据，或Excel工作表格。

其它可包含的数据：
我们欢迎具有更多附加属性的地面实况树数据，因为这将有助于今后对模型进行进一步评估和开发。这些属性包括但不限于
1.	多时态数据。
2.	树木测量数据：胸高直径（cm），树高（m），优势树。
3.	森林密度（株/单位面积，或基面积/单位面积）
4.	树木健康状况，衰退或死亡情况，可用百分率表示（0 = 没有衰退，100 = 死亡）。
5.	其它立地信息：气候，土壤，海拔，坡度等。
6.	林龄，再生情况（林下有幼苗或没有），森林经营活动等。
7.	对于已有RGB/RGB-NIR 图像的地块，其它遥感数据如高分辨率多光谱/高光谱图像、高分辨率地面全景照片、无人机和/或地面 LiDAR 点云数据将非常有价值。

此数据合作邀请的截止日期为2024年10月31日。
若您有意参与，或有其它问题，敬请联系Zhongyu Xia（zhongyu.xia@usys.ethz.ch）和Dr. Mirela Beloiu Schwenke（mirela.beloiu[at]usys.ethz.ch）
我们将根据严格的数据政策安全可靠地处理所有数据，未经许可不会将数据提供给第三方。
我们期待您的来信。 

