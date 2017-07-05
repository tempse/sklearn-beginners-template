[![ML](https://img.shields.io/badge/subject-machine%20learning-blue.svg)]() [![scikit-learn](https://img.shields.io/badge/subject-scikit--learn-blue.svg)]() [![tutorial](https://img.shields.io/badge/subject-tutorial-blue.svg)]()

# Scikit-learn Beginner's Template

A basic multivariate analysis of simulated physics data using the machine learning toolkit [scikit-learn](http://scikit-learn.org/stable/index.html). The entire analysis example is conveniently presented in form of a [Jupyter Notebook](http://jupyter.org/).

The example at hand mainly addresses people who are new to machine learning, scikit-learn or Python and should provide them with code implementations of basic analysis steps and plots. It does not necessarily claim to yield optimal analysis results - not even good ones, necessarily - but should rather illustrate some fundamental concepts of machine learning application.

## Prerequisites

The provided example makes use of the following Python libraries/frameworks:
- scikit-learn
- numpy
- pandas
- matplotlib
- seaborn

## Machine Learning Concepts

The following concepts are covered and implemented:
- Data visualization:
    - Variable histograms
    - Scatter matrix
    - Correlation matrix
    - RadViz
- Data preprocessing:
    - Standard scaling
- Data split into training, validation and test samples
- Model definition and training with decision trees / random forest
- Feature importances
- Model evaluation on the validation sample
    - MVA output distribution
    - Cut efficiencies plot / MVA cut optimization
    - ROC curve
    - Precision-recall curve
    - Confusion matrix
    - Classification report
- Model application to the test sample

## Contributing

This project is far from perfect, not least because the author is relatively new to Python and scikit-learn himself.

If you have any suggestions or improvements, feel free to let me know or contribute in any way you like.

## License [![license](https://img.shields.io/github/license/mashape/apistatus.svg)]()

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Following [PurpleBooth](https://github.com/PurpleBooth)'s [README style](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
- All badges made by [shields.io](http://shields.io/)