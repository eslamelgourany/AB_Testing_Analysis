# AB test Analysis


#### Table of Contents

1. [Project Motivation](#motivation)
2. [Data Description](#data)
3. [Results](#results)

### Project Motivation <a name="motivation"></a>

A/B tests are very commonly performed by data analysts and data scientists. For this project, I will be working to understand the results of an A/B test run by an e-commerce website. At the end of the project, I would give a recommendation to the company to one of the following points:

* Implement the new webpage,
* Keep the old webpage, or
* Perhaps run the experiment longer to make their decision.


### File Description <a name="data"></a>

'Analyze_ab_test_results_notebook.ipynb' - Python Notebook to show the experiement results.

### Results <a name="results"></a>

1. After using different ways to test whether new page increases conversion, it seems as a conclusion for all of the ways that the new page failed to provide better performance/conversion than the old page, and therfore we **fail to reject the null hypothesis** which means we go with the old page.
2. I tried to use the data to build ML model to predict whether a customer will convert but it wasn't possible to achieve high performance using only the given data.
