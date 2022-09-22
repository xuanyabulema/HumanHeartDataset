# Human Heart Dataset
为了方便网络质量不佳条件下，获取人体心脏数据集

# [Cardiac Atlas Project](http://www.cardiacatlas.org/)

![image-20220922142621049](README/image-20220922142621049.png)

## [Motion Tracking Challenge（运动追踪挑战）](http://www.cardiacatlas.org/challenges/motion-tracking-challenge/)

This is the first Cardiac Motion Analysis Challenge that was held at the 2011 MICCAI workshop entitled “Statistical Atlases and Computational Models of the Heart: Imaging and Modelling Challenges” (STACOM’11). The objective of this challenge is to evaluate the accuracy and reproducibility of different motion analysis algorithms applied to a multimodal cardiac database. The database includes a dataset from a dynamic phantom1 and 15 datasets from healthy volunteers. The data was acquired at the Division of Imaging Sciences and Biomedical Engineering, King’s College London, United Kingdom, and the Department of Internal Medicine II – Cardiology, University of Ulm, Germany.（这是第一届心脏运动分析挑战赛，是在2011年MICCAI研讨会上举行的，题为 "心脏的统计图谱和计算模型。影像和建模的挑战"（STACOM'11）。这项挑战的目的是评估应用于多模态心脏数据库的不同运动分析算法的准确性和可重复性。该数据库包括一个动态模型1的数据集和15个健康志愿者的数据集。这些数据是在英国伦敦国王学院影像科学和生物医学工程系以及德国乌尔姆大学内科二系--心脏科获得的。）

Click [here](http://cilab2.upf.edu/stacom_cesc11/index.php?option=com_content&view=article&id=24&Itemid=22) for more information about the motion tracking challenge.

![image-20220922142726898](README/image-20220922142726898.png)

### Data

The Cardiac Atlas Project hosts the challenge data. Each case consists of cardiac MRI and 3D ultrasound images. The MR acquisition includes: (1) cine SSFP sequences in 2-chamber, 4-chamber, and short-axis views, (2) a whole-heart SSFP sequence gated at end-diastole and end-expiration; and (3) a 4D tMR sequence2. Sequences including three orthogonal tagged directions will be provided together with a fused grid-tagged volume sequence, in VTK and NIFTI formats. The ultrasound acquisition includes a 4D apical volume acquisition. All the datasets will be provided in anonymized DICOM format. （The Cardiac Atlas Project托管了这些挑战数据。每个案例由心脏MRI和三维超声图像组成。磁共振采集包括 (1)两腔、四腔和短轴视图的cine SSFP序列；(2)在舒张末期和呼气末期门控的全心SSFP序列；以及(3)4D tMR序列2。将以VTK和NIFTI格式提供包括三个正交标记方向的序列，以及融合网格标记的体积序列。超声采集包括4D心尖容积采集。所有的数据集都将以匿名的DICOM格式提供。）

The data are provided with open access policy by attributation. This means that if you publish a paper using these data, then you are requested to cite the following citation:（这些数据是根据开放存取政策提供的。这意味着，如果你使用这些数据发表论文，那么你需要引用以下引文）

C. Tobon-Gomez, M. De Craene, K. McLeod, L. Tautz, W. Shi, A. Hennemuth, A. Prakosa, H. Wang, G. Carr-White, S. Kapetanakis, A. Lutz, V. Rasche, T. Schaeffter, C. Butakoff, O. Friman, T. Mansi, M. Sermesant, X. Zhuang, S. Ourselin, H.-O. Peitgen, X. Pennec, R. Razavi, D. Rueckert, A. F. Frangi, and K. S. Rhode, “[Benchmarking framework for myocardial tracking and deformation algorithms: An open access database](http://dx.doi.org/10.1016/j.media.2013.03.008),” *Med Image Anal*, 17(6), 632–648, 2013.

| No.  | File                                                         | Size     |
| ---- | ------------------------------------------------------------ | -------- |
| 1.   | [phantom.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/phantom.zip) | 290.8 MB |
| 2.   | [v1.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/v1.zip) | 396.6 MB |
| 3.   | [v2.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/v2.zip) | 454.7 MB |
| 4.   | [v4.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/v4.zip) | 394.1 MB |
| 5.   | [v5.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/v5.zip) | 390.2 MB |
| 6.   | [v6.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/v6.zip) | 387.1 MB |
| 7.   | [v7.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/v7.zip) | 489.1 MB |
| 8.   | [v8.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/v8.zip) | 472.5 MB |
| 9.   | [v9.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/v9.zip) | 448.8 MB |
| 10.  | [v10.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/v10.zip) | 409.9 MB |
| 11.  | [v11.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/v11.zip) | 491.9 MB |
| 12.  | [v12.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/v12.zip) | 395.8 MB |
| 13.  | [v13.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/v13.zip) | 581.3 MB |
| 14.  | [v14.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/v14.zip) | 461.9 MB |
| 15.  | [v15.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/v15.zip) | 317.2 MB |
| 16.  | [v16.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/v16.zip) | 399.3 MB |

### Ground truth

The ground truth data of this challenge is available: [cMac.zip](http://www.cardiacatlas.org/files/MOTION-STACOM2011/cMAC.zip) (363.5 MB)

### Additional files

- [Readme.pdf](http://www.cardiacatlas.org/wp-content/uploads/sites/2/2015/12/readme.pdf)
- [Short axis cine tag registration sheet data](http://www.cardiacatlas.org/wp-content/uploads/sites/2/2015/12/SA_cine_tag_registration.xls) (XLS)
- [The presentation of motion challenge data](http://www.cardiacatlas.org/files/MOTION-STACOM2011/Motion_Challenge.pptx) (PPTX)

### Contacts

For more inquiries about the data, please contact

- Kawal Rhode (kawal.rhode@kcl.ac.uk)
- Catalina Tobon Gomez (catactg@gmail.com)
- Mathieu de Craene (mathieu.de_craene@philips.com)
