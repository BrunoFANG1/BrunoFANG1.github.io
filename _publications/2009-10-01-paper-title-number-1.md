---
title: "Adapting Visual Policies via Predicted Rewards"
collection: publications
permalink: https://sites.google.com/view/prft
excerpt: 'Image-based reinforcement learning (RL) faces significant challenges in generalization when the visual environment undergoes substantial changes between the training and testing phases. Under such circumstances, learned policies may not perform well leading to degraded results. Previous approaches to this issue largely have aimed to broaden the training observation distribution, employing techniques like data augmentation and domain randomization. Nevertheless, given the sequential nature of the decision-making problem, and residual errors propagated by the policy model can accumulate throughout the trajectory, resulting in highly degraded performance. 
In this paper, we leverage the observation that the predict rewards under domain shift, even imperfect, can still be useful signal to guide fine-tuning. We exploit this property to fine-tune the policy from reward prediction in the target domain. We have found that, even under significant domain shift, the predicted reward can still provide meaningful signal and fine-tuning substantially improves the policy. Our approach, termed Predicted Reward Fine-tuning (PRFT), improves performance across diverse tasks in both simulated benchmarks and real-world experiments.'
date: 2023-10-17
venue: 'First Workshop on Out-of-Distribution Generalization in Robotics at Conference on Robot Learning (CoRL)'
paperurl: 'https://drive.google.com/file/d/10BI6IhTAY8Zf6pmeVfVk1GrxAssGb1g8/view?usp=sharing'
link: 'https://sites.google.com/view/prft'
---
<div style="display: flex; justify-content: space-around;">
  <img src="/images/pub_3.png" alt="Image 1 Alt Text" style="width: 100%;"/>
</div>

Citation:
Weiyao Wang, *Xinyuan Fang*, Gregory D. Hager. Adapting Visual Policies via Predicted Rewards. *First Workshop on Out-of-Distribution Generalization in Robotics at Conference on Robot Learning (CoRL)*.
