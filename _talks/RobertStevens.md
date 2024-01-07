---
title: "Automatic Lesion Segmentation for Acute Ischemic Stroke Based on Early Non-contrast Computed Tomography"
collection: talks
type: "Graduate Research"
permalink: /talks/RobertStevens
venue: "School of Medicine, Johns Hopkins University"
date: 2023-9-30
location: "Baltimore, US"
---
![Alt text for image](/images/3Dlesion.png)
The study is to segment infarcted brain tissue volumes for acute ischemic stroke using the non-contrast head CT scans at the early stage. For segmenting small lesions on CT images, exen most experienced expert doctors can only achieve a dice score of 0.2.

Treatment for acute ischemic stroke (AIS) depends on an early assessment of infarcted brain tissue volumes. Non-contrast CT (NCCT) of the brain is the standard of care for patients presenting with stroke symptoms. When the onset time is known and early, the infarcted tissue is assumed to be sufficiently small that the benefits of treatment outweigh the bleeding risks. However, when patients present with an unknown or delayed onset time, lesion CT density changes, and image exams may lead to a delay in treatment. To address this problem, our group developed a segmentation approach with deep learning method to segment the stroke lesion on early NCCT images to assist doctoral diagnosis and treatment decision.

My main contribution is to build generative model (e.g. GAN, diffusion model) to generate syn-MRIs to help segmentation model. Generative model is suitable for this task is because the diagnosis of AIS depends on both DWI and ADC sequence. Therefore, I decided to synthesize DWI and ADC from CT and ask the model to segment lesion areas. 

This is research is a long-term research project and is still undergoing. In the future, it will upgrade to an automatic medical system that is capable of:
1. Detecting whether a patient has a potential for AIS from CT images.
2. Segmentting area with respect to lesions.
3. Classify different type of lesions to provide advice on medical treatments.
