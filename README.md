# Data Analysis and Visualization of NYC EV Fleet Station Network

Authors:  **Genith Silvester George Betsy**, **Lakshmi Narasimhan Jayasimhan**, **Khushboo Ashwin Parmar**, **Manmohan Vijaybhaskar Adam**.

YouTube Video:  [Link](http://your_link_goes_here)


## Task List

| ID | Task Description | Due Date | Status |
| --- | --- | --- | --- |
| 1 | Define project scope and objectives | 2023-04-21 | DONE |
| 2 | Detailed project proposal | 2023-04-24 | DONE |
| 3 | Data cleaning | 2023-04-27 | DONE |
| 4 | Analyzing charging stations located in New York City | 2023-05-02 | DONE |
| 5 | Evaluating and comparing agencies in NYC based on their operational size | 2023-05-04 | DONE |
| 6 | Visualize agency charging port capacity | 2023-05-06 | DONE |
| 7 | Analysis on number of charging ports | 2023-05-08 | In progress |
| 8 | Analyzing the capacity of charging stations in the different boroughs of NYC | 2023-05-10 | Not started |
| 9 | Number of vehicles in operation within each Borough | 2023-05-12 | Not started |
| 10 | Number of agencies in operation within each Borough | 2023-05-14 | Not started |
| 11 | Number of agencies in operation within each Borough | 2023-05-15 | Not started |
| 12 | Result of the analysis | 2023-05-15 | Not started |
| 13 | Complete YouTube video and upload to YouTube | 2023-05-16 | Not started |
| 14 | Upload README.md document to Github | 2023-05-17 | Not started |

## Introduction
*The purpose of this section is to provide some background about your project.  For example, your introduction should discuss*
- *The purpose of your project;*
- *The type of data you're using;*
- *What you're doing with this data;*
- *What types of analysis you're conducting;*

*Your introduction should make the reader excited to read the rest of this document.*

---

## References
*In this section, provide links to your references and data sources.  For example:*
- Source code was adapted from [the magic source code farm](http://www.amagicalnonexistentplace.com)
- The code retrieves data from [the organization for hosting cool data](http://www.anothermagicalnonexistentplace.com)
- The forecasting models were modified from [some academic research paper](http://www.linktotheacademicpaperyouused.com)

---

## Requirements
*In this section, provide detailed instructions for installing any necessary pre-requisites.  This could include:*
- *Python packages/libraries;*
- *API keys;*
- *etc.*

---

## Explanation of the Code
*In this section you should provide a more detailed explanation of what, exactly, your Python script(s) actually do.  Your classmates should be able to read your explanation and understand what is happening in the code.*

The code, `needs_a_good_name.py`, begins by importing necessary Python packages:
```
import matplotlib.pyplot as plt
```

- *NOTE:  If a package does not come pre-installed with Anaconda, you'll need to provide instructions for installing that package here.*

We then import data from [insert name of data source].  We print the data to allow us to verify what we've imported:
```
x = [1, 3, 4, 7]
y = [2, 5, 1, 6]

for i in range(0,len(x)):
	print "x[%d] = %f" % (i, x[i])		
```
- *NOTE 1:  This sample code doesn't actually import anything.  You'll need your code to grab live data from an online source.*  
- *NOTE 2:  You will probably also need to clean/filter/re-structure the raw data.  Be sure to include that step.*

Finally, we visualize the data.  We save our plot as a `.png` image:
```
plt.plot(x, y)
plt.savefig('samplefigure.png')	
plt.show()
```

The output from this code is shown below:

![Image of Plot](images/samplefigure.png)

---

## How to Run the Code
*Provide step-by-step instructions for running the code.  For example, I like to run code from the terminal:*
1. Ensure that you have registered for the [insert name of API] API key.  (You may reference the instructions for doing this.)

2. Ensure that you have installed necessary Python packages. (Again, you may include a reference here to a prior section in the README that provides the instructions.)


2. Open a terminal window.

2. Change directories to where `needs_a_good_name.py` is saved.

3. Type the following command:
	```
	python needs_a_good_name.py
	```

- *NOTE: You are welcome to provide instructions using Anaconda, IPython, or Jupyter notebooks.*

---

## Results from your Analysis
*Last, but not least, you need to demonstrate your results.  You should include figures and/or tables of results.  What worked well?  What could be improved?*
