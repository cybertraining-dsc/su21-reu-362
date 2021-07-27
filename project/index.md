---
date: 2021-06-16
title: "Automated Detection and Classification of Breast Cancer Subtypes using Machine Learning Algorithms"
linkTitle: AI in Healthcare
tags: ["project", "reu"]
description: "This project provides a means to classify molecular breast cancer subtypes based on gene expression using the approach of machine learning algorithm." 
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

- [ ] quotes need to be used for quotes from a paper
- [ ] if you like to empasize do not use "emphasize" but *emphasize*
- [ ] The relationship of kmeans and your description of AI/ML may not quite fit nicely. I think your focus should be what clustering is and not ML. 

## Abstract

Breast cancer is an heterogenous disease that forms in the cells of the breast and characterized by abnormal growth of the cells[^1]. Early diagnosis and detection of possible cancerous cells in the breast usually increase survival chances and provide a better approach for treatment and management.  Artificial Intelligence involves the simulation of human intelligence in machines and can be used for learning or to solve problems. A major subset of AI is Machine Learning which involves training a piece of software (called model) to makwe useful predictions using dataset. 

In this project, a clustering (kMeans) was used to classify a proteomic dataset into similar clusters using its proteins identifiers. The protein identifiers were associated with the PAM50genes. The project revealed that machine learning algorithm can be used to (WAIT FOR THE RESULT) and suggests the implementation of several algorithms that can be leveraged upon to address healthcare issues like breast cancer and other diseases that are charactized with subtypes. it also suggeests that studying the specific subtypes based on the algorithm has the potential in developing new therapies as well as effective management and treatment plan.


Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

**Keywords:** AI, cancer, breast, algorithms, machine learning, healthcare, subtypes, classification.

## 1. Introduction

Breast cancer is the most common cancer, and also the primary cause of mortality due to cancer in females around the World. It is an heterogenous disease that is characterized by the abnormal growth of cells in the breast region[^1]. Early diagnosis and detection of possible cancerous cells in the breast usually increase survival chances and provide a better approach for treatment and management. Treatment and management often depend on the stage of cancr, the subtype, the tumor size, location and many other factors. Most times, breast cancer is diagnosed and detected through a combination of different approaches such as imaging (e.g. mammogram and ultrasound), physical examination by a radiologist and biopsy. Biopsy is used to confirm the breast cancer symptoms. However, research has shown that radiologists can miss up to 30% of breast cancer tissues during detection[^2]. This gap has brought about the introduction of Computer aided Diagnosis (CAD) systems can help detect abnormalities in an efficient manner. CAD is a technology that includes utilizing the concept of artificial intelligence(AI) and medical image processing to find abnormal signs in the human body[^3].

During the last 20 years, four major intrinsic molecular subtypes for breast cancer- luminal A, luminal B, HER2-enriched and Basal-like have been identified, classified and intensively studied.  Each subtype has its distinct morphologies and clinical treatment. The classification is based on gene expression profiling, specificaly defined by mRNA expression of 50 genes (also known as, PAM50 Genes).The accurate grouping of breast cancer into its relevant subtypes can improve accurate treatment-decision making[^4].

The PAM50 test is now known as he Prosigna Breast Cancer Prognostic Gene Signature Assay
50 (known ad Prosigna) and it analyzes the activity of certain genes in early-stage, hormone-receptor-positive breast cancer[^5]. The classification of the breast cancer subtypes is based on the mRNA expression and the activity of 50 genes and it aims to estimate the rik of distanat reccurrence of breast cancer. Since the assay was based on mRNA expression, it was suggested that a classification based on the final product of mRNA, that is protien, can be implemented to investigate its role in the classifictaion of molecular breast cancer subtypes. As a result, the project was focused on the use of a proteomic dataset which contained published iTRAQ proteome profiling of 77 breast cancer samples and expression values ofr the proteins of each sample. Machine learning algorithm was implemented to design and analyze the data into clusters and determine the relationship of the clusters with each subtype. 

Recently, Artificial intelligence methods, Machine Learning methods, image classifcation have been largely used for breast cancer classification. The advancements in the field of  Machine Learning (ML) have led to more intelligent and self-reliant computer-aided diagnosis (CAD) systems, as the learning ability of ML methods has been constantly improving. A conventional ML method includes enhancement, feature extraction, segmentation, and classification[^6]. 

This project provides an automated classification of breast cancer subtypes using KMeans, a classification algorithm. The scope of the project is to identify the molecular subtypes of breast cancer using the protein  unique identifiers of the breast cancer genes and to investigate its efficacy with the established PAM50 assay.


## 2. Datasets

Datasets are eseential in drawing conclusion. In the diagnosis, detection and classification of breast cancecr, datasets have been essential to draw conclusion to identifiable patterns. They range from imaging datasets to clinical datasets, proteomic datasets etc. Due to new technological and computational advances like NCBI, EEG that record clinical information respectively, large amounts of data have been collected. Medical researchers leverage these datasets to make useful health care decisions that affect a region, gender or the world. The need for accuracy and reproducibilty has led to the use of machine learning as an important tool for drawing conclusions.

Machine Learning involves training a piece of software, also known as model, to idnetify patterns from a dataset and make useful predictions. There are several factors to be considered when using datasets. One of such is data privacy. Recently, measures have been taken to ensure that the privacy of data. Some of these measures include, replacing codes for patients name, using documents and mobile applications that ask for permission from patients before using their data. Recently, the World Health Organization (WHO) made her report on AI and provided priniples that ensure that AI works for all. On of such is that the designer of AI technologies should satisfy regulatory requirements for safety, accuracy and efficacy for well-defined use cases or indications. Measures of quality control in practice and quality improvement in the use of AI must be available[^7]. Building a model using machine learning involves selecting and preparing the appropriate dataset, identifying the accurate machine learnning algorithm to use, training the algorithm on the data to build a model, validating the resulting model's performance on testing data and using the model on a new data[^8].


## 3. Dataset in the Project

KMeans clustering is an unsupervised machine learning algorithm that makes inferences from datasets without referring to a known outcome. It aims to identify underlying patterns in a dataset by looking for a fixed number of clusters , (known as k). The required number of clusters is chosen by the person building the model. KMens was used in this project to classify the protein IDs (or RefSeq_IDs) into clusters. Each cluster was designed to identify related protein IDs.

Three datasets were used for the algorithm. The first and main dataset was a proteomic dataset. It contains published iTRAQ proteome profiling of 77 breast cancer samples generated by the Clinical Proteomic Tumor Analysis Consortium (NCI/NIH). It contains expression values for ~12.000 proteins for each sample, with missing values present when a given protein could not be quantified in a given sample. The variables include the RefSeq_accession_number(also known as RefSeq protein ID), "the gene_symbol" (which is unique to each gene), “the gene_name” (which is the full name of the gene). The remaining columns are the log2 iTRAQ ratios for each of the 77 samples while the last three columns are from healthy individuals.

The second dataset was a PAM50 dataset. It contains the list of genes and proteins used in the PAM50 classification system. The variables include the RefSeqProteinID which matches the Protein IDs in the main proteome dataset. 

The third dataset was a clinical data of about 105 clinical of which the 77 breast cancer samples were extracted from after a `.`. The variables are:
‘Complete TCGA ID', 'Gender', 'Age at Initial Pathologic Diagnosis', 'ER Status', 'PR Status', 'HER2 Final Status', 'Tumor', 'Tumor--T1 Coded', 'Node', 'Node-Coded', 'Metastasis', 'Metastasis-Coded', 'AJCC Stage', 'Converted Stage', 'Survival Data Form', 'Vital Status', 'Days to Date of Last Contact', 'Days to date of Death', 'OS event', 'OS Time', 'PAM50 mRNA', 'SigClust Unsupervised mRNA', 'SigClust Intrinsic mRNA', 'miRNA Clusters', 'methylation Clusters', 'RPPA Clusters', 'CN Clusters', 'Integrated Clusters (with PAM50)', 'Integrated Clusters (no exp)', 'Integrated Clusters (unsup exp).'


## 4. The KMeans Approach

The link to the original study where the samples were used <http://www.nature.com/nature/journal/v534/n7605/full/nature18003.html>
The referred kernals for the code <https://www.kaggle.com/shashwatwork/proteomes-clustering-analysis> and <https://pastebin.com/A0Wj41DP>

- [ ] the code must be put into the github and the link to the github notbook used. In addition you can put in the colab link

- [ ] next sentence unclear because of `.`

During the preparation of the datasets for KMeans analysis, the first and third dataset were merged together, while `.` The variable 'Complete TCGA ID' in the third dataset was found to be the same as the TCGAs in the first dataset. The Complete TCGA ID refers to a breast cancer patient, some patients can be found in both datasets. The TCGA ID in the first dataset was renamed to match with the TCGA of the third dataset, thereby giving the same syntax. The first dataset was also transposed as a row and its gene expression as the columns. These processes were done in order to merge both dataset.

After merging, the "PAM5O RNA" variable from the second dataset was selected to join the merged dataset. This single dataset was named "pam50data". It contained all the variables that were needed for KMeans Analysis which included the 12553 unique genes, the complete TCGA ID of each 80 patient, and their molecular tumor type.

Missing values were imputed using SimpleImputer, the number of clusters that works best were determined. Figures 1 and 2 reveals the result for KMeans clustering using 3 and 5 clusters respectively.

The link to the full code for the algorithm <https://colab.research.google.com/drive/1ETvGu_cMFlATT28LrHdWgRFahBv9gStN#scrollTo=Qu6nLUiudcYa>

- [ ] the code must be put into the github and the link to the github notbook used. In addition you can put in the colab link

## 5. Using Images

- [ ] the section heder `Using Images` makes no sense. IT was used in an example paper weher we expalined how to use images in a paper, are you trying to explain to us how to use images in a paper?

- [ ] Figures must have at leas one sentence in the text explaining what they show while refering to the figure

![Figure 1](https://github.com/cybertraining-dsc/su21-reu-362/blob/main/project/images/new.png)

**Figure 1:** The classification of Breast Cancer Moleecular Subtypes using KMeans Clustering. (k=3)

![Figure 2](https://github.com/cybertraining-dsc/su21-reu-362/blob/main/project/images/k%3D4_image.png)

**Figure 2:** The classification of Breast Cancer Moleecular Subtypes using KMeans Clustering. (k=4)


## 6. Benchmark

- [ ] no expalnation provides
- [ ] no explanation which hardware is used
- [ ] time does not have a unit

| Name        | Status  | Time  |
|-------------|---------|-------|
| parallel 1  |   ok    | 0.647 |
| parallel 3  |   ok    | 0.936 |
| parallel 5  |   ok    | 0.952 |
| parallel 7  |   ok    | 0.943 |
| parallel 9  |   ok    | 1.002 |
| parallel 11 |   ok    | 0.991 |
| parallel 13 |   ok    | 0.958 |
| parallel 15 |   ok    | 1.012 |

**Benchmark:** The table shows the parallel process time take the for loop for n_components. 
 
## 7. Conclusion

- [ ] the comparision of 3 vs 4 needs to be explained in your paper then you can refer to it in the conclusion as you did, what does 3 vs 4 mean.... why did you do 3 vs 4 and not 3 vs 5?

The results of the KMeans analysis indicated that a cluster of 3 is better than a cluster of 4. Future research would be to use other machine learning algorithms, possibly a supervised learning algotithm, to identify the correlation between the clusters and the four molecular subtypes.

## 8. Acknowledgments

- [ ]  This needs to have a full sentence/paragraph

- [ ] Gregor guided me through this process
- [ ] REU Instructors - Carlos Theran, Yohn Jairo, Victor Adankai
- [ ] Jacques Fleischer, David Umanzor

## 9. References

[^1]: Akram, Muhammad et al. "Awareness and current knowledge of breast cancer." Biological research vol. 50,1 33. 2 Oct. 2017, doi:10.1186/s40659-017-0140-9

[^2]: L. Hussain, W. Aziz, S. Saeed, S. Rathore and M. Rafique, "Automated Breast Cancer Detection Using Machine Learning Techniques by Extracting Different Feature Extracting Strategies," 2018 17th IEEE International Conference On Trust, Security And Privacy In Computing And Communications/ 12th IEEE International Conference On Big Data Science And Engineering (TrustCom/BigDataSE), 2018, pp. 327-331, doi: 10.1109/TrustCom/BigDataSE.2018.00057. 

[^3]: Halalli, Bhagirathi et al. "Computer Aided Diagnosis - Medical Image Analysis Techniques." 20 Dec. 2017, doi: 10.5772/intechopen.69792

[^4]: Wallden, Brett et al. "Development and verification of the PAM50-based Prosigna breast cancer gene signature assay." BMC medical genomics vol. 8 54. 22 Aug. 2015, doi:10.1186/s12920-015-0129-6

[^5]: Breast Cancer.org Prosigna Breast Cancer Prognostic Gene Signature Assay. https://www.breastcancer.org/symptoms/testing/types/prosigna

[^6]: Gardezi, Syed Jamal Safdar et al. "Breast Cancer Detection and Diagnosis Using Mammographic Data: Systematic Review." Journal of medical Internet research vol. 21,7 e14464. 26 Jul. 2019, doi:10.2196/14464

[^7]:  WHO, WHO issues first global report on Artificial Intelligence (AI) in health and six guiding principles for its design and use. <https://www.who.int/news/item/28-06-2021-who-issues-first-global-report-on-ai-in-health-and-six-guiding-principles-for-its-design-and-use>

[^8]: Salod, Zakia, and Yashik Singh. "Comparison of the performance of machine learning algorithms in breast cancer screening and detection: A protocol." Journal of public health research vol. 8,3 1677. 4 Dec. 2019, doi:10.4081/jphr.2019.1677Articles

[^9]: Gregor von Laszewski, Cloudmesh StopWatch and Benchmark from the Cloudmesh Common Library, [GitHub] 
      <https://github.com/cloudmesh/cloudmesh-common>
