---
title: "Saliency-based Masked Autoencoder"
collection: talks
type: "Student Summer Research"
permalink: /talks/YijiangLi
date: 2023-08-08
location: "Baltimore, US"
---

I proposed a saliency-based masking technique over the conventional random masking to pretrain a visual foundation model called Masked Autoencoder (MAE). 

In the pretrain phase, I utilized the cc3m dataset, which pairs three million images with descriptive captions. These captions inherently draw human attention to the most informative elements of an image—for instance, if an image’s caption is “an elephant near the river”, people will pay more attention to the elephant rather than peripheral backgrounds like the sky or rocks. Aiming to replicate this discerning attention in machine learning, I leveraged the CLIP model with the GRAD-CAM technique to generate saliency maps.

Upon evaluating the model's generalization ability on downstream tasks, I encountered a counterintuitive result: the saliency-based masking model underperformed compared to the baseline model pretrained with random masking. I had hypothesized that focusing on key objects would expedite learning and enhance the model's visual comprehension. This unexpected phenomena puzzled me for two weeks. I solved the problem by going back to the essence of the problem: machine intelligence imitates humans, it will encounter the same problems as humans. Masking all important parts of a picture will make the picture meaningless and equivalent to noise.

Adjusting the saliency masking to cover only 25% of the image, I observed a notable improvement. The model's performance on ImageNet-1k classification tasks increased by 1.9% over the baseline after 100 epochs of pretraining. While this did not surpass the SOTA results achieved with pre-training 800 epochs, it confirmed the potential of saliency-based masking to accelerate learning within the constraints of available resources. Limited access to GPUs and the end of summer led me to pause this research. However, this experience helped me to secure two opportunities to work with professors at the start of this semester, marking significant progress in my academic journey.


