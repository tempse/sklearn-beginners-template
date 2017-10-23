![ML](https://img.shields.io/badge/subject-machine%20learning-blue.svg) ![scikit-learn](https://img.shields.io/badge/subject-scikit--learn-blue.svg) ![tutorial](https://img.shields.io/badge/subject-tutorial-blue.svg)

# Scikit-learn Beginner's Template

A basic multivariate analysis of simulated physics data using the machine learning toolkit [scikit-learn](http://scikit-learn.org/stable/index.html). The entire analysis example is conveniently presented in form of [Jupyter Notebooks](http://jupyter.org/).

This project mainly addresses people who are new to machine learning, scikit-learn or Python and should provide them with code implementations of basic analysis steps and plots. It does not necessarily claim to yield optimal analysis results - not even good ones, necessarily - but should rather illustrate some fundamental concepts of machine learning application.

## Prerequisites

The provided example makes use of the following Python libraries/frameworks:
- [scikit-learn](http://scikit-learn.org/)
- [numpy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)

## Machine Learning Concepts

The following concepts are covered and implemented:
- Data visualization
    - Variable histograms
    - Scatter matrix
    - Correlation matrix
    - RadViz
- Data preprocessing
    - Standard scaling
- Data split into training, validation and test samples
- Model definition and training with decision trees / random forest
- Overfitting the data and how to prevent it
- Feature importances
- Model evaluation using training and validation sample
    - MVA output distribution
    - Cut efficiencies plot / MVA cut optimization
    - ROC curve
    - Precision-recall curve
    - Confusion matrix
    - Classification report
- Model application to the test sample / classifier performance assessment

## Content overview and file description

Notebooks:
- [`example analysis - random forest.ipynb`](example%20analysis%20-%20random%20forest.ipynb): Example analysis of simulated physics data using a random forest classifier.
- [`overtraining demo - random forest.ipynb`](overtraining%20demo%20-%20random%20forest.ipynb): Using simulated physics data and a random forest classifier to demonstrate the effects and consequences of overtraining.

## Contributing

This project is far from perfect, not least because the author is relatively new to Python and scikit-learn himself.

If you have any suggestions or improvements, feel free to let me know or contribute in any way you like.

## License ![license](https://img.shields.io/github/license/mashape/apistatus.svg)

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Many thanks to [S. Lehner](https://github.com/sebaleh) for valuable feedback on first drafts of this project.
- Following [PurpleBooth](https://github.com/PurpleBooth)'s [README style](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
- All badges made by [shields.io](http://shields.io/)
