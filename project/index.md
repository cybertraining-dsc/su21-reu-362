---
date: 2021-06-16
title: "Automated Detection and Classification of Breast Cancer Subtypes using Machine Learning Algorithms"
linkTitle: AI in Healthcare
tags: ["project", "reu"]
description: "This project provides a means to detect breast cancer subtypes using three different machine learning algorithms and aims to determine the accuracy of each model."
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

Breast cancer is a form of disease that is caused by the growth of cells in the breast out of proportion. The major forms by which breast cancer can be detected are through Artificial Intelligence(AI). AI is a concept or technology that is fast-growing in the medical and healthcare field. AI has provided opportunities for the healthcare ecosystem to make quick analysis, observe trends and introduce technological solutions to healthcare problems like diseases. In  previous  studies, researchers  extracted  different  features  from  colon  biopsy  images  to  detect  the  cancer  and  distinguish  the  normal  and  malignant  subjects. 

Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

**Keywords:** AI, cancer, breast, algorithms, machine learning, healthcare, privacy.

## 1. Introduction

Breast cancer is the most common cancer, and also the primary cause of mortality due to cancer in female around the World[^1]. Breast cancer is the abnormal growth of cells in the breast region and some are invasive while some are non-invasive. Early diagnosis and detection of possible cancerous cells in the breast can increase survival chances and provide a chance for better treatment and management. The breast cancer is diagnosed and detected through a combination of different approaches such as imaging, physical examination by a radiologist and biopsy.(REFERNECE). Imaging technology employs the use of Artificial Intelligence(AI) and it consists of mammography and ultrasound. The results of the imaging as deciphered by a radiologist determines the next step. If abnormal cells are detected, a physical examination is conducted to decipher the kind of appearance - normal,benign or nonspecific. 

Biopsy is used to confirm the breast cancer symptoms. However, research has shown that radiologists can miss up to 30% of breast cancer tissues[^2]. Hence, the introduuction of Computer aided Diagnosis (CAD) systems can help radiologists to detect abnormailities in an efficient manner. CAD is a technology that includes concept of artificial intelligence(AI), medical image processing to find abnormal signs in the human body[^3]. Machine Learning and AI allows for the implementation of several algorithms that can be leveraged upon to address health issues like breast cancer. 

Breast cancer consists of multiple subtypes,identified based on their differences in gene expression. They come with distinct morphologies and clinical outcomes. They are luminal A, luminal B, HER2 over-expression, basal and normal-like tumors[^4]. Hence, the accurate grouping of breast cancer into its relevant subtypes can improve accurate treatment-decision making. Machine Learning Algorithms is a model that can be used to achieve the classification of the grouping categories subtypes. 

This project provides an automated detection of breast cancer subtypes using Linear Regression, Lasso Regression and Data Visualization. Linear regression is an algorithm  . The project also aims to identify the accuracy of the models in the classification and detection of breast cancer subtypes


## 2. Datasets

- [ ] Finding datasets in breast cancer.
- [ ] Research data privacy in the healthcare
- [ ] Can any of the datasets be used in AI?
- [ ] What are the challenges with Healthcare dataset? Privacy, Inconsistent Dataset
- [ ] Datasets can be huge and GitHub has limited space. Only very small datasets should be stored in GitHub.
      However, if the data is publicly available you program must contain a download function instead that you customize.
      Write it using pythons `request`. You will get point deductions if you check-in data sets that are large and do not use
      the download function.

## 3. Using Images

![Figure 1](https://github.com/kehinde-ezekiel/su21-reu-362/blob/main/project/images/chart_image.jpg)

**Figure 1:** Pair plots of Diagnostic Features

## 4. Example of an AI algorithm in Healthcare

- [ ] Identify the concrete datasets that will be used.
- [ ] Identify the concrete algorithm that is used to analyze the datasets
- [ ] Write the program
- [ ] Verify that it works

## 5. Benchmark

Your project must include a benchmark. The easiest is to use cloudmesh-common [^2]
 
## 6. Conclusion

A convincing but not fake conclusion should summarize what the conclusion of the project is.

## 7. Acknowledgments

- [ ] Gregor guided me through this process
- [ ] Please add acknowledgments to all that contributed or helped on this project.

## 8. References

[^1]: Akram, Muhammad et al. "Awareness and current knowledge of breast cancer." Biological research vol. 50,1 33. 2 Oct. 2017, doi:10.1186/s40659-017-0140-9

[^2]: National Breast Cancer Foundtaion.<https://www.cancer.org/cancer/breast-cancer/screening-tests-and-early-detection.html>

[^3]: L. Hussain, W. Aziz, S. Saeed, S. Rathore and M. Rafique, "Automated Breast Cancer Detection Using Machine Learning Techniques by Extracting Different Feature Extracting Strategies," 2018 17th IEEE International Conference On Trust, Security And Privacy In Computing And Communications/ 12th IEEE International Conference On Big Data Science And Engineering (TrustCom/BigDataSE), 2018, pp. 327-331, doi: 10.1109/TrustCom/BigDataSE.2018.00057. 

[^4]: Sørlie, T et al. "Gene expression patterns of breast carcinomas distinguish tumor subclasses with clinical implications." Proceedings of the National Academy of Sciences of the United States of America vol. 98,19 (2001): 10869-74. doi:10.1073/pnas.191367098

[^5]: Effect of artificial intelligence-based triaging of breast cancer screening mammograms on cancer detection and radiologist workload: a retrospective simulation study Dembrower, Karin et al. The Lancet Digital Health, Volume 2, Issue 9, e468 - e474

[^6]: Halalli, Bhagirathi et al. "Computer Aided Diagnosis - Medical Image Analysis Techniques." 20 Dec. 2017, doi: 10.5772/intechopen.69792

[^7]: Salod, Zakia, and Yashik Singh. "Comparison of the performance of machine learning algorithms in breast cancer screening and detection: A protocol." Journal of public health research vol. 8,3 1677. 4 Dec. 2019, doi:10.4081/jphr.2019.1677

[^8]: Gregor von Laszewski, Cloudmesh StopWatch and Benchmark from the Cloudmesh Common Library, [GitHub] 
      <https://github.com/cloudmesh/cloudmesh-common>
