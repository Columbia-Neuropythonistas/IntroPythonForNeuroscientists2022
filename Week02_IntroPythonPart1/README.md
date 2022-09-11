# Week 2 -- Intro to Python Part 1

## Pre-Work
Like last week, if you run into issues please contact us before class. Please upload a screenshot of the problem you are running into to the relevant assignment on courseworks so we can help you debug.

### 1. Test to make sure you have your ssh key set up correctly by following the [test instructions](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection).
- Please take a screenshot of your terminal output showing what is expected from step 3 of the instructions and submit it to the assignment on courseworks.
- Remember that you should copy lines starting with `$` in to your terminal, excluding the `$`. Lines after `#` give a comment or explanation on what you are being told to do, and lines after `>` are the output you should expect to see.
- Windows users, use git bash for this.
- If you get errors about git being an unknown command, make sure the intropython environment is active for this step.
- If you run into issues, make sure you have finished following the ssh key setup instructions we used in the first class, specifically: 
  1. [Generating a new ssh key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#generating-a-new-ssh-key)
  2. [Adding your ssh key to the ssh agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#adding-your-ssh-key-to-the-ssh-agent)
  3. [Add a new ssh key to your github account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account#adding-a-new-ssh-key-to-your-account)
  
### 2. Navigate to your git repo
- If you were able to `git clone` successfully during or after class, use `cd` and `ls` in terminal to navigate to your github repository on your computer.
- If running `git status` gives you an error like this: ```fatal: not a git repository (or any of the parent directories): .git```, you are not in your git repository, and either still need to navigate to it, or you may not have successfully run `git clone` during class.
- If you were unable to run `git clone` successfully during or after class, please do so now.
  - Go to your repository by going to [github](github.com), clicking on your profile picture at the top right, clicking "My Repositories" and then clicking the repository you made for class.
  - Click on the green button labeled "Code", make sure ssh is selected, and copy the link to the repository -- mine is "git@github.com:syncrostone/IntroPythonExample.git"
  - Go to terminal (git bash in windows) and run `git clone <your-url>`, so I would run `git clone git@github.com:syncrostone/IntroPythonExample.git`. 
- Run `git status`, take a screenshot of the result, and upload it to the assignment on courseworks.

### 3. Move hello.py to your git repo.
 - See the video linked in the assignment, and submit a screenshot to the assignment at the end.

### 4. Commit hello.py to your git repo.
- See the video linked in the assignment, and submit a screenshot of hello.py in your github repo online at the end.

### 5. Create a jupyter notebook and commit it to your git repo.
- See the video linked in the assignment, and submit a link to the ipynb file in your github repo at the end.
- [More on markdown in case you are curious](https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Working%20With%20Markdown%20Cells.html)

### 6. Watch a short video to prepare for class (and remember to watch last week's video if you forgot to).
- [Programming Terms: Mutable vs Immutable (7 min video)](https://www.youtube.com/watch?v=5qQQ3yzbKp8)


## Resources
- [W3 schools python intro](https://www.w3schools.com/python/python_operators.asp)
- [Python's tutorial](https://docs.python.org/3/tutorial/introduction.html)

## Optional After Class Practice
- [Coding Bat](https://codingbat.com/python)
