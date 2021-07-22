---
date: 2021-06-16
title: "Automated Detection and Classification of Breast Cancer Subtypes using Machine Learning Algorithms"
linkTitle: AI in Healthcare
tags: ["project", "reu"]
description: "This project provides a means to detect breast cancer subtypes from a proteomic dataset using three different machine learning algorithms and aims to determine the accuracy of each model."
author: Kehinde, Ezekiel
github_url: https://github.com/cybertraining-dsc/su21-reu-362/edit/main/project/index.md
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
---

[![Check Report](https://github.com/cybertraining-dsc/hid-example/workflows/Check%20Report/badge.svg)](https://github.com/cybertraining-dsc/su21-reu-362/actions)
[![Status](https://github.com/cybertraining-dsc/hid-example/workflows/Status/badge.svg)](https://github.com/cybertraining-dsc/su21-reu-362/actions)
Status: draft, Type: Project

Kehinde Ezekiel, [su21-reu-362](https://github.com/cybertraining-dsc/su21-reu-362), [Edit](https://github.com/cybertraining-dsc/su21-reu-
362/blob/main/project/index.md)

{{% pageinfo %}}

## Abstract

Breast cancer is the most common cancer, and also the primary cause of mortality due to cancer in females around the World[^1]. It is an heterogenous disease that is characterized by the abnormal growth of cells in the breast region. Early diagnosis and detection of possible cancerous cells in the breast usually increase survival chances and provide a better approach for treatment and management. Most times, breast cancer is diagnosed and detected through a combination of different approaches such as imaging (e.g. mammogram and ultrasound), physical examination by a radiologist and biopsy. Biopsy is used to confirm the breast cancer symptoms. However, research has shown that radiologists can miss up to 30% of breast cancer tissues[^2]. Hence, the introduction of Computer aided Diagnosis (CAD) systems can help radiologists to detect abnormailities in an efficient manner. CAD is a technology that includes concept of artificial intelligence(AI), medical image processing to find abnormal signs in the human body[^3]. 

Artificial Intelligence involves the simulation of human intelligence in machines and can be used for learning or to solve problems. A major subset of AI is Machine Learning which involves. In this project, a machine learning algotithm (kMeans) was used to classify a proteomic dataset into similar clusters using its proteins identifiers. The protein identifiers were associated with the PAM50genes. The project revealed that machine learning algorithm can be used to (WAIT FOR THE RESULT) and suggests the implementation of several algorithms that can be leveraged upon to address healthcare issues like breast cancer and other diseases (QUALIFY THE DISEASE)


Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

**Keywords:** AI, cancer, breast, algorithms, machine learning, healthcare, subtypes, classification.

## 1. Introduction

Breast cancer is the most common cancer, and also the primary cause of mortality due to cancer in females around the World[^1]. It is an heterogenous disease that is characterized by the abnormal growth of cells in the breast region. Early diagnosis and detection of possible cancerous cells in the breast usually increase survival chances and provide a better approach for treatment and management. Most times, breast cancer is diagnosed and detected through a combination of different approaches such as imaging (e.g. mammogram and ultrasound), physical examination by a radiologist and biopsy. Biopsy is used to confirm the breast cancer symptoms. However, research has shown that radiologists can miss up to 30% of breast cancer tissues[^2]. Hence, the introduction of Computer aided Diagnosis (CAD) systems can help radiologists to detect abnormailities in an efficient manner. CAD is a technology that includes concept of artificial intelligence(AI), medical image processing to find abnormal signs in the human body[^3]. Machine Learning and AI allows for the implementation of several algorithms that can be leveraged upon to address health issues like breast cancer. 

During the last 20 years, five (5) intrinsic molecular subtypes for breast cancer- luminal A, luminal B, HER2-enriched, Basal-like and Claudin-low have been identified, classified and intensively studied. This classification is based on gene expression profiling, specificaly defined by mRNA expression of 50 genes (also known as, PAM50 Genes). Each subtype has its distinct morphologies and clinical treatment. The accurate grouping of breast cancer into its relevant subtypes can improve accurate treatment-decision making. Machine Learning Algorithms is a model that can be used to achieve the classification of the grouping categories subtypes. 
 hence, there have been more research and advance to ensure quicker and more accurate prediction and classification. Artificial intelligence (AI), machine learning are one of such approach. They allow for more accurate classification, detection and prediction of breast cancer subtypes.

Proteins are mRNA final product. The basis of classification of the subtypes based on the PAM50 genes using mRNA expression may not be as using protein, mRNA final product. With the knowledege of advancing technologies and the basis of the PAM50 gene classification, this project focused on the use of a proteomic dataset which contained published iTRAQ proteome profiling of 77 breast cancer samples and expression values ofr the proteins of each sample. Machine learning algorithm was implemented to design and analyze the data into clusters and

This project provides an automated detection of breast cancer subtypes using KMeans. The project also aims to identify the accuracy of the models in the classification and detection of breast cancer subtypes. The project aim to idnetify unique protein identifiers that may be unique or similar for a particular suubtype


## 2. Datasets

Datasets are eseential in drawing conclusion. In the diagnosis, detection and classification of breast cancecr, datasets have been essential to draw conclusion to identifiable patterns. They range from imaging datasets to clinical datasets, proteomic datasets etc. Many of these datasets.

Due to new technological and computational advances like NCBI, EEG that record clinical information respectively, large amounts of data have been collected. These data vary . Medical researchers leverage these datasets to make useful health care decisions that affect a region, gender or the world. The need for accuracy and reproducibilty has led to the use of machine learning as an important tool for drawing conclusions.

Machine Learning involves training a piece of software, also known as model, to idnetify patterns from a dataset and make useful predictions. There are several factors to be considered when using datasets. One of such isa is data privacy. Recently, measures have been taken to ensure that the privacy of data. Some of these measures include, replacing codes for patients name, using documents and mobile applications that ask for permission from patients before using their data. Recently, the World Health Organization (WHO) made her report on AI and provided priniples that ensure that AI works for all. On of such is that the designer of AI technologies should satisfy regulatory requirements for safety, accuracy and efficacy for well-defined use cases or indications. Measures of quality control in practice and quality improvement in the use of AI must be available[^4].

 Building a model using machine learning involves selecting and preparing the appropriate dataset, identifying the accurate machine learnning algorithm to use, training the algorithm on the data to build a model, validating the resulting model's performance on testing data and using the model on a new data[^5].


## 3. Dataset in the Project

The dataset that is used in this project is a proteomic dataset. It contains published iTRAQ proteome profiling of 77 breast cancer samples generated by the Clinical Proteomic Tumor Analysis Consortium (NCI/NIH). It contains expression values for ~12.000 proteins for each sample, with missing values present when a given protein could not be quantified in a given sample. Proteomics is the study of proteomes(the entire complement of proteins that is or can be expressed by a cell, tissue, or an organism) and their functions. Proteome is the main functional unit of cells and it is translated from RNA molecules. The RNA molecules are transcribed from the DNA in the genes.

Consequently, the five breast cancer subtypes are classified based on their gene expression. The method that was used to classify them was the PAM50,  a 50-gene signature. This project is focused on classifying the subtypes using nachine learning algorithm using the knowledge that a relationship exist between gene and protein. The machine learning algorithms that were used in this project are K-Means, Support Vector Machine(SVM) and Linear Regresssion. 

KMeans is an unsupervised learning algorithm that describe relationships in a data. In this proteome dataset, it aims to look for similarities and patterns in the data and use it to classify the data. Linear Regresssion is a supervised learrning algorithm that models the relatonship between variables in the dataset while Support Vector Machine(SVM) is supervised learrning algorithm that classifies the dataset.

The result of the pprogram is then compared with a clinical dataset from which the 77 breast cancer samples used in the dataset were extracted from. The extent of similarity will identify which algorithm best classifies the dataset into the five breast cancer subtypes.


## 4. Example of an AI algorithm in Healthcare

- [ ] Identify the concrete datasets that will be used.
- [ ] Identify the concrete algorithm that is used to analyze the datasets
- [ ] Write the program
- [ ] Verify that it works


## 5. Using Images

![Figure 1](https://github.com/kehinde-ezekiel/su21-reu-362/blob/main/project/images/chart_image.jpg)

**Figure 1:** Pair plots of Diagnostic Features


## 6. Benchmark

Your project must include a benchmark. The easiest is to use cloudmesh-common [^8]
 
## 7. Conclusion

A convincing but not fake conclusion should summarize what the conclusion of the project is.

## 8. Acknowledgments

- [ ] Gregor guided me through this process
- [ ] Please add acknowledgments to all that contributed or helped on this project.

## 9. References

[^1]: Akram, Muhammad et al. "Awareness and current knowledge of breast cancer." Biological research vol. 50,1 33. 2 Oct. 2017, doi:10.1186/s40659-017-0140-9

[^2]: National Breast Cancer Foundtaion.<https://www.cancer.org/cancer/breast-cancer/screening-tests-and-early-detection.html>

[^3]: L. Hussain, W. Aziz, S. Saeed, S. Rathore and M. Rafique, "Automated Breast Cancer Detection Using Machine Learning Techniques by Extracting Different Feature Extracting Strategies," 2018 17th IEEE International Conference On Trust, Security And Privacy In Computing And Communications/ 12th IEEE International Conference On Big Data Science And Engineering (TrustCom/BigDataSE), 2018, pp. 327-331, doi: 10.1109/TrustCom/BigDataSE.2018.00057. 

[^4]: Sørlie, T et al. "Gene expression patterns of breast carcinomas distinguish tumor subclasses with clinical implications." Proceedings of the National Academy of Sciences of the United States of America vol. 98,19 (2001): 10869-74. doi:10.1073/pnas.191367098

[^5]: Effect of artificial intelligence-based triaging of breast cancer screening mammograms on cancer detection and radiologist workload: a retrospective simulation study Dembrower, Karin et al. The Lancet Digital Health, Volume 2, Issue 9, e468 - e474

[^6]: Halalli, Bhagirathi et al. "Computer Aided Diagnosis - Medical Image Analysis Techniques." 20 Dec. 2017, doi: 10.5772/intechopen.69792

[^7]: Salod, Zakia, and Yashik Singh. "Comparison of the performance of machine learning algorithms in breast cancer screening and detection: A protocol." Journal of public health research vol. 8,3 1677. 4 Dec. 2019, doi:10.4081/jphr.2019.1677

[^8]: Gregor von Laszewski, Cloudmesh StopWatch and Benchmark from the Cloudmesh Common Library, [GitHub] 
      <https://github.com/cloudmesh/cloudmesh-common>
