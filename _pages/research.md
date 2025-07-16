---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

Our research areas span from developing an interactive user interface with eye tracking to using eye tracker as a diagnostic tool for various applications, such as cognitive style classification. Our latest research interest has been implementing deep learning technology for various gaze-based applications such as:
- Spontaneous gaze-based interaction.
- Time-series eye movement data classification
- Predicting cognitive style of online learners and online shoppers through visual attention.
- Visual saliency model for optimizing user experience of web. <br><br> 
  

:white_check_mark: Intelligent touchless technology based on eye tracking sensor
========

<iframe width="400" height="200" src="https://www.youtube.com/embed/WYedQ0HJaWY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

We are working on developing an intelligent touchless technology based on artificial intelligence and eye tracking sensor. This technology is promising for public health education and prevention of Covid-19. We are working on a government-sponsored research project that explores possibilities of replacing old-fashioned eye movements classification methods with modern architectures of deep neural networks such as BiLSTM, Temporal Convolutional Networks, and so forth. We also have keen interest on optimizing deep neural networks architecture in gaze-based applications with various techniques such as pruning, hyperparameters optimization, knowledge distillation, and neural architecute search. Our focuses are not only performance of algorithm, but also minimizing carbon footprint of the developed technology. Our final goal will be developing robust gaze-based applications that are powered by eco-friendly deep learning technology. <br><br>


:white_check_mark: Unlocking cognitive styles with time-series eye tracking and artificial intelligence
========

<img src="/images/et_cognitive.png" width="600">
<figcaption>Eye tracking patterns resemble different cognitive style: Sequential vs. Global.</figcaption>

Personalized education works best when we understand how people learn. One key factor is cognitive style — whether someone prefers a sequential or a global learning approach. Eye tracking has shown promise in distinguishing these styles, but past research relied on proprietary software and oversimplified the data, often boiling down each person’s gaze patterns into a single row of numbers. That left a lot of insight untapped. Our team set out to change that by leveraging the full richness of time-series eye tracking data and applying advanced machine learning. We explored how different data window sizes and individual features impact classification accuracy, using the well-established Felder–Silverman Learning Style Model as our framework. In our latest study, 68 participants viewed a learning object for 60 seconds while we recorded their eye movements. The results were striking: XGBoost, trained on time-series data, achieved a classification accuracy of 99.65%—outperforming other state-of-the-art models. Even more impressive, the system could accurately classify cognitive style in just 5 seconds of gaze data, still hitting 99.67% accuracy. We also found that just three features—displacement, and horizontal and vertical gaze coordinates—were enough to reach this performance. These findings highlight the power of time-series eye tracking to uncover subtle patterns that can drive adaptive, data-driven learning. This work lays the groundwork for smarter, more responsive educational tools that adapt to how each of us learns best. <br><br>


:white_check_mark: Teaching machines to see what we read: improving saliency prediction in text-heavy images
========

<img src="/images/et_saliency.png" width="600">
<figcaption>Saliency prediction using deep learning in text-heavy images</figcaption>

Most saliency prediction models are trained on natural scenes, learning to spot what draws our eyes — shapes, colors, and objects in the wild. But throw text into the mix, and things get tricky. That’s because our brains process words very differently from visual features like trees or faces. Our research team set out to bridge this gap by fine-tuning saliency models to better handle text-rich images — in particular, movie posters, which often combine striking visuals and bold typography. Building on two state-of-the-art models, GSGNet and TranSalNet, we trained them to recognize the unique ways people look at text in context. The results were impressive: our fine-tuned models significantly outperformed the originals at predicting where viewers focus on movie posters. The experiments also revealed that text elements in images follow learnable patterns — opening the door to smarter, more accurate saliency predictions in advertising, design, and beyond. <br><br>

:white_check_mark: Taming motion sickness in 3D movies with gaze behavior and biometrics
========

<iframe width="400" height="200" src="https://www.youtube.com/embed/jU4WoOHJH-E" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Stereoscopic 3D movies were once hailed as the future of entertainment, but for many viewers they also brought nausea, dizziness, and discomfort — symptoms of visually induced motion sickness (VIMS). To better understand and address this problem, our team conducted a study combining self-reported symptoms, heart rate variability (ECG), and 3D gaze tracking to uncover how the body and eyes respond to 3D motion. Forty participants watched one of two 3D movies: a moderate-motion computer-generated city walkthrough, or an intense real roller-coaster ride. Half were instructed to keep their eyes fixed on a point during the movie, while the rest viewed freely. The roller-coaster scenes triggered more severe symptoms, but viewers who fixated their gaze experienced significantly less nausea and disorientation.

Heart rate data revealed that free viewers had stronger sympathetic nervous system activation — a marker of stress — particularly during intense scenes. Meanwhile, 3D gaze tracking showed that participants with higher sickness scores exhibited more erratic depth gaze movements. Fixated viewers showed steadier depth gaze, suggesting that stable eye behavior helps reduce sensory conflicts that cause VIMS. Notably, the researchers used a consumer-grade, low-frame-rate 3D gaze tracker and still detected meaningful patterns, demonstrating that affordable tools could monitor discomfort in real time. These findings suggest that keeping gaze fixed and minimizing abrupt depth changes could make 3D (and by extension, VR/AR) experiences more comfortable. This work highlights the importance of measuring not just subjective discomfort but also physiological and eye movement responses to immersive media. As virtual environments become more common, understanding how gaze and bodily signals interact could help designers build experiences that excite without making users sick. <br><br>

:white_check_mark: Detecting vertigo with eye movements: a dual-camera system for 3D tracking
========

<iframe width="400" height="200" src="https://www.youtube.com/embed/aaToRS88l-Y" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Accurately tracking the complex, three-dimensional movements of the human eye is crucial in clinical diagnostics and research. Traditional systems, like the scleral search coil, while precise, are invasive and uncomfortable. More modern video-based systems have emerged, but they often suffer from geometric distortions, cumbersome calibration, or the need for contact lenses with artificial markers — all impractical for routine use. To tackle these challenges, our team developed a novel, dual-camera system that combines simplicity, precision, and real-time performance. Mounted on a lightweight goggle, two miniature infrared-sensitive cameras simultaneously capture stereo images of one eye. Using center-of-mass and template-matching algorithms, the system tracks the pupil center and iris striations in two dimensions. A direct linear transformation (DLT) algorithm then reconstructs the full 3D position of the eye, correcting for geometric distortions without complicated, per-patient calibration or camera adjustments.

The system achieves angular errors as low as 0.15° horizontally, 0.14° vertically, and 0.20° torsionally — better than many existing methods — and delivers real-time feedback via an OpenGL-based 3D visualization of the eyeball. Validation tests showed the system robustly tracks both voluntary movements, like following a moving target, and involuntary movements, like the nystagmus seen in vertigo patients. Affordable, easy to use, and accurate, this dual-camera setup points the way toward more practical and widespread use of 3D eye-tracking in clinical settings. With further refinements, it could even pave the way for high-speed or wireless applications, opening new possibilities for diagnosing and understanding eye and vestibular disorders. <br><br>

