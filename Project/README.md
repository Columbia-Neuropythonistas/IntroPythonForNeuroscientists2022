# Project

## Important Dates and Deadlines
- Wed Oct 19th: Everyone must have [signed up](http://tiny.cc/pfncolumbia2022) for initial consultations
    - consults will take place Oct 25 - Nov 3
    - [sign up here](http://tiny.cc/pfncolumbia2022)
- Oct 25 - Nov 3: Project consultations take place
    - Come with some project ideas - if you don’t have data, take a look at the Neuromatch datasets before your consultation
- Mon Nov 7th: Project Proposals Due
    - Goals, people, plan
    - We will release a rubric at latest by Thu Oct 20th


## Project Outline
Can work individually or in pairs.
- If you want help finding a partner let us know if there  are particular datasets you are most excited about.

Four class periods (not expected to work outside class)
- Class 1/2: working on projects
- Class 3: code exchange
- Class 4: presentations (5 minutes)

Goal: work with data in python
- This can be your own, or a supplied dataset
- Try out a tool or package that you are interested in
- Create a small notebook showing all of your work and explaining it so that someone else can run and understand it

## Dataset & Tools Resources
Feel free to bring your own data. If you bring your own data, make sure to have it in a format that can be loaded into python by the first project work day. 

- [Dataset options from neuromatch](https://compneuro.neuromatch.io/projects/docs/datasets_overview.html)
- [Pure modeling package option (disclaimer: created by one of your instructors)](https://psychrnn.readthedocs.io/en/latest/)


## Rubric

### End product

The end product should be a Jupyter notebook, in which you define your analysis. Depending on your project, the result may look a little different. It may, but doesn’t have to involve functions. You should, however, make sure that you specify all the relevant input at the top of your notebook. For example, if you use a certain file to read in for your analysis, you should define a variable ‘file_path’ and provide it with the corresponding file path. This allows you to easily modify the file you are reading in if you want to analyze a different dataset. When provided an inappropriate input you should raise an error (or at least print out a message indicating that the code cannot work with this input).

### Functionality

The code should run if we execute the Jupyter notebook in order. Moreover, if we modify the input in a minor way, the notebook should still be able to execute in order. For example, maybe you are analyzing one particular neural dataset. If we instead read in a dataset structured in the same manner, the code should still work.

Hint 1: Make sure to run “Restart & Run All” under the “Kernel” tab in the notebook before turning your project in. This makes sure that the code runs if all cells are executed in order.
Hint 2: One major reason why your code may not run if the input is modified is if certain variables are hard-coded. For example, suppose you are analyzing a dataframe with 250 observations. This may mean that you are explicitly referencing this number of observations somewhere. You should not write “250” in this position, but rather compute how many observations your dataframe has (e.g. using “df.shape[0]”).

### Error handling

Some inputs to different steps in your analysis may be inappropriate. If this is the case, you should raise an error with the appropriate type and an informative error message that tells the user what went wrong.
Hint: Review the section on Exceptions in the lesson from Week 5 to see some examples for error messages and how you can raise them.

### Documentation

Your notebook should explain at each step what your code is implementing. If you are working with functions, you should use a docstring that explains the arguments your function is expecting, what the function is doing, and what the return values of the function look like. Otherwise you can simply provide the explanations as text in your notebook.
Hint: Explaining the arguments the function is expecting may give you some good ideas for appropriate error messages.

### Modularity (Advanced.)

We recommend that you work with functions. Each function you define should implement a specific step of your analysis. What this looks like will depend a lot on your project. It is also often difficult to see what the appropriate modularity for a given project is, so this is an advanced criterion.

### Efficiency (Advanced.)

Your code doesn’t need to be optimal, but it should not be much slower than an equally complicated solution. In particular, we encourage you to use vectorized operations on numpy arrays instead of lists or for loops, wherever possible.


