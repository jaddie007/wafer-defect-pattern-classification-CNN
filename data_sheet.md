# Datasheet 


## Motivation

This data is created for scientists / engineers to study the wafer defect patterns. To build an automated image classification system to accurately classify the wafer defect type

The data is provided by J. Wang, C. Xu, Z. Yang, J. Zhang and X. Li on behalf of Institute of Intelligent Manufacturing, Donghua University, China. The data was published on Kaggle (https://www.kaggle.com/datasets/co1d7era/mixedtype-wafer-defect-datasets)
 
## Composition

The instances that comprise the dataset are images with the size of 52 x 52, and there are 38015 instances in the dataset. There are no missing or NaN data. This dataset is not considered confidential as it is published online on Kaggle by the authors.

## Collection process

The data consists of 38015 wafer defect maps (images) that was collected by measuring the electrical resistance spatial distribution across the whole wafer.
The sampling strategy of acquiring each point is that by fixing an spatial interval, measuring the electrical resistance of the whole wafer.

## Preprocessing/cleaning/labelling

There's labeling of each map to different types of wafer defects in the dataset. Also the authors have processed the labelled data and turned them into one-hot coding with 8 digits. By different combinations of the 8 digits, they have created 38 different labels corresponding to 38 different types of wafer defects. 

There are no un-processed raw data but only the pre-labelled data

 
## Uses

This data set is originally for scientists / engineers to investigate the defect patterns classification problem. By building the appriopriate model to help detecting the defect accurately. 

But this dataset can also be used for other purposes. For example, by building unsupervised learning algorithm, like segmentation, we can use the accurate model to understand the fundamentals of each defect pattern and finding correlations between each defect patterns, which might give insignt into the reasons for causing particular type of defect.


## Distribution

The data is made public by the authors and they have published on Kaggle (https://www.kaggle.com/datasets/co1d7era/mixedtype-wafer-defect-datasets)

There's no copyright or IP licences claims on the source page.

## Maintenance

The authors who published the data.

