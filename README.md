**A vademecum of machine learning (with emphasis on sequential models)**

* * * * *

**Massimo Piccardi, University of Technology Sydney (UTS)**

email: Massimo (dot) Piccardi (at) uts.edu.au

http://scholar.google.com.au/citations?sortby=pubdate&hl=en&user=9OvNWLUAAAAJ&view_op=list_works

These notes present some useful techniques of machine learning, an area in which I have become increasingly interested in recent years. We start by covering three fundamental distributions (categorical aka discrete, Gaussian and the mixture), showing how to estimate their parameters with maximum likelihood and how to perform inference. We then introduce **classification by Bayes' theorem** and by probabilistic discriminative models (the **logistic regression classifier**). We also cover the **support vector machine**.
As the next step, we extend all these techniques to **sequential data**, covering **hidden Markov models**, **conditional random fields** and the **structural support vector machine**, using the linear-chain HMM and the HCRF as the graphical models of reference. Since text and video data are sequential in nature, the current coverage suits a broad range of applications in NLP and computer vision. **NB: all these classifiers are useful independently**, or as **output layers of deep networks!** So, it is definitely important to know them well. We also cover two other topics: 1) **dimensionality reduction** by linear models such as PCA and factor analysis and mixtures of linear models, preceded by a brief introduction to **linear regression**; 2) tracking, in the sense of **recursive Bayesian estimation**, including Kalman and particle filters. At some stage, I will add deep learning, obviously with focus on recurrent neural networks.

I sometimes post updates and corrections. Since April-May 2014, all these notes are accompanied by videolectures. The videolectures are streamed from a Mediasite server, requiring the MS Silverlight plug-in. The player allows re-sizing of the video or the slides at your preference. It also remembers your last position on the video, so you can stop watching and resume at any time.

[Introductory notes](SPR_00_Intro_v4.pdf)\
Introduction to the short course.

[Review of probability and statistics](SPR_01_ProbabilityReview_v4.pdf) |  [video (Intro + Review. 2h:38', 16/04/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/50d703fd3e1d4777b2ebaf8cd05319701d)\
Discrete and continuous random variables; joint, conditional, marginal probabilities, Bayes' theorem; expectations; the Gaussian distribution; Gaussian mixture models. [MATLAB examples](SPR_01_MATLAB.zip). Note: in this lecture, the view angle from the side is not optimal. In all the other videos, the view is frontal  and the whiteboard can be seen clearly.

[Density estimation](SPR_03_DensityEstimation_v4.pdf) | [video (2h:05', 23/04/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/5680d5ab5a364976bd64f379dd9a1dc11d)\
Density estimation. Maximum likelihood; EM; maximum a posteriori; Gaussian, GMM; nonparametric estimators: KDE. Some [exercises](Exercises.pdf) to solve.

[Dimensionality reduction](SPR_04_DimensionalityReduction_v3.pdf) | [video (2h:30', 30/04/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/13468514e7ac4cc6af6d4cf7843377c61d)\
Dimensionality reduction: principal component analysis (PCA), probabilistic PCA (PPCA), factor analysis (FA), mixtures, linear discriminant analysis (LDA). Mention to non-linear techniques. Preceded by a brief introduction to [linear regression](SPR_04a_LinearRegression_v2.pdf). [MATLAB examples](SPR_04_MATLAB.zip).

[Classification](SPR_02_Classification_v4.pdf) | [video (1h:57', 07/05/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/fee244746f4f48a59ad3ba69478cadb21d)\
Probabilistic classifiers. Measures of a test's accuracy. Classification by Bayes' theorem. Learning of probabilistic classifiers. [MATLAB examples](SPR_02_MATLAB.zip).

[Learning or inference?](SPR_03A_Inference_and_learning_v3.pdf) | [video (31', 07/05/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/61070c512b984fb49b5a27babb4ea6251d)\
 This is not a real lecture: just an exercise to recognise at a glance problems commonly labelled as "inference" and "learning".
 
[The hidden Markov model](SPR_05_HiddenMarkovModel_v5.pdf) | [video (2h:31', 14/05/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/58cb976b900343ef839b626df5e3459d1d)\
Sequential data. The hidden Markov model. A **A vademecum of machine learning (with emphasis on sequential models)**

* * * * *

**Massimo Piccardi, University of Technology Sydney (UTS)**

email: Massimo (dot) Piccardi (at) uts.edu.au

http://scholar.google.com.au/citations?sortby=pubdate&hl=en&user=9OvNWLUAAAAJ&view_op=list_works

These notes present some useful techniques of machine learning, an area in which I have become increasingly interested in recent years. We start by covering three fundamental distributions (categorical aka discrete, Gaussian and the mixture), showing how to estimate their parameters with maximum likelihood and how to perform inference. We then introduce **classification by Bayes' theorem** and by probabilistic discriminative models (the **logistic regression classifier**). We also cover the **support vector machine**.
As the next step, we extend all these techniques to **sequential data**, covering **hidden Markov models**, **conditional random fields** and the **structural support vector machine**, using the linear-chain HMM and the HCRF as the graphical models of reference. Since text and video data are sequential in nature, the current coverage suits a broad range of applications in NLP and computer vision. **NB: all these classifiers are useful independently**, or as **output layers of deep networks!** So, it is definitely important to know them well. We also cover two other topics: 1) **dimensionality reduction** by linear models such as PCA and factor analysis and mixtures of linear models, preceded by a brief introduction to **linear regression**; 2) tracking, in the sense of **recursive Bayesian estimation**, including Kalman and particle filters. At some stage, I will add deep learning, obviously with focus on recurrent neural networks.

I sometimes post updates and corrections. Since April-May 2014, all these notes are accompanied by videolectures. The videolectures are streamed from a Mediasite server, requiring the MS Silverlight plug-in. The player allows re-sizing of the video or the slides at your preference. It also remembers your last position on the video, so you can stop watching and resume at any time.

[Introductory notes](SPR_00_Intro_v4.pdf)\
Introduction to the short course.

[Review of probability and statistics](SPR_01_ProbabilityReview_v4.pdf) |  [video (Intro + Review. 2h:38', 16/04/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/50d703fd3e1d4777b2ebaf8cd05319701d)\
Discrete and continuous random variables; joint, conditional, marginal probabilities, Bayes' theorem; expectations; the Gaussian distribution; Gaussian mixture models. [MATLAB examples](SPR_01_MATLAB.zip). Note: in this lecture, the view angle from the side is not optimal. In all the other videos, the view is frontal  and the whiteboard can be seen clearly.

[Density estimation](SPR_03_DensityEstimation_v4.pdf) | [video (2h:05', 23/04/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/5680d5ab5a364976bd64f379dd9a1dc11d)\
Density estimation. Maximum likelihood; EM; maximum a posteriori; Gaussian, GMM; nonparametric estimators: KDE. Some [exercises](Exercises.pdf) to solve.

[Dimensionality reduction](SPR_04_DimensionalityReduction_v3.pdf) | [video (2h:30', 30/04/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/13468514e7ac4cc6af6d4cf7843377c61d)\
Dimensionality reduction: principal component analysis (PCA), probabilistic PCA (PPCA), factor analysis (FA), mixtures, linear discriminant analysis (LDA). Mention to non-linear techniques. Preceded by a brief introduction to [linear regression](SPR_04a_LinearRegression_v2.pdf). [MATLAB examples](SPR_04_MATLAB.zip).

[Classification](SPR_02_Classification_v4.pdf) | [video (1h:57', 07/05/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/fee244746f4f48a59ad3ba69478cadb21d)\
Probabilistic classifiers. Measures of a test's accuracy. Classification by Bayes' theorem. Learning of probabilistic classifiers. [MATLAB examples](SPR_02_MATLAB.zip).

[Learning or inference?](SPR_03A_Inference_and_learning_v3.pdf) | [video (31', 07/05/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/61070c512b984fb49b5a27babb4ea6251d)\
 This is not a real lecture: just an exercise to recognise at a glance problems commonly labelled as "inference" and "learning".
 
[The hidden Markov model](SPR_05_HiddenMarkovModel_v5.pdf) | [video (2h:31', 14/05/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/58cb976b900343ef839b626df5e3459d1d)\
Sequential data. The hidden Markov model. A [MATLAB example](SPR_05_MATLAB.zip). 

[Conditional random fields](SPR_07_ConditionalRandomFields_v4.pdf) | [video (2h:06', 21/05/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/5bbe235938fa42cc8654d4c5509c41a81d)\
Exponential family of distributions. Undirected graphical models. The linear-chain conditional random field and the hidden conditional random field. [MATLAB examples](SPR_07_MATLAB.zip).

[The support vector machine (SVM) and structural SVM](SPR_08_SVM_v3.pdf) | [video (2h:19', 11/06/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/0ae0150e722e40abbcddaa7c34337d8a1d)
The support vector machine (SVM). Multi-class SVM as a single machine. Structural SVM and latent structural SVM.

[Kalman and particle filters](SPR_06_KalmanAndParticleFilters_v5.pdf) | [video (2h:23', 04/06/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/2e4d7ac8b6c5430e86c79d1aa692aabd1d)\
Recursive Bayesian estimation. Kalman and particle filters.
[MATLAB example](SPR_05_MATLAB.zip). 

[Conditional random fields](SPR_07_ConditionalRandomFields_v4.pdf) | [video (2h:06', 21/05/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/5bbe235938fa42cc8654d4c5509c41a81d)\
Exponential family of distributions. Undirected graphical models. The linear-chain conditional random field and the hidden conditional random field. [MATLAB examples](SPR_07_MATLAB.zip).

[The support vector machine (SVM) and structural SVM](SPR_08_SVM_v3.pdf) | [video (2h:19', 11/06/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/0ae0150e722e40abbcddaa7c34337d8a1d)
The support vector machine (SVM). Multi-class SVM as a single machine. Structural SVM and latent structural SVM.

[Kalman and particle filters](SPR_06_KalmanAndParticleFilters_v5.pdf) | [video (2h:23', 04/06/2014)](https://mediasite.feit.uts.edu.au/Mediasite/Play/2e4d7ac8b6c5430e86c79d1aa692aabd1d)\
Recursive Bayesian estimation. Kalman and particle filters.
