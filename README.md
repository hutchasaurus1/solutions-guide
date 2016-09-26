## Normal Sprint Solutions


Solutions should follow the logical workflow the student might go through

1. Python script

	a. Comment each new part

		```python
		# Part 1
		```

	b. Add the text for each question before each part that is being answered

		```python
		# 1.1
		# Write a function to calculate the root mean squared error using a
		# for loop
		Def rmse(predicted, true):
			“””
			Returns root mean squared error for any predicted values and
			associated true values
			“””
		Errors = []
		For i, pred in enumerate(predicted):
		Errors.append((pred - true[i]) ** 2)
		Return np.mean(Errors) ** .5
		```

	c. If one question alters a small part of a previous function, rewrite the function then comment on the changed lines

		```python
		# 1.2
		# Rewrite the root mean squared error function using numpy operations to # remove the for loop
		Def rmse(predicted, true):
			“””
			Returns root mean squared error for any predicted values and
			associated true values
			“””
		errors = (np.array(predicted) - np.array(true)) ** 2 # Condensed the for loop to one line
		return np.mean(Errors) ** .5
		```

	d. Link to good example

2. Object oriented problems

	a. Comment each section of the object with the part of the problem the object was created in

	b. Include docstrings for each function within the object

	c. Link to good example

## Case Studies

1. ???


## Assessments

1. Follow the general instructions for the python solutions, case studies, math and text solutions

## Python Solutions

1. All code written in python should follow pep-8 style standards

	a. Use pep-8 linter in your text editor!

	b. https://www.python.org/dev/peps/pep-0008/

2. Every function or class should start with a docstring where the first line is a short description of what the function does

3. Multiple word function names should be separated by an underscore (this_function())

4. Link to good example

## Math and Text Solutions

1. Written in markdown

2. Use Latex to display proper notation when necessary

3. Link to good example
