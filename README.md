
![Logo](https://ccirlab.files.wordpress.com/2019/03/har_pic.jpeg)


# Human Activity Recognition Using Sensors Data

Human activity recognition (HAR) aims to classify a person's actions from a series of measurements captured by sensors.
Nowadays, collecting this type of data is not an arduous task. With the growth of the Internet of Things, almost everyone has some gadget that monitors their movements. It can be a smartwatch, a pulsometer, or even a smartphone.
Some of the entire features that we will use are -

- Body acceleration,
- Gravity acceleration,
- Body angular speed,
- Body angular acceleration, etc.


## Features

- The proposed model will able to classify the given measures of sensors into following classes:

    STANDING, SITTING, LAYING, WALKING, WALKING-DOWNSTAIRS, WALKING-UPSTAIRS 
- The above predicted classes will furthur used by different smart devices to monitor health, discover activity pattern and improve wellbeing.
- It is becoming a fundamental tool in healthcare solutions such as preventing obesity or caring for elderly persons.


## Optimizations

The proposed model trained using Hyperparameter tuning for different classifiers and on different combinations of parameters. The model achieved an Accuracy of 96% when trained using SVM and Radial Basis Function (RBF) as Kernel. 


## Tech Stack

NumPy, Pandas, Jupyter and other Python Libraries.


## Run Locally

Clone the project

```bash
  git clone https://github.com/bcsabhisekh/HAR.git
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  !pip install --dependencies
```

To run a .ipynb file as a script, run:

```bash
  pip3 install runipy # for python 3.x 
  pip install runipy  # for python 2.x
  runipy MyNotebook.ipynb # for executing
  runipy -o MyNotebook.ipynb # for saving output
  
```


## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## Used By

This project can be used as software that need to be install on IC (Integrated Chips) to perform monitoring using various devices like smartphones and smartwatches. The sensors present inside these devices will feed the required data.



## Acknowledgements

 - [Support Vector Machine](https://www.javatpoint.com/machine-learning-support-vector-machine-algorithm)
 - [Random Forest Classification Algorithm](https://en.wikipedia.org/wiki/Random_forest)
 - [Decision Tree Classification Algorithm](https://www.javatpoint.com/machine-learning-decision-tree-classification-algorithm)
  - [Hyperparameter Tuning](https://www.jeremyjordan.me/hyperparameter-tuning/)
 - [Dimensionality Reduction for Data Visualization using PCA and TSNE](https://towardsdatascience.com/dimensionality-reduction-for-data-visualization-pca-vs-tsne-vs-umap-be4aa7b1cb29)



## Feedback

If you have any feedback, please reach out to us at y.abhisekhmessi535@gmail.com

