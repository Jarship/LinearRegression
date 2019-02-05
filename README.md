# LinearRegression
LinearRegression is a Jupyter Notebook presentation showing the basics of Neural Networks.

This was presentation 1 for the [Machine Learning GR](https://www.meetup.com/GRAIML/) meetup group. It shows how NNs approximate functions, such an AND gate. Linear Regression is approximated at the end.

In order to run the Jupyter Notebook itself, I would recommend installing either [Anaconda](https://www.anaconda.com/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html).
Conda is a command line/terminal tool that allows easy installation, and management of virtual environments, libraries, and dependencies.
Anaconda is the full suite of tools, and miniconda is a lightweight version.

After you have either installed and have cloned the repo, then the command

```conda env create -f environment.yml```

Creates the MLGR environment and installs all dependencies for the presentation.

You have to activate the environment

Windows: ```activate MLGR``` 

Mac or Linux: ```source activate MLGR```

Either: ```conda activate MLGR```

Then launch the Jupyter Notebook.

``` jupyter notebook 'Input to Output An example of Linear Regression.ipynb' ```

Helpful links:

[Conda Environment Cheatsheet](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)
