A vademecum of machine learning
\
with emphasis on sequential models

* * * * *

\

**Massimo Piccardi, University of Technology Sydney (UTS)**

email: Massimo (dot) Piccardi (at) uts.edu.au \

http://scholar.google.com.au/citations?sortby=pubdate&hl=en&user=9OvNWLUAAAAJ&view_op=list_works

\

These notes present some useful techniques of machine learning, an area in which I have become
increasingly interested in recent years. We start by covering three
fundamental distributions (categorical aka discrete, Gaussian and the mixture), showing
how to estimate their parameters with maximum likelihood and how to use them in inference. 
We then introduce classification by Bayes' theorem and by probabilistic discriminative models (the logistic regression
classifier). We also cover maximum-margin classifiers and the support
vector machine. \
As the next step, we extend all these techniques to sequential data,
covering hidden Markov models, conditional random fields and the
structural support vector machine, using the linear-chain HMM and the
HCRF as the graphical models of reference. Since video data are
sequential in nature, the current coverage is well suited to
applications such as activity recognition and tracking. Although to date
we do not cover other types of structured outputs such as trees and
lattices, these notes can still be a good start towards them. For
tracking, we cover Kalman and particle filters. Lastly, a separate note
covers dimensionality reduction by linear models (such as PCA and factor
analysis) and mixtures of linear models. \
\
I frequently post updates and corrections. Since April-May 2014, these
notes are accompanied by videolectures. The videolectures are streamed
from a Mediasite server, requiring the MS Silverlight plug-in. The
player allows re-sizing of the video or the slides at your preference.
It also remembers your last position on the video, so you can stop
watching and resume any time.

\
\

+--------------------+--------------------+--------------------+--------------------+
| Title              | Last updated       | Content            | Video              |
+====================+====================+====================+====================+
| [Introductory      | 16/04/2014         | Introduction to    | see link below     |
| notes](SPR_00_Intr |                    | the short course.  |                    |
| o_v4.pdf)          |                    |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| [Review of         | 16/04/2014         | Discrete and       | [video (Intro +    |
| probability and    |                    | continuous random  | Review. 2h:38',    |
| statistics](SPR_01 |                    | variables; joint,  | 16/04/2014)](https |
| _ProbabilityReview |                    | conditional,       | ://mediasite.feit. |
| _v4.pdf)           |                    | marginal           | uts.edu.au/Mediasi |
|                    |                    | probabilities,     | te/Play/50d703fd3e |
|                    |                    | Bayes' theorem;    | 1d4777b2ebaf8cd053 |
|                    |                    | expectations; the  | 19701d)            |
|                    |                    | Gaussian           |                    |
|                    |                    | distribution;      | Note: in this      |
|                    |                    | Gaussian mixture   | lecture, the view  |
|                    |                    | models. [MATLAB    | angle from the     |
|                    |                    | examples.](SPR_01_ | side is not        |
|                    |                    | MATLAB.zip)        | optimal. In all    |
|                    |                    |                    | the other videos,  |
|                    |                    |                    | the view is        |
|                    |                    |                    | frontal and the    |
|                    |                    |                    | whiteboard can be  |
|                    |                    |                    | seen clearly.      |
+--------------------+--------------------+--------------------+--------------------+
| [Density           | 21/04/2014         | Density            | [video (2h:05',    |
| estimation](SPR_03 |                    | estimation.        | 23/04/2014)](https |
| _DensityEstimation |                    | Maximum            | ://mediasite.feit. |
| _v4.pdf)           |                    | likelihood; EM;    | uts.edu.au/Mediasi |
|                    |                    | maximum a          | te/Play/5680d5ab5a |
|                    |                    | posteriori;        | 364976bd64f379dd9a |
|                    |                    | Gaussian, GMM;     | 1dc11d)            |
|                    |                    | nonparametric      |                    |
|                    |                    | estimators: KDE.   |                    |
|                    |                    | Some               |                    |
|                    |                    | [exercises](Exerci |                    |
|                    |                    | ses.pdf)           |                    |
|                    |                    | to solve.          |                    |
+--------------------+--------------------+--------------------+--------------------+
| [Dimensionality    | 30/04/2014         | Dimensionality     | [video (2h:30',    |
| reduction](SPR_04_ |                    | reduction:         | 30/04/2014)](https |
| DimensionalityRedu |                    | principal          | ://mediasite.feit. |
| ction_v3.pdf)      |                    | component analysis | uts.edu.au/Mediasi |
|                    |                    | (PCA),             | te/Play/13468514e7 |
|                    |                    | probabilistic PCA  | ac4cc6af6d4cf78433 |
|                    |                    | (PPCA), factor     | 77c61d)            |
|                    |                    | analysis (FA),     |                    |
|                    |                    | mixtures, linear   |                    |
|                    |                    | discriminant       |                    |
|                    |                    | analysis (LDA).    |                    |
|                    |                    | Mention to         |                    |
|                    |                    | non-linear         |                    |
|                    |                    | techniques.        |                    |
|                    |                    | Preceded by a      |                    |
|                    |                    | brief introduction |                    |
|                    |                    | to [linear         |                    |
|                    |                    | regression](SPR_04 |                    |
|                    |                    | a_LinearRegression |                    |
|                    |                    | _v2.pdf)           |                    |
|                    |                    | (last updated:     |                    |
|                    |                    | 30/04/2014).       |                    |
|                    |                    | [MATLAB            |                    |
|                    |                    | examples.](SPR_04_ |                    |
|                    |                    | MATLAB.zip)        |                    |
+--------------------+--------------------+--------------------+--------------------+
| Classification     | 06/05/2014         | Probabilistic      | [video (1h:57',    |
|                    |                    | classifiers.       | 07/05/2014)](https |
|                    |                    | Measures of a      | ://mediasite.feit. |
|                    |                    | test's accuracy.   | uts.edu.au/Mediasi |
|                    |                    | Classification by  | te/Play/fee244746f |
|                    |                    | Bayes' theorem.    | 4f48a59ad3ba69478c |
|                    |                    | Learning of        | adb21d)            |
|                    |                    | probabilistic      |                    |
|                    |                    | classifiers.       |                    |
|                    |                    | [MATLAB            |                    |
|                    |                    | examples.](SPR_02_ |                    |
|                    |                    | MATLAB.zip)        |                    |
+--------------------+--------------------+--------------------+--------------------+
| [Learning or       | 06/05/2014         | This is not a real | [video (31',       |
| inference?](SPR_03 |                    | lecture: just an   | 07/05/2014)](https |
| A_Inference_and_le |                    | exercise to        | ://mediasite.feit. |
| arning_v3.pdf)     |                    | quickly recognise  | uts.edu.au/Mediasi |
|                    |                    | problems commonly  | te/Play/61070c512b |
|                    |                    | labelled as        | 984fb49b5a27babb4e |
|                    |                    | "inference" and    | a6251d)            |
|                    |                    | "learning".        |                    |
+--------------------+--------------------+--------------------+--------------------+
| [The hidden Markov | 14/05/2014         | The hidden Markov  | [video (2h:31',    |
| model](SPR_05_Hidd |                    | model. A [MATLAB   | 14/05/2014)](https |
| enMarkovModel_v5.p |                    | example.](SPR_05_M | ://mediasite.feit. |
| df)                |                    | ATLAB.zip)         | uts.edu.au/Mediasi |
|                    |                    |                    | te/Play/58cb976b90 |
|                    |                    |                    | 0343ef839b626df5e3 |
|                    |                    |                    | 459d1d)            |
+--------------------+--------------------+--------------------+--------------------+
| [Conditional       | 21/05/2014         | Exponential family | [video (2h:06',    |
| random             |                    | of distributions.  | 21/05/2014)](https |
| fields](SPR_07_Con |                    | Undirected         | ://mediasite.feit. |
| ditionalRandomFiel |                    | graphical models.  | uts.edu.au/Mediasi |
| ds_v4.pdf)         |                    | The linear-chain   | te/Play/5bbe235938 |
|                    |                    | conditional random | fa42cc8654d4c5509c |
|                    |                    | field and the      | 41a81d)            |
|                    |                    | hidden conditional |                    |
|                    |                    | random field.      |                    |
|                    |                    | MATLAB examples.   |                    |
+--------------------+--------------------+--------------------+--------------------+
| [The support       | 25/08/2014         | The support vector | [video (2h:19',    |
| vector machine     |                    | machine (SVM).     | 11/06/2014)](https |
| (SVM) and          |                    | Multi-class SVM as | ://mediasite.feit. |
| structural         |                    | a single machine.  | uts.edu.au/Mediasi |
| SVM](SPR_08_SVM_v3 |                    | Structural SVM and | te/Play/0ae0150e72 |
| .pdf)              |                    | latent structural  | 2e40abbcddaa7c3433 |
|                    |                    | SVM.               | 7d8a1d)            |
+--------------------+--------------------+--------------------+--------------------+
| [Kalman and        | 28/05/2013         | Kalman and         | [video (2h:23',    |
| particle           |                    | particle filters.  | 04/06/2014)](https |
| filters](SPR_06_Ka |                    |                    | ://mediasite.feit. |
| lmanAndParticleFil |                    |                    | uts.edu.au/Mediasi |
| ters_v5.pdf)       |                    |                    | te/Play/2e4d7ac8b6 |
|                    |                    |                    | c5430e86c79d1aa692 |
|                    |                    |                    | aabd1d)            |
+--------------------+--------------------+--------------------+--------------------+

\
