---
date: 2021-06-16
title: "Overview of Feature Extraction Strategies related to Privacy Issues in Breast Cancer"
linkTitle: AI in Healthcare
tags: ["project", "reu"]
description: "This project provides an overview of feature extraction strategies in breast cancer diagnosis and detection as t relates with privacy issues."
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

Breast cancer is a form of disease that is caused by the growth of cells in the breast out of proportion. The major forms by which breast cancer can be detected are through. Artificial Intelligence(AI) is a concept or technology that is fast-growing in the medical and healthcare field. It has provided opportunities for the healthcare ecosystem to make quick analysis, observe trends and introduce technological solutions to healthcare problems like diseases. In  the  previous  studies, researchers  extracted  different  features  from  colon  biopsy  images  to  detect  the  cancer  and  distinguish  the  normal  and  malignant  subjects. 

Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

**Keywords:** ai, cancer, breast, algorithms, machine learning, healthcare, privacy.

## 1. Introduction

Breast cancer is the most common cancer and also the primary cause of mortality due to cancer in female around the World.(1) Breast cancer is the abnormal growth of cells in the breast region. Some are invasive while some are non-invasive. Early diagnosis and detection of possible cancerous cells in the breast can increase survival chances and provide a chance for better treatment and management. The breast cancer is diagnosed and detected through a ocmbination of different approaches such as imaging, physical examination by a radiologist and biopsy.(REFERNECE). Imaging employs the use of Artificial Intelligence(AI) and it consists of mammography and ultrasound. The results of the imaging as deciphered by a radiologist determines the next step. If detected present, a physical examination si conducted to decipher the kind of appearance - normal,benign or nonspecific. Then, biopsy is used to confirm the breast cancer symptoms. However, reseaarch has shown that radiologists can miss up to 30% of brease cancer(2). Hence, the introduuction of Computer aided Diagnosis (CAD) systems that can help radiologists to detect abnormailities in an efficient manner. CAD is a technology that includes concept of artificial intelligence(AI), medical image processing to find abnormal signs in the human body(3). Machine Learning in AI allows for the implementation of several algorithms that can be leveraged upon to . One of such is feature extraction.

Feature Extratcion strategies are methods that are used in machine learning to reduce the number of resources required to describe a large amount of data. In the diagnosis and detection of breast cancer, feature extraction strategies can include texture, morphological entropy based, scale invariant feature transform (SIFT), and wlliptic Fourier desriptors (EFDs).(2) Explain how it used in Machine learning.

Since the generation technology, cloud computing, privacy in healthcare has become a pertinent issue. Researchers need medical data to advance their work. in building an effective AI system, a large amount of data. Since these data belong to certain patients, sharing of patients' data calls for privacy concerns. Recent developments that have been done include designing a system that restricts access to a patient information only when the patient mobile approves the access.(Reference).

This project provides an overview of different feature extraction strategies that are related to privacy issues in breast cancer detection and diagnosis. 


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

[^2]: L. Hussain, W. Aziz, S. Saeed, S. Rathore and M. Rafique, "Automated Breast Cancer Detection Using Machine Learning Techniques by Extracting Different Feature Extracting Strategies," 2018 17th IEEE International Conference On Trust, Security And Privacy In Computing And Communications/ 12th IEEE International Conference On Big Data Science And Engineering (TrustCom/BigDataSE), 2018, pp. 327-331, doi: 10.1109/TrustCom/BigDataSE.2018.00057.     
      
[^3]: Effect of artificial intelligence-based triaging of breast cancer screening mammograms on cancer detection and radiologist workload: a retrospective simulation study Dembrower, Karin et al. The Lancet Digital Health, Volume 2, Issue 9, e468 - e474

[^3]: Halalli, Bhagirathi et al. "Computer Aided Diagnosis - Medical Image Analysis Techniques." 20 Dec. 2017, doi: 10.5772/intechopen.69792
      
      
[^4]: Salod, Zakia, and Yashik Singh. "Comparison of the performance of machine learning algorithms in breast cancer screening and detection: A protocol." Journal of public health research vol. 8,3 1677. 4 Dec. 2019, doi:10.4081/jphr.2019.1677

[^5]: Gregor von Laszewski, Cloudmesh StopWatch and Benchmark from the Cloudmesh Common Library, [GitHub] 
      <https://github.com/cloudmesh/cloudmesh-common>
