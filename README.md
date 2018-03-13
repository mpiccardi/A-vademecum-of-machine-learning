**A vademecum of machine learning (with emphasis on sequential models)**

* * * * *

**Massimo Piccardi, University of Technology Sydney (UTS)**

email: Massimo (dot) Piccardi (at) uts.edu.au

http://scholar.google.com.au/citations?sortby=pubdate&hl=en&user=9OvNWLUAAAAJ&view_op=list_works

These notes present some useful techniques of machine learning, an area in which I have become increasingly interested in recent years. We start by covering three fundamental distributions (categorical aka discrete, Gaussian and the mixture), showing how to estimate their parameters with maximum likelihood and how to perform inference. We then introduce **classification by Bayes' theorem** and by probabilistic discriminative models (the **logistic regression classifier**). We also cover the **support vector machine**.
As the next step, we extend all these techniques to **sequential data**, covering **hidden Markov models**, **conditional random fields** and the **structural support vector machine**, using the linear-chain HMM and the HCRF as the graphical models of reference. Since text and video data are sequential in nature, the current coverage suits a broad range of applications in NLP and computer vision. We also cover two other topics: 1) **dimensionality reduction** by linear models such as PCA and factor analysis and mixtures of linear models, preceded by a brief introduction to **linear regression**; 2) tracking, in the sense of **recursive Bayesian estimation**, including Kalman and particle filters. At some stage, I will add deep learning, obviously with focus on recurrent neural networks.

I sometimes post updates and corrections. Since April-May 2014, all these notes are accompanied by videolectures. The videolectures are streamed from a Mediasite server, requiring the MS Silverlight plug-in. The player allows re-sizing of the video or the slides at your preference. It also remembers your last position on the video, so you can stop watching and resume at any time.

[Introductory notes](SPR_00_Intro_v4.pdf)\
Introduction to the short course.

[Review of probability and statistics](SPR_01_ProbabilityReview_v4.pdf) |  [video (Intro + Review. 2h:38', 16/04/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/50d703fd3e1d4777b2ebaf8cd05319701d)\
Discrete and continuous random variables; joint, conditional, marginal probabilities, Bayes' theorem; expectations; the Gaussian distribution; Gaussian mixture models. [MATLAB examples](SPR_01_MATLAB.zip). Note: in this lecture, the view angle from the side is not optimal. In all the other videos, the view is frontal  and the whiteboard can be seen clearly.

[Density estimation](SPR_03_DensityEstimation_v4.pdf) | [video (2h:05', 23/04/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/5680d5ab5a364976bd64f379dd9a1dc11d)\
Density estimation. Maximum likelihood; EM; maximum a posteriori; Gaussian, GMM; nonparametric estimators: KDE. Some [exercises](Exercises.pdf) to solve.
