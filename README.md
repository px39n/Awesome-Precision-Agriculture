
# Awesome Advanced Precision Agriculture [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
Advancement of **UAV, deep Learning and cutting edged technologies** and papers in Precision Agriculture. 
 (**contribution are welcome**)

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSSoYg6SncM1t6zA0YPfWG-nB0kS2v1d3BBkA&usqp=CAU)" alt="drawing" width="600"/>

##  

## Table of Contents

<!-- Start TOC (do not remove me) -->

-   [Overview of PA](#overview-of-pa)
-   [Recent Advanced Plant Phenotyping](#recent-advanced-plant-phenotyping)
    -   [Topic 1. Crop Yield Prediction](#topic-1-crop-yield-prediction)
    -   [Topic 2. Crop Counting/ Detection](#topic-2-crop-counting-detection)
    -   [Topic 3. Classification](#topic-3-classification)
    -   [Topic 4. Tree Health](#topic-4-tree-health)
    -   [Topic 5. Water Stress](#topic-5-water-stress)
    -   [Topic 6. Weed Detection](#topic-6-weed-detection)
-   [General Auxiliary Datasets for PA](#general-auxiliary-datasets-for-pa)
-   [Tools, Library](#tools-library)
-   [Community](#community)
    -   [Learning Materials](#learning-materials)
    -   [Discussion](#discussion)
-   [Software programs](#software-programs)
    -   [Commercial](#commercial)
    -   [Open Source](#open-source)
    -   [Project](#project)
-   [Note](#note)
<!-- End TOC (do not remove me) -->

<!-- Start Links (do not remove me) -->
## Overview of PA
- Definition ([WIKI](https://en.wikipedia.org/wiki/Precision_agriculture#:~:text=Precision%20agriculture%20%28PA%29,%20satellite,intra-field%20variability%20in%20crops.), [ScienceDirect](https://www.sciencedirect.com/topics/agricultural-and-biological-sciences/precision-agriculture))
- Overview of Precision Agriculture ([Cisternas et al.2020](https://www.sciencedirect.com/science/article/abs/pii/S0168169920312357))
- Remote sensing in PA( [Mulla et al.2013](https://www.sciencedirect.com/science/article/abs/pii/S1537511012001419))
- GeoStatistical Applications for PA([Oliver, Margaret A](https://www.springer.com/gp/book/9789048191321))
- UAV images for PA([Radoglou-Grammatikisa et al.2020](https://www.sciencedirect.com/science/article/pii/S138912862030116X))
- Machine Learning for PA([Chlingaryan et al. 2018](https://www.sciencedirect.com/science/article/abs/pii/S0168169917314710))
- Big Data in PA([Wolfert et al.2017](https://www.sciencedirect.com/science/article/pii/S0308521X16303754))
- GPS in PA([Neményi et al.2013](https://www.sciencedirect.com/science/article/abs/pii/S0168169903000103))
- IoT for PA([Khanna et al.2018](https://www.sciencedirect.com/science/article/abs/pii/S0168169918316417))
- Robot System in PA([P.Vasconez et al.2019](https://www.sciencedirect.com/science/article/abs/pii/S0168169903000103))


## Recent Advanced Plant Phenotyping

The implementation of PA could be divided into monitoring and plant management. 
For plant monitoring/phenotyping, the considerable diversity of vegetation indicators can broadly be divided into three categories: compositional, structural, and functional indicators ([Noss, 1990](https://www.sciencedirect.com/science/article/pii/S1470160X15001454#bib0505)). Where two main approaches have been applied to monitoring vegetation condition: site-based assessments and remote sensing.  ([Methodology Reference](https://www.sciencedirect.com/science/article/pii/S1470160X15001454))
The management of plant is based on spatial and temporal scales. 

There have been attempts to use a long list monitoring the plant. However, due to the complex environment and plant characteristics, specific topics need to be discussed separately. 

In this list, **the most popular 20 advancements of topic** are selected. The **link** of topic directly connect to the discussion part.

*Table XX. Topics of Implement of PA*
<table border="0" cellpadding="0" cellspacing="0" width="489" class="xl677465" style="border-collapse:collapse;table-layout:fixed;width:367pt">
 <colgroup><col class="xl677465" width="90" style="mso-width-source:userset;mso-width-alt:
 3056;width:68pt">
 <col class="xl677465" width="92" style="mso-width-source:userset;mso-width-alt:
 3102;width:69pt">
 <col class="xl677465" width="139" style="mso-width-source:userset;mso-width-alt:
 4698;width:104pt">
 <col class="xl677465" width="68" style="width:51pt">
 <col class="xl677465" width="100" style="mso-width-source:userset;mso-width-alt:
 3388;width:75pt">
 </colgroup><tbody><tr height="38" style="height:28.7pt">
  <td height="38" class="xl657465" width="90" style="height:28.7pt;width:68pt">Area</td>
  <td class="xl657465" width="92" style="width:69pt">factors/indicators</td>
  <td class="xl657465" width="139" style="width:104pt">Topic</td>
  <td class="xl657465" width="68" style="width:51pt">Methods</td>
  <td class="xl657465" width="100" style="width:75pt">Reference (Review)</td>
 </tr>
 <tr height="38" style="height:28.7pt">
  <td rowspan="15" height="456" class="xl667465" width="90" style="height:344.35pt;
  width:68pt">Plant Monitoring</td>
  <td rowspan="7" class="xl667465" width="92" style="width:69pt;box-sizing: border-box">compositional</td>
  <td class="xl687465" width="139" style="width:104pt">richness</td>
  <td class="xl677465" width="68" style="width:51pt">UAV, RS, site-based<span style="mso-spacerun:yes">&nbsp;</span></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="19" style="height:14.35pt">
  <td height="19" class="xl687465" width="139" style="height:14.35pt;width:104pt">diversity</td>
  <td class="xl677465" width="68" style="width:51pt"></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="38" style="height:28.7pt">
  <td height="38" class="xl687465" width="139" style="height:28.7pt;width:104pt">vegetation
  classification</td>
  <td class="xl677465" width="68" style="width:51pt">UAV, RS, site-based<span style="mso-spacerun:yes">&nbsp;</span></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="19" style="height:14.35pt">
  <td height="19" class="xl687465" width="139" style="height:14.35pt;width:104pt">threated
  species</td>
  <td class="xl677465" width="68" style="width:51pt"></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="19" style="height:14.35pt">
  <td height="19" class="xl687465" width="139" style="height:14.35pt;width:104pt">disease
  detection</td>
  <td class="xl677465" width="68" style="width:51pt"></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="38" style="height:28.7pt">
  <td height="38" class="xl687465" width="139" style="height:28.7pt;width:104pt">weed
  detection</td>
  <td class="xl677465" width="68" style="width:51pt">UAV, RS, site-based<span style="mso-spacerun:yes">&nbsp;</span></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="38" style="height:28.7pt">
  <td height="38" class="xl697465" width="139" style="height:28.7pt;width:104pt"><a href="https://github.com/px39n/Awesome-Precision-Agriculture#topic-2.-crop-counting-detection">crop
  detection/counting</a></td>
  <td class="xl677465" width="68" style="width:51pt">UAV, RS, site-based<span style="mso-spacerun:yes">&nbsp;</span></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="38" style="height:28.7pt">
  <td rowspan="4" height="95" class="xl667465" width="92" style="height:71.75pt;
  width:69pt;box-sizing: border-box">structural</td>
  <td class="xl687465" width="139" style="width:104pt">spatial-temporal variability</td>
  <td class="xl677465" width="68" style="width:51pt"></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="19" style="height:14.35pt">
  <td height="19" class="xl687465" width="139" style="height:14.35pt;width:104pt">canopy
  cover</td>
  <td class="xl677465" width="68" style="width:51pt"></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="19" style="height:14.35pt">
  <td height="19" class="xl687465" width="139" style="height:14.35pt;width:104pt">plant
  density</td>
  <td class="xl677465" width="68" style="width:51pt"></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="19" style="height:14.35pt">
  <td height="19" class="xl697465" width="139" style="height:14.35pt;width:104pt"><a href="https://github.com/px39n/Awesome-Precision-Agriculture#learning-materials">landscape
  context</a></td>
  <td class="xl677465" width="68" style="width:51pt"></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="19" style="height:14.35pt">
  <td rowspan="4" height="152" class="xl667465" width="92" style="height:114.75pt;
  width:69pt">functional indicators</td>
  <td class="xl687465" width="139" style="width:104pt">disturbance history</td>
  <td class="xl677465" width="68" style="width:51pt"></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="76" style="height:57.35pt">
  <td height="76" class="xl687465" width="139" style="height:57.35pt;width:104pt">water
  stress<span style="mso-spacerun:yes">&nbsp;</span></td>
  <td class="xl677465" width="68" style="width:51pt"></td>
  <td class="xl707465" width="100" style="width:75pt"><a href="https://www.mdpi.com/2072-4292/11/10/1240/htm">Gerhards et al.2019,
  Ihuoma et al.2016</a></td>
 </tr>
 <tr height="38" style="height:28.7pt">
  <td height="38" class="xl697465" width="139" style="height:28.7pt;width:104pt"><a href="https://github.com/px39n/Awesome-Precision-Agriculture#tree-health">forest/tree
  health</a></td>
  <td class="xl677465" width="68" style="width:51pt">UAV, RS, site-based<span style="mso-spacerun:yes">&nbsp;</span></td>
  <td class="xl707465" width="100" style="width:75pt"><a href="https://www.mdpi.com/2072-4292/9/2/129">Lausch et al.2016</a></td>
 </tr>
 <tr height="19" style="height:14.35pt">
  <td height="19" class="xl687465" width="139" style="height:14.35pt;width:104pt">nutrient
  cycling</td>
  <td class="xl677465" width="68" style="width:51pt"></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="19" style="height:14.35pt">
  <td rowspan="7" height="190" class="xl667465" width="90" style="height:143.45pt;
  width:68pt">Plant Management</td>
  <td rowspan="5" class="xl667465" width="92" style="width:69pt">in-situ</td>
  <td class="xl687465" width="139" style="width:104pt">fertilizer</td>
  <td class="xl687465" width="68" style="width:51pt">VRT,GPS</td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="19" style="height:14.35pt">
  <td height="19" class="xl687465" width="139" style="height:14.35pt;width:104pt"><span style="font-variant-ligatures: normal;font-variant-caps: normal;orphans: 2;
  widows: 2;-webkit-text-stroke-width: 0px;text-decoration-style: initial;
  text-decoration-color: initial">soil management</span></td>
  <td class="xl677465" width="68" style="width:51pt">sampling</td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="19" style="height:14.35pt">
  <td height="19" class="xl687465" width="139" style="height:14.35pt;width:104pt">yield
  management</td>
  <td class="xl677465" width="68" style="width:51pt"></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="19" style="height:14.35pt">
  <td height="19" class="xl687465" width="139" style="height:14.35pt;width:104pt">water
  management</td>
  <td class="xl677465" width="68" style="width:51pt"></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="38" style="height:28.7pt">
  <td height="38" class="xl687465" width="139" style="height:28.7pt;width:104pt">environment
  management</td>
  <td class="xl677465" width="68" style="width:51pt"></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="19" style="height:14.35pt">
  <td height="19" class="xl667465" width="92" style="height:14.35pt;width:69pt">risk</td>
  <td class="xl687465" width="139" style="width:104pt">insect<span style="mso-spacerun:yes">&nbsp; </span>weather</td>
  <td class="xl677465" width="68" style="width:51pt"></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <tr height="57" style="height:43.0pt">
  <td height="57" class="xl667465" width="92" style="height:43.0pt;width:69pt">cost</td>
  <td class="xl687465" width="139" style="width:104pt">crop selection,market,loans
  and insurance</td>
  <td class="xl677465" width="68" style="width:51pt"></td>
  <td class="xl677465" width="100" style="width:75pt"></td>
 </tr>
 <!--[if supportMisalignedColumns]-->
 <tr height="0" style="display:none">
  <td width="90" style="width:68pt"></td>
  <td width="92" style="width:69pt"></td>
  <td width="139" style="width:104pt"></td>
  <td width="68" style="width:51pt"></td>
  <td width="100" style="width:75pt"></td>
 </tr>
 <!--[endif]-->
</tbody></table>

### Topic 1. Crop Yield Prediction

- [x] DL for Crop Yield Prediction
- [x] traditional ML for Crop Yield Prediction
- [x]  Datasets, contests
- [ ]  Conceptional diagram of relationship between yield, historical yield, environment. 

*Table 1. ML methods for Crop Yield Prediction*
Year |Method| Keywords | Publication | (Re-)Implementation
|--|--|--|--|--|
2006 | piecewise linear regression | NDVI, Iowa, Soybean, Corn |  Crop yield estimation model for Iowa using remote sensing and surface parameters([Prasad et al.2006](https://www.sciencedirect.com/science/article/abs/pii/S0303243405000553))| ML library |
2015|InnerProductLayer| Agriculture,RS,ML,Feature extraction,Indexes,Data models|Estimating crop yields with deep learning and remotely sensed data[(Kuwata et al.2015)](https://ieeexplore.ieee.org/document/7325900)| Caffe
2016| Random Forest | Wheat, RF | Random Forests for Global and Regional Crop Yield Predictions([Jeong et al.2016](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0156571))| ML library
2017|CNN with Gaussian Process | Gaussian Process, DL| Deep gaussian process for crop yield prediction based on remote sensing data ([You et al.2017](https://scholar.google.com/citations?user=NDbMl7oAAAAJ&hl=en&oi=sra))| Tensorflow 2+([Code](https://github.com/gabrieltseng/pycrop-yield-prediction))
2018|LSTM | LSTM,RNN,soybean,maize | A Scalable Machine Learning System for Pre-Season Agriculture Yield Forecast([Cunha et al.2018](https://ieeexplore.ieee.org/document/8588750))|Keras([Code](https://ieeexplore.ieee.org/mediastore_new/IEEE/content/media/8588285/8588619/8588750/8588750-fig-3-source-large.gif))
2019|LSTM with Gaussian Process| Gaussian Process| Deep Learning For Crop Yield Prediction in Africa([Kaneko et al.2019](https://aiforsocialgood.github.io/icml2019/accepted/track1/pdfs/20_aisg_icml2019.pdf))|Tensorflow([Code](https://github.com/akkaneko/africa-crop-yield))
2019| CNN-RNN | DL, CNN, Feature Selection, RNN|A CNN-RNN Framework for Crop Yield Prediction([Khaki et al.2019](https://arxiv.org/abs/1911.09045))| Python 3.0 Tensorflow 2+ ([Code](https://github.com/saeedkhaki92/Yield-Prediction-DNN))
2019|CNN-LSTM | soybean, yield prediction, county-level, Google Earth Engine, CNN-LSTM| County-Level Soybean Yield Prediction Using Deep CNN-LSTM Model([Sun et al.2019](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6832950/)) | Google Earth Engine
2019|CNN based on Regression | CNN, Regression |  Winter Wheat Yield Estimation from Multitemporal Remote Sensing Images based on Convolutional Neural Networks ([Mu et al.2019](https://www.researchgate.net/publication/336560099_Winter_Wheat_Yield_Estimation_from_Multitemporal_Remote_Sensing_Images_based_on_Convolutional_Neural_Networks))| tensorflow 2.0, gdal([Code](https://github.com/HaoweiGis/Winter-Wheat-Yield-Estimation))
2020|Two-branch DNN |RS,crop,yield prediction,yield detrending|  Winter Wheat Yield Prediction at County Level and Uncertainty Analysis in Main Wheat-Producing Regions of China with Deep Learning Approaches([wang et al.2020](https://www.mdpi.com/2072-4292/12/11/1744/htm)) | No-data
|| Others | Updating, Please make contributions |

*Table 2. Datasets for Crop Yield Prediction*
| Name| Description| Crop| Range |
|--|--|--|--|
|faostat(CSV)| Basic yield according to country in format of CSV | All range | World,1961-2016
| EarthStat| Harvested Area and Yield for 4 Crops of wheat, maize, rice, and soybean.| wheat, maize, rice, and soybean| World(1995，2000,2005) | 
| [GDHY](https://doi.pangaea.de/10.1594/PANGAEA.909132) |The Global Dataset of Historical Yield (GDHYv1.2+v1.3) offers annual time series data of 0.5-degree grid-cell yield estimates of major crops worldwide for the period 1981-2016.| maize, rice, wheat and soybean| World,1981-2016
| Others | Updating, Please make contributions |


**Contest of Crop Yield Prediction**
- [2020 Syngenta Crop Challenge](https://www.syngenta-us.com/newsroom/news_release_detail.aspx?id=211564) (Syngenta, 2020)
Using real-world crop data to develop models that can predict the performance of potential corn products.
- [2018 Syngenta Crop Challenge](https://www.ideaconnection.com/syngenta-crop-challenge/) (Syngenta, 2018)
In the 2018 Syngenta Crop Challenge, Syngenta released several large datasets that recorded the genotype and yield performances of 2,267 maize hybrids planted in 2,247 locations between 2008 and 2016 and asked participants to predict the yield performance in 2017.

### Topic 2. Crop Counting/ Detection

- [x] DL for crop detection
- [x] traditional ML for crop detection
- [x]  Datasets, contests
- [ ]  Overview of Different crops
- [ ]  Difference of counting and detection


*Table1.DL Methods for Crop Counting* 
Year | Method | Keywords| Title | MAE| Re-Implement| 
|--|--|--|--|--|--|
2017|mTASSEL| Land-based,Maize tassels,CNN |TasselNet: counting maize tassels in the wild via local counts regression network([Lu et al.2017](TasselNet:%20counting%20maize%20tassels%20in%20the%20wild%20via%20local%20counts%20regression%20network)) | 6.6 | Pytorch([Code](https://github.com/poppinace))
2018|Fast-RCNN| Land-based,Spike Count | # Detection and analysis of wheat spikes using Convolutional Neural Networks([Hasan et al.2019](https://plantmethods.biomedcentral.com/articles/10.1186/s13007-018-0366-8)) | 5.4 | Caffe([Code](https://github.com/rbgirshick/py-faster-rcnn))
2019|TasselNetv2 |  Land-based,Maize tassels,CNN |TasselNetv2: in-field counting of wheat spikes with context-augmented local regression networks([Xiong et al.2019](https://link.springer.com/article/10.1186/s13007-019-0537-2)) | 5.4 | Pytorch([Code](https://github.com/poppinace))
 2019|Deep Counting| Land-based,superpixels,crop yield|_DeepCount_: In-Field Automatic Quantification of Wheat Spikes Using Simple Linear Iterative Clustering and Deep Convolutional Neural Networks([Sadeghi-Tehran et al., 2019](https://www.frontiersin.org/articles/10.3389/fpls.2019.01176/full)) | XXX | Keras([Code](https://github.com/pouriast/DeepCount))
 2020 |Comparison ||Automatic wheat ear counting using machine learning based on RGB UAV imagery(https://onlinelibrary.wiley.com/doi/full/10.1111/tpj.14799)) 
| Others |  |Updating, Please make contributions

*Table2. ML Methods for Crop Counting* 
| Method | Author  | Height   | Accuracy | Limitation |
|--|--|--|--|--|
| RGB image texture histogram analysis                                                                                                                    | (Cointault et al., 2008)                | 1-2meter | 73%~85%  | Low accuracy                                                                                                                        |
| Laplacian frequency filter, median spatial filter and local peak segmentation                                                                           | (Fernandez-Gallego et al., 2018)        | 1meter   | 90%      | Failed at different stages of plant development. Due to changes in canopy color (yellowing)                                         |
| Use Gabor filter, principal component analysis and k-means clustering                                                                                   | (Alharbi et al., 2018)                  | 2 meter  | 80~90%   | Different stages. Complex environment.                                                                                              |
| Use color, texture and histogram, kernel principal component analysis (KPCA) and dual support vector machine (TWSVM) model for multi-feature extraction | Chengquan Zhou 2018                     | 5.0meter | 82%      | The initial steps require minimal human intervention to generate patches from the original image for different developmental stages |
| Artificial Nerual Network                                                                                                                               | Hao Lu 2017  Pouria Sadeghi-Tehran 2019 | 2.5meter | 85%~95%  | Vehicle-mounted visible camera                                                                                                      
| Others |  |Updating, Please make contributions

*Table3. Datasets  for Crop Counting*
Source | Name| Size|Description|
|--|--|--|--|
Land-based | [Global Wheat Detection Kaggle](https://www.kaggle.com/c/global-wheat-detection/overview)| The data is images of wheat fields, with bounding boxes for each identified wheat head. Not all images include wheat heads / bounding boxes. The images were recorded in many locations around the world. |3,000+1000
Land-based | [SPIKE](https://sourceforge.net/projects/spike-dataset/) | The SPIKE dataset contains images with manually annotated ground truth labels for training and testing convolutional neural networks for spike detection of wheat in the field. | 500+
Land-based | [Maize Tassels Counting Dataset](https://github.com/poppinace/mtc)| -   361 field images collected from 4 experimental fields across China: Zhengzhou, Henan Province, China, Taian, Shandong Province, China, Gucheng, Hebei Province, China, and Jalaid, Sinkiang Autonomous Region, China. | 361

**Contest  for Crop Counting**
- [Global Wheat Detection](https://www.kaggle.com/c/global-wheat-detection) (kaggle, 2020)
In this competition, players detect wheat heads from outdoor images of wheat plants, including wheat datasets from around the globe.


### Topic 3. Classification

### Topic 4. Tree Health 

- [x] Method, Indices, and example applications in PA
- [ ]  Furthermore 

Index: leaf defoliation,leaf chlorosis and other discolouration,dead branches,canopy damage

Methods: close range remote sensing, Lidar, RADAR, Multi-Sensor Approaches, Spectral Laboratory, Plant Phenomics Facilities and Ecotrons, UAV, THermal


*Table x. Recent progress of tree health monitoring in PA*
| Application| Platform| Keywords| Title | 
|--|--|--|--|
| polar vegetation,vigorous| UAV&Satellite | SVM, Hyper-spectrum | Unmanned aircraft system advances health mapping of fragile polar vegetation([Malenovsky et al.2017](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.12833))
| urban tree, discoloration and defoliation | UAV&Lidar|  random forest, Hyper-spectrum,HSI,VI| Urban Tree Health Classification Across Tree Species by Combining Airborne Laser Scanning and Imaging Spectroscopy([Chi et al.2020](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.12833))
| orchard, defoliation | In-situ&UAV&Thermal |  Hyper-spectrum,HSI,VI| Early Detection and Quantification of Almond Red Leaf Blotch Using High-Resolution Hyperspectral and Thermal Imagery([Lopez et al.2016](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.12833))
||Updating||Mapping canopy defoliation by herbivorous insects at the individual tree level using bi-temporal airborne imaging spectroscopy and LiDAR measurements([paper](https://scholar.google.com/scholar_lookup?title=Mapping%20canopy%20defoliation%20by%20herbivorous%20insects%20at%20the%20individual%20tree%20level%20using%20bi-temporal%20airborne%20imaging%20spectroscopy%20and%20LiDAR%20measurements&author=Meng,%20R.&author=Dennison,%20P.E.&author=Zhao,%20F.&author=Shendryk,%20L.&author=Rickert,%20A.&author=Hanavan,%20R.P.&author=Cook,%20B.D.&author=Serbin,%20S.P.&publication_year=2018&journal=Remote%20Sens.%20Environ.&volume=215&pages=170%E2%80%93183&doi=10.1016/j.rse.2018.06.008))
||Updating||Using UAV-based photogrammetry and hyperspectral imaging for mapping bark beetle damage at tree level.([paper](https://www.mdpi.com/2072-4292/7/11/15467))
||Updating||Urban tree health assessment using airborne hyperspectral and LiDAR imagery([paper](https://www.sciencedirect.com/science/article/abs/pii/S0303243418302095))
||Updating||Street tree health from space? An evaluation using WorldView-3 data and the Washington D.C. Street Tree Spatial Database([paper](https://www.sciencedirect.com/science/article/pii/S1618866719306508))

### Topic 5. Water Stress

- [x] Plant based measurement summary
- [x] RS based measurement summary
- [x] Conceptional diagram of relationship between stress, response, VIs
- [ ] ET model
- [ ] Integration of thermal and narrow-band [hyperspectral imagery](http://www-sciencedirect-com-443.ncu1.naihes.cn/topics/agricultural-and-biological-sciences/hyperspectral-imagery "Learn more about Hyperspectral Imagery from ScienceDirect's AI-generated Topic Pages")
- [ ]  Community support like meeting, dataset, workflow...

*Table XX. Plant based method([Ihuoma et al.2016](http://www-sciencedirect-com-443.ncu1.naihes.cn/science/article/pii/S0168169916310766))*
|  Method  | Description  | Adv   | Disadv  |Papers
|--|--|--|--|--|
| Stomatal conductance     | Indirect indicator of plant water stress by measuring the stomata opening                | Good measure of plant water status. Used as benchmark for most research studies                                     | Labour intensive and unsuitable for automation and commercial application. Not very accurate for anisohydric crops |
|  Leaf water potential    | Direct measurement of leaf water content                                                 | Widely accepted reference technique                                                                                 | Slow, destructive, and unsuitable for isohydric crops                                                              |
|  Relative water content  | Direct measurement of leaf water status                                                  | Good indicator plant water status, requiring less sophisticated equipment                                           | Destructive and time consuming                                                                                     |
| Sap flow measurement     | Measures the rate of transpiration through heat pulse                                    | Sensitive to stomatal closure and water deficits. Adapted for automated recording and control of irrigation systems | Needs calibration for each tree and is difficult to replicate. Requires complex instrumentation and expertise      |
|  Stem and fruit diameter | Measures fluctuation in stem and fruit diameters in response to changes in water content | Sensitive measure of plant water stress                                                                             | Not useful for the control of high-frequency irrigation systems                                                    |



In Remote sensing, the monitoring water stress is based on the relationships between primary plant stresses, the induced plant responses, and the multi-/hyperspectrum([Gerhards et al.2019](https://www.mdpi.com/2072-4292/11/10/1240/htm), [Jones et al.2010](https://scholar.google.com/scholar_lookup?title=Remote%20sensing%20of%20vegetation:%20principles,%20techniques,%20and%20applications&author=Jones,%20H.G.&author=Vaughan,%20R.A.&publication_year=2010) ).

*Figure XX. Relationship between stresses, response, RS*
![enter image description here](https://www.mdpi.com/remotesensing/remotesensing-11-01240/article_deploy/html/images/remotesensing-11-01240-g001.png)

*Table X. commonly applied indices and approaches for water-stress detection using the main multi-/hyperspectral remote sensing imaging techniques([Gerhards et al.2019](https://www.mdpi.com/2072-4292/11/10/1240/htm)*)
| Water-Stress Index                            | Plant Response to Water Stress                                     | Formula                                              | Reference | Application 
|-----------------------------------------------|--------------------------------------------------------------------|------------------------------------------------------|-----------|   ---|                                                         
| SDD (Stress Degree Day)                       | Rise in plant temperature                                          | Tc − Tair                                            | updating  |
| CWSI (Crop Water Stress Index)                | Rise in plant temperature                                          | CWSI = (Tc − Twet)/(Tdry − Twet)                     | updating  |
| WDI (Water Deficit Index)                     | Rise in plant temperature                                          | Combination of NDVI (or derivate, e.g., SAVI) and Tc | updating  |
| Spectral emissivity                           | Alteration due to changes in the compositions of leaf constituents | Spectral emissivity (ɛ)                              | updating  |                                                                    |                                                      | updating  |
| PRI (Photochemical Reflectance Index)         | Changes in xanthophyll content                                     | PRI = (R570 − R531)/(R570 + R531)                    | updating  |
| SR (Simple Ratio)                             | Decrease in chlorophyll content                                    | SR = R800/R670                                       | updating  |
| NDVI (Normalized Difference Vegetation Index) | Decrease in chlorophyll content, canopy structural changes         | NDVI = (R800 − R670)/(R800 + R670)                   | updating  |
| WI (Water Index)                              | Decrease in leaf water content                                     | WI = R900/R970                                       | updating  |
| LWI (Leaf Water Index)                        | Decrease in leaf water content                                     | LWI = R1300/R1450                                    | updating  |
| MSI (Moisture Stress Index)                   | Decrease in leaf water content                                     | MSI = R1600/R820                                     | updating  |
| NDWI (Normalized Difference Water Index)      | Decrease in leaf water content                                     | NDWI = (R857 − R1241)/(R857 + R1241)                 | updating  |
| SIF                                           | Changes in photosynthetic efficiency due to decreased CO2 uptake   | SIF685, SIF740, or SIF685/SIF740                     | updating  |




### Topic 6. Weed Detection
[A Crop/Weed Field Image Dataset](https://github.com/ros-agriculture/dataset) - This dataset comprises field images, vegetation segmentation masks and crop/weed plant type annotations. 




##  General Auxiliary Datasets for PA

*Table XX. Auxiliary dataset list* 
Type |Name |Resolution | Description | Range|
|--|--|--|--|--|
|| [worldclim](https://www.worldclim.org/data/index.html) | WorldClim is a database of high spatial resolution global weather and climate data. | World, 1960-2018|
||[CRU TS v4](https://crudata.uea.ac.uk/cru/data/hrg/)|CRU TS is one of the most widely used observed climate datasets and is produced by the UK’s National Centre for Atmospheric Science (NCAS)| World, 1901-2019
||[SRTM](https://www2.jpl.nasa.gov/srtm/) | Elevation |World,1970-Present|
|Soil | [SoilGrids](https://soilgrids.org/)| A system for digital soil mapping based on global compilation of soil profile data and environmental layers | World, Prediction| 30-90m
||[MODIS](https://modis.gsfc.nasa.gov/data/)| The many data products derived from MODIS observations describe features of the land, oceans and the atmosphere that can be used for studies of processes and trends on local to global scales |World,1970-Present|
|Weather|[Daymet](https://daymet.ornl.gov/getdata)| The Daymet dataset provides gridded estimates of daily weather parameters. Seven surface weather parameters are available at a daily time | North American,1980-Present|
Crop |[CropScape and Cropland](https://www.nass.usda.gov/Research_and_Science/Cropland/Release/) |Crop Dataset Layer|US,2008-Present|
Precipitation|[CHIRPS](http://legacy.chg.ucsb.edu/data/chirps/) |Climate Hazards Group InfraRed Precipitation with Station data (CHIRPS) is a 30+ year quasi-global rainfall dataset.| World,1980-Present| 0.05
 Weather |ECMWF | ECMWF produce and disseminate weather forecast data for the National Meteorological and Hydrological Services (NHMSs) of ECMWF Member and Co-operating States and their authorised users| Prediction |
Meteorology| National | [Australia BOM](http://www.bom.gov.au/catalogue/anon-ftp.shtml)


## Tools, Library 

## Community

### Learning Materials

* [Remote Sensing in Precision Agriculture: An Educational Primer](http://www.amesremote.com/contents.htm) 
* [Index Database](https://www.indexdatabase.de/) - An Index-Data-Base (IDB) could be an useful tool to find indices for a required application, adapted to a selected sensor.
* [Awesome GIS](https://github.com/sshuair/awesome-gis) - Awesome GIS is a collection of geospatial related sources, including cartographic tools, geoanalysis tools, developer tools, data, conference & communities, news, massive open online course, some amazing map sites, and more.
* Awesome Agriculture 
### Discussion
* [Open Plant Pathology](https://www.openplantpathology.org/) - Open Plant Pathology is an supports and promotes the spread of all open, transparent and reproducible practices in the field of plant pathology.
* [Farm Hack](https://farmhack.org/tools) - Worldwide community of farmers that build and modify our own tools.
* [ROS Agriculture Community](http://rosagriculture.org/) - Open Source community focusing on using Robot Operating System to empower farmers with robotics tools.
* [OpenFarm](https://github.com/openfarmcc/OpenFarm) - A free and open database for farming and gardening knowledge. You can grow anything
* [Harvest_helper](https://github.com/damwhit/harvest_helper) - Provides growing, harvesting and recipe information for the 45 plants in the database as well as a json api so that people can hopefully use this data to build other apps.


## Software programs
There are currently a large number of software with PA tools, and we have a brief summary of them

### Commercial
| Name | Description | Applications|
|--|--|--|
|ERDAS
|ArcGIS
|ENVI

### Open Source
Library
| Name | Description | Language|
|--|--|--|
|[PlantCV](https://plantcv.readthedocs.io/en/stable/)|PlantCV is composed of modular functions in order to be applicable to a variety of plant types and imaging systems.|Python
| [pyprecag](https://github.com/CSIRO-Precision-Agriculture/pyprecag) | A suite of tools for Precision Agriculture data analysis | Python
[Crop Monitoring](https://github.com/px39n/Precision_Agriculture) | Machine Set of Machine Learning Algorithms developed with the aim of determining health states of different types of crops | Python
 [Open Plant Pathology](https://github.com/openplantpathology/) |A community that values open data and computational tools for advancing epidemiology and pathogen population biology and ecology | Mix



Software
| Name | Description |Platform|
|--|--|--|
[GeoFIS](https://www.geofis.org/en/) | GeoFIS is a free and open source software platform for high spatial resolution data processing with a decision support perspective.| Win, Linux,Docker
 [Sen2Agri-System](https://github.com/Sen2Agri/Sen2Agri-System) | Sentinel-2 for Agriculture (Sen2Agri) is a software system processing high resolution satellite images for agricultural purposes funded by ESA (European Space Agency). Please register on the Sen2Agri webpage for Sen2Agri system updates and information. | Service

### Project
[Precision Farming](https://github.com/princegyan/Precision-Farming) - It employs the use of IOT to monitor, store and analyse soil conditions in a green house to enhance crop production. The microcontroller used is the raspberry pi.
[Plant Phenotyping](https://github.com/ricber/Plant-Phenotyper) - A modular software architecture for Automatic Plant Phenotyping
[Deep Learning for Biologists with Keras](https://github.com/totti0223/deep_learning_for_biologists_with_keras#deep-learning-for-biologists-with-keras) - Tutorials for deep learning based analysis (mainly) on biological relavent themes.

<!-- End Links (do not remove me) -->
 ## Note

This list will be updated in time, and volunteer contributions are welcome. For questions or sharing, please feel free to  [contact us](isxzl39@gmail.com)  or make contributions.
