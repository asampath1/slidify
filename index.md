Developing Data Products
=====================================================================================================================================
author: Anand
date:   26th July 2014

- Assignment
- Dataset Summary
- Prediction Summary
- Conclusion

Assignment
=================================================================================================================


- Part of the Data Science - Develop Data Products Course.
- Developed a Shiny application and deployed into the Shiny Apps io server. 
- [Shiny Apps IO Link](http://asampath1.shinyapps.io/ShinyApps-Project)
- ui.R and server.R files corresponding to the Shiny applications are deployed in  the github repository
- [Github Repository Link](https://github.com/asampath1/ShinyApps-Project.git)
- Application has one side Panel and a 3 tabs in the main panel
- First Tab is a Writeup  tab acts as a documentation place holder which describes briefly about the project
- Second Tab is a Dataset summary that will display the results of the data set
- Third Tab is a Prediction  tab that displays a small prediction example

DataSet Summary
=================================================================================================================

1. In this application mtcars and iris dataset examples are taken.
2. A SidePanel with controls to select a dataset, and no. of records to be fetched are used
3. Users can select one of the dataset and the number of records to be fetched ie n number of head/tail records.
(for this slider)
4. As per the selection, the DataSet Summary tab will display the results. 
5. for example, A user selects "iris" dataset and no of records = 5, displays the following


```
  Sepal.Length Sepal.Width Petal.Length Petal.Width Species
1          5.1         3.5          1.4         0.2  setosa
2          4.9         3.0          1.4         0.2  setosa
3          4.7         3.2          1.3         0.2  setosa
4          4.6         3.1          1.5         0.2  setosa
5          5.0         3.6          1.4         0.2  setosa
```


Prediction Summary
=================================================================================================================

1. In this application prediction of water consumption for a person is calculated based on the temperature and mowing time.
2. A Sidebar with controls to select a temperature, and no. of mowing time in hours are used.
3. As per the selection, the Prediction Summary tab will display the results.

For example, if the temperature were 90 degrees Fahrenheit and someone mowed for one and a half hours 
how much water would you estimate that they would want to drink during three hours outside?'

Once we have the Multiple regression equation, it is relatively straight forward to make predictions.

In this example, the regression equation was given by Water = - 122 + 1.51*Temperature + 12.5*Mowing Time
Now when we set temperature to 90 degrees and mowing for 1.5 hours as given in the example. 
Water= 32.65 oz. 

Thus we estimate that the person in the example would drink a little less than 33 ounces.

Conclusion
=================================================================================================================

Thus in this class assignment, we have learnt following :

1. Building and Deploying a Shiny Application.
2. Use Slidify for making runtime presentations.

Note: In this exercise, I have used
1. Slidify
2. Five pages
3. Hosted on github or Rpubs
4. Contains some embedded R code that gets run when slidifying the document i.e 1) one data set records and 2) A simple formula in the prediction sum. 

THANKS
