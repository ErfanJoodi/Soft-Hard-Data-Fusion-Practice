# Soft & Hard Data Fusion Practice

## Overview

In this practice, we wanted to combine soft and hard data together so we can have a better understanding of the problem. we are working on two different problems: bank customer risk assessment and programmers ranking.

## Dataset

The dataset was given by the questions.
for the bank customer risk assessment we had hard data as probabilities of being in each class(low-ridk, high-risk, ...) and the soft data as [belief, disbelief, uncertainty] from four different experts opinion.
for the programmers ranking the dataset was linguistic and we had four metric and two experts opinion.

## Project Structure

In the customer risk assessment we visualized the beta distribution function outputs.
In the programmers ranking we used IULOWA method and at the end, we simulate a method to combine the output of 4 different machine learning models by using average ranking.

## Requirements

Ensure you have the following packages installed:

* Python 3.x
* NumPy
* Pandas
* Matplotlib

You can install the required packages using:

```bash
pip install -r requirements.txt
```

## Usage

You can clone the repository and for customer risk assessment you should run the 'CustomerRiskAssessment.ipynb' notebook and for the programmers ranking you should run the 'Programmers.ipynb' notebook.

## Results

We can now see that there is some methods to use all kind of data together as soft and hard data fusion for better understanding of the problem in any situations, and also by using these methods we can use experts opinion to any problem.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.