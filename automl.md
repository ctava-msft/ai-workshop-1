---
title: automl
layout: home
nav_order: 1
---

# Use AutoML in Azure ML Studio

## Introduction

Quality Healthcare has identified the need to develop a model to predict if patients will develop diabetes.

## Description

In this task, you will leverage the AutoML and compute to train a model to predict patient outcome of having diabetes or not.

To build a dataset inside of ML Studio please follow these steps off an AutoML job here are the following key tasks:

1. The following steps are used to setup data within ML Studio:

![data1](Images/data-1.png)
![data2](Images/data-2.png)
![data3](Images/data-3.png)
![data4](Images/data-4.png)


To kick off an AutoML job here are the following key tasks:

1. Use [Azure ML Studio](https://ml.azure.com) to kick off an Automated ML Job.

![automated-job](Images/automated-job.png)

2. Fill in the job and experiment name and click next.

![automated-job-1](Images/automated-job-1.png)

3. Select task type as Classification and choose Pima for the dataset and click next.

![automated-job-2](Images/automated-job-2.png)

4. For the target column choose Outcome and for the Experiment timeout (minutes) enter 15.

![automated-job-3](Images/automated-job-3.png)

5. Select Serverless Compute and a VM and click next.

![automated-job-4](Images/automated-job-4.png)

6. Click on Submit training job.

![automated-job-5](Images/automated-job-5.png)

## Success Criteria

* AutoML job runs and completes in 15 minutes. It should highlight which features are the most important to the performance of the model. All artifacts are generated and stored inside the storage account and container.