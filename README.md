# Professional Certificate in Machine Learning and Artificial Intelligence
## Module 11: Practical Application 2: What Drives the Price of a Car?

The data comes from a subset of a Kaggle dataset but was given in the form of a CSV file found [here](https://mo-pcco.s3.us-east-1.amazonaws.com/BH-PCMLAI/module_11/practical_application_II_starter.zip)

Link for the [The Jupyter Notebook](https://github.com/tshih94/car-price-model/blob/main/car-price.ipynb)

## Findings
After doing my best to fill in missing information and removing obviously erroneous information, the model with the best mean squared error on the test data was the Ridge model with alpha = 1.0. It found luxury and premium marques such as Lexus, Maserati, and Porsche as well as special marques such as Tesla to sell for quite higher prices compared to other marques. Bigger work vehicle types such as trucks and pickups also commanded a premium compared to other types of cars. Additionally, manual transmissions and running on diesel boosted the price, as well as cleaner bills of health for condition and title status.

## Built With
* [Jupyter Notebooks](https://jupyter.org/) - Python3

## Authors

* **Tinyen Shih** 

## Acknowledgments
This project was created as a class assignment for the class Professional Certificate in Machine Learning and Artificial Intelligence, part of the Emeritus program from:
* [BerkeleyExecEd|BerkeleyHaas](https://em-executive.berkeley.edu/)
* [Kaggle](https://www.kaggle.com), dataset [here](https://mo-pcco.s3.us-east-1.amazonaws.com/BH-PCMLAI/module_11/practical_application_II_starter.zip)
