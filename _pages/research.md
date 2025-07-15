---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

Our research interests span from developing an interactive user interface with eye tracking to using eye tracker as a diagnostic tool for various applications, such as cognitive style classification. Our latest research interest has been implementing deep learning technology for various gaze-based applications such as:
- Spontaneous gaze-based interaction.
- Time-series eye movement data classification
- Predicting cognitive style of online learners and online shoppers through visual attention.
- Visual saliency model for optimizing user experience of web.

[![CoviDisplay first version (2021)](https://img.youtube.com/vi/ApU1MEdvkPI/0.jpg)](https://www.youtube.com/watch?v=ApU1MEdvkPI)

[![CoviDisplay second version (2023)](https://img.youtube.com/vi/WYedQ0HJaWY/0.jpg)](https://www.youtube.com/watch?v=WYedQ0HJaWY)

Intelligent touchless technology
=====
We are working on developing an intelligent touchless technology based on artificial intelligence and eye tracking sensor. This technology is promising for public health education and prevention of Covid-19. We are working on a government-sponsored research project that explores possibilities of replacing old-fashioned eye movements classification methods with modern architectures of deep neural networks such as BiLSTM, Temporal Convolutional Networks, and so forth. We also have keen interest on optimizing deep neural networks architecture in gaze-based applications with various techniques such as pruning, hyperparameters optimization, knowledge distillation, and neural architecute search. Our focuses are not only performance of algorithm, but also minimizing carbon footprint of the developed technology. Our final goal will be developing robust gaze-based applications that are powered by eco-friendly deep learning technology.

<img src="/images/et_cognitive.png" width="600">
<figcaption>Eye tracking patterns resemble different cognitive style: Sequential vs. Global.</figcaption>

Eye tracking and AI for predicting cognitive style
=====

Personalized education works best when we understand how people learn. One key factor is cognitive style — whether someone prefers a sequential or a global learning approach. Eye tracking has shown promise in distinguishing these styles, but past research relied on proprietary software and oversimplified the data, often boiling down each person’s gaze patterns into a single row of numbers. That left a lot of insight untapped. Our team set out to change that by leveraging the full richness of time-series eye tracking data and applying advanced machine learning. We explored how different data window sizes and individual features impact classification accuracy, using the well-established Felder–Silverman Learning Style Model as our framework. In our latest study, 68 participants viewed a learning object for 60 seconds while we recorded their eye movements. The results were striking: XGBoost, trained on time-series data, achieved a classification accuracy of 99.65%—outperforming other state-of-the-art models. Even more impressive, the system could accurately classify cognitive style in just 5 seconds of gaze data, still hitting 99.67% accuracy. We also found that just three features—displacement, and horizontal and vertical gaze coordinates—were enough to reach this performance. These findings highlight the power of time-series eye tracking to uncover subtle patterns that can drive adaptive, data-driven learning. This work lays the groundwork for smarter, more responsive educational tools that adapt to how each of us learns best.

