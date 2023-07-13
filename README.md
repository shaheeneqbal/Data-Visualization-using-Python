# Data-Visualization-using-Python
### About
In this project, Airbnb and HR Datasets are used for the visualization with the help of python libraries : Matplotlib and Seaborn. And also using Excel for analyzing and cleaning both the Datasets. Showing 10 different visualization by using these 2 datasets after loading into 2 different dataframes. In each Visualisation, describing about the columns that are being used to visualise and the forms of representation.
### Introduction
Data visualization is an essential part of data analysis and communication, as it allows us to understand and interpret data more effectively through visual representations such as charts, graphs, and maps. It can be used by teachers to display student test results, by computer scientists exploring advancements in artificial intelligence (AI) or by executives looking to share information with stakeholders and also plays an important role in big data projects. With the help of Data visualization, business users gain insight into their vast amount of data and get benefits from them to recognize new patterns and errors in the data. Making sense of these patterns help the users to pay attention to the areas that indicate red flags and progress.
### Prerequisites
Before begin, ensure that we have the following prerequisite:
* Jupyter Notebook
* Excel
### Data Source
Airbnb dataset from kaggle https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata

Human Resources dataset from kaggle https://www.kaggle.com/datasets/rhuebner/human-resources-data-set
### Getting Started
To get started with data visualization using Python:
* Two extensively used Python libraries for data visualisation are Matplotlib and Seaborn.
   * Matplotlib: A widely used library for creating static, animated, and interactive visualizations in Python. It provides a comprehensive set of functions for 
     creating line plots, bar charts, scatter plots, histograms, and more.
   * Seaborn: Built on top of Matplotlib, Seaborn provides a high-level interface for creating visually appealing statistical graphics. It simplifies the process 
     of creating complex visualizations such as heatmaps, pair plots, and categorical plots.
* In 1st Visualization: The columns using to visualize are 'neighbourhood_group' and 'price' from 'Airbnb dataset' with 'Bar chart' representation.
  
  ![image](https://github.com/shaheeneqbal/Data-Visualization-using-Python/assets/67499556/ff651f80-aad0-4cd6-971e-aac4654524a9)

  From this above chart we can analyze that variation in price depends on area by area.
* In 2nd Visualization: The columns using to visualize are 'number_of_reviews' and 'price' from 'Airbnb dataset' with 'Scatter chart' representation.

  ![image](https://github.com/shaheeneqbal/Data-Visualization-using-Python/assets/67499556/15e8e5f1-619f-4c77-bb65-135090f3e3c9)

  From this above chart we can analyze that most number of people like to stay in less price and their reviews are higher in those areas.
* In 3rd Visualization: Here using all the columns for visualization from 'Airbnb dataset' with 'Heatmap' representation.

  ![image](https://github.com/shaheeneqbal/Data-Visualization-using-Python/assets/67499556/0374463d-359b-4634-a4b1-e752895d2cf1)

  From this above visualization we have seen all the correlation between different features or variables.
* In 4th Visualization: The columns using to visualize are 'neighbourhood_group' and 'room_type' from 'Airbnb dataset' with 'countplot chart' representation.

  ![image](https://github.com/shaheeneqbal/Data-Visualization-using-Python/assets/67499556/308271b6-c705-450e-9da7-f1ec63aff053)

  From this above chart we can analyze that different types of rooms count grouped by neighbourhood_group.
* In 5th Visualization: The column using to visualize is 'neighbourhood' from 'Airbnb dataset' with 'Histogram chart' representation.

  ![image](https://github.com/shaheeneqbal/Data-Visualization-using-Python/assets/67499556/c398b66a-85d2-4173-8259-a1910465fd15)

  From this above chart we can analyze that the frequency or the occurance of neighbourhood.
* In 6th Visualization: The column using to visualize are 'Performance Score' and 'Salary' from 'HRDataset' with 'boxplot chart' representation.

  ![image](https://github.com/shaheeneqbal/Data-Visualization-using-Python/assets/67499556/89cf1a30-27f7-47e0-a415-e14807a1eb82)

  From this above chart we can analyze that the Employees having salary according to their performance score.
* In 7th Visualization: The column using to visualize is 'Salary' from 'HRDataset' with 'Distplot chart' representation.

  ![image](https://github.com/shaheeneqbal/Data-Visualization-using-Python/assets/67499556/97a3b71d-f0e3-4bee-9c8d-ac2dd7cf5717)

  From this above chart we can analyze that the maximum number of Employees have salary range between 50 thousand to 1 lakhs.
* In 8th Visualization: The column using to visualize are 'MaritalDesc' and 'Salary' from 'HRDataset' with 'Stripplot chart' representation.

  ![image](https://github.com/shaheeneqbal/Data-Visualization-using-Python/assets/67499556/8a174525-fb10-4d1d-a59e-8bafe6fb6da5)

  From this above chart we can analyze that the Salary distribution among the Marital Status.
* In 9th Visualization: The column using to visualize are 'Department' and 'Absences' from 'HRDataset' with 'violinplot chart' representation.

  ![image](https://github.com/shaheeneqbal/Data-Visualization-using-Python/assets/67499556/a7f6db36-3c05-41d1-a2af-1f9ddba1e4ca)

  From this above chart we can analyze that the number of Employees absent in each department.
* In 10th Visualization: The column using to visualize is 'Department' from 'HRDataset' with 'Pie chart' representation.

  ![image](https://github.com/shaheeneqbal/Data-Visualization-using-Python/assets/67499556/ad3e83a9-9657-446e-b5b6-92778ed6bf27)

  From this above chart we can analyze that the number of Employees in each department.
### License
This project is licensed under the MIT License. Feel free to modify and use it as per your requirements.
### Conclusion
Python offers a wide range of powerful libraries and tools that enable us to create stunning visualizations, uncover insights, and tell compelling stories with our data. The provided examples have demonstrated how to create different types of visualizations, including bar chart, scatter plot, heatmap, box plot and interactive plots. 

I hope this repository serves as a valuable resource for data visualization journey using Python.
