
# Awesome Advanced Precision Agriculture [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
Advancement of **UAV, deep Learning and cutting edged technologies** and papers in Precision Agriculture. 
 (**contribution are welcome**)

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSSoYg6SncM1t6zA0YPfWG-nB0kS2v1d3BBkA&usqp=CAU)" alt="drawing" width="600"/>

##  

## Table of Contents

<!-- Start TOC (do not remove me) -->
- [Overview of PA](#literature-reviews-for-vi)
- [Recent Advancement in Precision Agriculture ](#multispectral-vegetation-index)
  - [Topic 1. Crop Yield Prediction](#greenness-and-cover)
  - [Topic 2. Crop Counting/ Detections](#other-applications-for-broadband-images)
  - [Topic 3. Classification ](#other-applications-for-broadband-images)
  - [Topic 4. Disease Detection](#other-applications-for-broadband-images)
  - [Topic 5. Weed Detection](#other-applications-for-broadband-images)
- [General Auxiliary Datasets for PA](#hyperspectral-egetation-Index)
- [Community](#community)
  - [Learning Materials](#learning-materials)
- [Software and Library](#Software)
  - [Commercial](#Commercials)
  - [Open](#Open)
 
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
## Recent Advancement in Precision Agriculture 

### Topic 1. Crop Yield Prediction

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

### Topic 4. Disease Detection

### Topic 5. Weed Detection

### Topic 6. Water 




##  General Auxiliary Datasets for PA

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



## Tools, Library 

## Community

### Learning Materials

* [Remote Sensing in Precision Agriculture: An Educational Primer](http://www.amesremote.com/contents.htm) 
*  [LandscapeToolbox](https://wiki.landscapetoolbox.org/doku.php/remote_sensing_methods:home) - The Vegetation/Greenness Indices part provides a detailed descriptions and applications of 9 common indices.


## Software programs
There are currently a large number of software with Vegetation Index tools, and we have a brief summary of them, 
### Commercial

<!-- End Links (do not remove me) -->

 ## Note

This list will be updated in time, and volunteer contributions are welcome. For questions or sharing, please feel free to  [contact us](isxzl39@gmail.com)  or make contributions.

