

# Probability and Statistics in R

### Introduction
This repository contains all the Jupyter notebooks and R scripts used to complete the "Introduction to Probability and Statistics using R" course on Coursera. It's designed to provide other learners with resources and a framework for understanding the fundamental concepts of probability and statistics in R.

### Course Overview
This course provided an in-depth look into probability and statistics, emphasizing their applications in real-world scenarios. It focuses on designing studies, exploring data via numerical summaries and visualizations, and learning about rules of probability and commonly used probability distributions. The main tool used was R, a powerful programming language for statistical computing and graphics.

### How to Install and Run the Notebooks

#### Prerequisites
- **R:** Download and install R from the [CRAN repository](https://cran.r-project.org/). Choose the version compatible with your operating system and follow the installation instructions.
- **Jupyter Notebooks:** Install Jupyter via Anaconda (recommended for beginners) by downloading it from [Anaconda's website](https://www.anaconda.com/products/individual) or via pip (`pip install notebook`) for an existing Python setup.

#### Installing R Kernel for Jupyter
- After installing Jupyter, add the R kernel by running the following in your R console:
  ```R
  install.packages('IRkernel')
  IRkernel::installspec(user = FALSE)
  ```

#### Visual Studio Code Extensions
- **R Extension:** Enhance your R coding experience in VS Code by installing the [R Extension](https://marketplace.visualstudio.com/items?itemName=Ikuyadeu.r). It provides features like syntax highlighting and code snippets.
- **GitLens:** This extension helps you visualize code authorship at a glance via Git blame annotations and code lens ([GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)).
- **Markdown All in One:** Useful for editing README files and markdown documents within VS Code ([Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)).

### Weekly Lab Summaries

#### Week 1: Introduction to Probability and Data
Explored fundamental probability concepts and simulations in R. Examples include calculating the probability of events, simulating dice rolls, and understanding independent probabilities.

#### Week 2: Exploratory Data Analysis and Introduction to Inference
Introduced hypothesis testing and confidence intervals. For instance, we calculated real-life scenarios using data provided by BTS and RITA.

#### Week 3: Conditional Probability and Bayes' Theorem
Dove into conditional probability and Bayes' Theorem, applying them to problems like the hot hand problem. Practical R exercises included creating contingency tables and visualizing probabilities.

#### Week 4: Probability Distributions
Focused on different types of distributions (normal, binomial, etc.) and calculating expected values. Labs included performing t-tests on real data sets and interpreting the results to make informed conclusions.

#### Week 5: Data Analysis Project
Completed an initial data analysis project with a real-world data set (BRFSS2013). The project was designed to help discover and explore research questions of your own, using real data and statistical methods we learn in this class

### Running the Notebooks
To run these notebooks:
1. Clone the repository: `git clone https://github.com/egbonjefri/prob_stats_r`
2. Navigate to the cloned directory: `cd prob_stats_r`
3. Run Jupyter Notebook: `jupyter notebook`
4. Open the desired notebook file (`.ipynb`) in the Jupyter interface.

### Contributing
Contributions are welcome! If you have suggestions, corrections, or improvements to the code or documentation, please fork the repository and submit a pull request with your changes.

### License
This project is licensed under the MIT License - see the LICENSE.md file for details.

