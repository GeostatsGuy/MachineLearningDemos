<h1 align="center"<p>
    <img src="https://github.com/GeostatsGuy/GeostatsPy/blob/master/geostatspy_logo.png?raw=true" width="200" height="200" />
</p></h1>

<h1 align="center">MachineLearningDemos: Python Machine Learning Demonstration Workflows Repository (0.0.1)</h1>

<h3 align="center">Approximately 20 Well-Documented Machine Learning Workflows!</h3>

*It is challenging to learn machine learning. For me, great examples for common workflows are crtical. So I built out over 20 well-documented demonstration workflows that apply machine learning to accomplish common data science tasks to support my students in my **Data Analytics and Geostatistics**, **Spatial Data Analytics** and **Machine Learning** courses and anyone else learning data analytics and machine learning.* 

### Michael Pyrcz, Professor, The University of Texas at Austin, Data Analytics, Geostatistics and Machine Learning 
#### [Twitter](https://twitter.com/geostatsguy) | [GitHub](https://github.com/GeostatsGuy) | [Website](http://michaelpyrcz.com) | [GoogleScholar](https://scholar.google.com/citations?user=QVZ20eQAAAAJ&hl=en&oi=ao) | [Book](https://www.amazon.com/Geostatistical-Reservoir-Modeling-Michael-Pyrcz/dp/0199731446) | [YouTube](https://www.youtube.com/channel/UCLqEr-xV-ceHdXXXrTId5ig)  | [LinkedIn](https://www.linkedin.com/in/michael-pyrcz-61a648a1)

***

### Cite As:

Pyrcz, M.J., 2024, MachineLearningDemos: Python Machine Learning Demonstration Workflows Repository (0.0.1) (0.0.1). Zenodo. TBD

[![DOI](https://zenodo.org/badge/777871341.svg)](https://zenodo.org/doi/10.5281/zenodo.12667035) To Be Updated

***

#### Recent Updates

Here's some highlights from recent updates:

##### What's New with Version 0.0.1

I spent quite a bit of time checking, updating and improving all of the workflows for this first release.

* improved documentation with concepts and theory from my courses to motivate the workflows
* improved code comments
* improved data and model visualization

I'm quite happy with the current state. I feel that this set of well-documented workflow for machine learning in Python now lives up to its goal - to launch anyone into building machine learning workflows! I'm stoked to help out, Michael

***

#### Setup

A minimum environment includes:

* Python 3.7.10 - due to the depdendency of GeostatsPy on the Numba package for code acceleration
* GeostatsPy - I am continuously testing these workflow with the most current version, [GeostatsPy](https://pypi.org/project/geostatspy/)(Pyrcz et al., 2021)
* MatPlotLib - plotting
* NumPy - gridded data and array math
* Pandas - tabulated data
* SciPy - statistics module
* scikit-learn - most of the machine learnng models

The required datasets are available in the [GeoDataSets](https://github.com/GeostatsGuy/GeoDataSets) repository and linked in the workflows.

#### Repository Summary

More than 20 well-documented demonstration workflow for common machine learning workflows in Python. 

* utilizing synthetic data from my [GeoDataSets](https://github.com/GeostatsGuy/GeoDataSets) repository
* small and often 2D examples for fast run times and ease of interpretation
* often used and cited in my courses for repeatable educational content

Common geostatistical workflows that are included:

* multivariate analysis
* feature selection
* feature transformations
* cluster analysis
* principal component analysis
* linear regression
* ridge regression
* LASSO regression
* Bayesian linear regression
* naive Bayes classification
* polynomial regression
* k-nearest neighbours
* decision trees
* bagging trees and random forest
* gradiate boosting
* support vector machines

***

#### Installing GeostatsPy

Firstly, if you haven't installed GeostatsPy, here's the GitHub repository [GeostatsPy GitHub](https://github.com/GeostatsGuy/GeostatsPy/tree/master). GeostatsPy is available on the Python Package Index (PyPI) [GeostatsPy PyPI](https://pypi.org/project/geostatspy/).

To install GeostatsPy, use pip

```console
pip install geostatspy
```
***

#### GeostatsPy Package Dependencies

The functions rely on the following packages:

1. **numpy** - for ndarrays
2. **pandas** - for DataFrames
3. **numpy.linalg** - for linear algebra
4. **numba** - for numerical speed up
5. **scipy** - for fast nearest neighbor search
6. **matplotlib.pyplot** - for plotting
7. **tqdm** - for progress bar
8. **statsmodels** - for weighted (debiased) statistics                

These packages should be available with any modern Python distribution (e.g. https://www.anaconda.com/download/).

If you get a package import error, you may have to first install some of these packages. This can usually be accomplished by opening up a command window on Windows and then typing 'python -m pip install [package-name]'. More assistance is available with the respective package docs.  

#### GeostatsPyDemos Repository Author:

### Michael Pyrcz, Professor, The University of Texas at Austin 
*Novel Data Analytics, Geostatistics and Machine Learning Subsurface Solutions*

With over 17 years of experience in subsurface consulting, research and development, Michael has returned to academia driven by his passion for teaching and enthusiasm for enhancing engineers' and geoscientists' impact in subsurface resource development. 

For more about Michael check out these links:

#### [Twitter](https://twitter.com/geostatsguy) | [GitHub](https://github.com/GeostatsGuy) | [Website](http://michaelpyrcz.com) | [GoogleScholar](https://scholar.google.com/citations?user=QVZ20eQAAAAJ&hl=en&oi=ao) | [Book](https://www.amazon.com/Geostatistical-Reservoir-Modeling-Michael-Pyrcz/dp/0199731446) | [YouTube](https://www.youtube.com/channel/UCLqEr-xV-ceHdXXXrTId5ig)  | [LinkedIn](https://www.linkedin.com/in/michael-pyrcz-61a648a1)

#### Want to Work Together?

I hope this content is helpful to those that want to learn more about subsurface modeling, data analytics and machine learning. Students and working professionals are welcome to participate.

* Want to invite me to visit your company for training, mentoring, project review, workflow design and / or consulting? I'd be happy to drop by and work with you! 

* Interested in partnering, supporting my graduate student research or my Subsurface Data Analytics and Machine Learning consortium (co-PIs including Profs. Foster, Torres-Verdin and van Oort)? My research combines data analytics, stochastic modeling and machine learning theory with practice to develop novel methods and workflows to add value. We are solving challenging subsurface problems!

* I can be reached at mpyrcz@austin.utexas.edu.

I'm always happy to discuss,

*Michael*

Michael Pyrcz, Ph.D., P.Eng. Professor, Cockrell School of Engineering and The Jackson School of Geosciences, The University of Texas at Austin

#### More Resources Available at: [Twitter](https://twitter.com/geostatsguy) | [GitHub](https://github.com/GeostatsGuy) | [Website](http://michaelpyrcz.com) | [GoogleScholar](https://scholar.google.com/citations?user=QVZ20eQAAAAJ&hl=en&oi=ao) | [Book](https://www.amazon.com/Geostatistical-Reservoir-Modeling-Michael-Pyrcz/dp/0199731446) | [YouTube](https://www.youtube.com/channel/UCLqEr-xV-ceHdXXXrTId5ig)  | [LinkedIn](https://www.linkedin.com/in/michael-pyrcz-61a648a1)

More functionality will be added soon.
