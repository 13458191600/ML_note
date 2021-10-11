# ML


## chapter1

### description

- dataset

	- sample space

		- rows

			- sample/instance

				- feature vector

		- cols

			- feature

			- feature value

			- dimensionnalty 

				- the amount of features

	- label space

		- Discrete

			- classification

		- continus

			- regression

		- supervised

	- no label

		- unsupervised

- learning

	- learner/model

- hypothesis

	- function learned

		- valid hypothesis

			- version space

- testing

	- testingsample

### hypothesis

- induction

	- concept learing

		- bool concept

- deduction

## Chapter2

### error rate

- training error

- generalization error

### fitting

- training error is low but generalization error  is high

	- overfitting

		- gets one-to-one function

		- can’t be avoided

			- P != NP

- training error is high

	- underfitting

- generalization error  is low

	- nice model

### model selection 

- divide dataset into training and test space

	- hold out

		- label :Uniform distribution better

		- Randomly divide and average

		- When the test set is small, the variance of the evaluation result is large

		- When the training set is small, the evaluation result has a large deviation 

		- 2/3-4/5 for training

	- cross vaidation

		- k-fold cross vaidation

			- k- 10

			- k=1

				- all data

	- bootstrapping

		- default

			- Estimated Bias

		- virtue

			- small dataset

			- Integrated learning

