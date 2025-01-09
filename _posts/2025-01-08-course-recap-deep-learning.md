---
title: 'Course Recap and Reflections: Deep Learning'
date: 2025-01-08
permalink: /posts/2025/01/deeplearning/
tags:
  - course-recap
  - cogsci-masters
  - 'neural networks'
---

#### **Course Overview:**
This course provided an invaluable processes and concepts to the field of deep learning, combining foundational concepts with practical implementation. Started from basic NN architectures, neurons, backprop, loss functions, performance metrics, prediction features with SHAP, to CNN, RNN and pretrained models for image classification and so many others. From a cognitive neuroscience perspective, it highlighted how computational techniques can deepen our understanding of brain and behavior.  

## Broader Topics Covered 

- **Introduction** to deep learning, backpropagation algorithm, adaptive optimization methods. These fundamentals provided insight into how artificial networks model cognitive processes like learning and memory. Learning from errors.
- **Layers:** Convolution and pooling layers, ConvNet architectures, and data augmentation for computer vision tasks. CNNs' ability to analyze spatial features is directly applicable to processing neuroimaging data, such as fMRI or EEG.
- **Transfer Learning:** Analogous to how the brain reuses knowledge across tasks, providing frameworks to study domain generalization in cognitive systems.  
- **Reinforcement Learning (RL):** Models decision-making and reward optimization, which are directly relevant to understanding behavioral adaptation in neuroscience.  
- **Automatic Speech Recognition (ASR) & Text-to-Speech (TTS):** Highlighted parallels with auditory cognition and speech processing in the brain.  
- **Model Interpretability:** Techniques like attention weight visualization and SHAP values ensure computational models align with biological processes, making them useful in neuroscience research.

## Key Takeaways

- **Data** for the whole project is as important as the project itself. Data size, preprocessing and standardizing are important to designing a good model. 
- **Data shape** as it's fed to the network must be monitored as it goes through the layers due to the matrix multiplications with activation and other hidden functions. Not knowing data shape and how it changes at each step is dangerous.
- **Transfer learning** is just one of the best ideas; Its like student getting the professors bucket of experience without having to spend same decades of learning patterns and connections. The professor just passes it over (transfer) and the student(new model) can just do few final layer training and it is as good as the professor. 
- **Prior to this course**, I have played with lots of ML and data have mostly been few megabytes. Well, real projects and neuroscience data are just a little heavy (Gigabytes). Processing data in batches saved my semester (actually google colab GPU was the real savior). Since then, I have learned new tricks avaible in both pytorch and keras for handling big data. 
- **Not sure if this is key catch** but in some cases, just adding dropouts, batch normalizations, increasing width and depth of model architecture just did'nt work beyond increasing training time. This was irritating, and sometimes all i needed was to patiently build simple structures then increase density. Worked in most cases.
- **Few Changes at a time** was a pearl of advice from the course professor. This trick helped me to follow and see effect  of stuctural changes i made. It does not help to tune and make many changes at a time because eventually something works and you really do not know which of the twerks worked. 
- **More**: Yes there is so much more, and I will implement them in my neurscience data analysis pipelines and publish outcomes. 

## Practical Application  

Hands-on experience with tools like PyTorch and ConvNets enabled the development of interpretable models that align computational outputs with biological data. These skills will be instrumental in exploring cognitive and neural mechanisms, bridging computational and experimental neuroscience.  

In sum, this course laid a solid foundation for applying deep learning techniques in neuroscience, inspiring new research directions at the intersection of computation and cognition.

[Course link: Deep Learning by HSE, Skoltech & Yandex](https://www.hse.ru/en/edu/courses/894121223)

Other helpful resources: 
- [Deep Learning](https://www.deeplearningbook.org/) - A web book that provides good info and explanation about neural networks
- [Paperswithcode](https://paperswithcode.com/) - Site for accessing publications that implemented some code you may wish to know more about the paper or code
- [Huggging face](https://huggingface.co/models) - For pretrained models like BERTH, GPT-3, Datasets and so much more 