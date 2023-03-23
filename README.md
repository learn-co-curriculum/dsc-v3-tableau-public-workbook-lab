# Tableau Public - Tableau Workbooks Lab

## Introduction
Now that you have learned of the many features of Tableau, it is time to put that knowledge to work and create your first worksheet. In this lab, we will create a Tableau worksheet and generate a basic visualization that will express Profits by Sub-Category. Along the way, we will discuss Dimensions and Measures and how they are the building blocks of your visualizations.

To begin this lesson, you should have already:
1. Created a Tableau Public account and downloaded and installed Tableau Public.
2. Downloaded the Super Store Sales data set from Tableau Public's resources.

## Objectives
You will be able to: 
* Load a data set to Tableau and create a workbook
* Create a basic worksheet in a workbook
* Format and customize a basic Tableau visualization
* Save and publish the worksheet to Tableau Public

## Load Data and Create a Worksheet 

1. First, load the Superstore Sales dataset from the **Start page** via the **Connect Pane**. Now you have created a **Tableau workbook**.

2. Upon loading the data, Tableau will launch the **Data Source page**. Select the **Worksheet icon** from the sheets tab. Now you have created a new worksheet in the workbook.

3. Finally, populate the Data Source page by dragging the Orders table from the Left pane to the Canvas.

## Generate and Format Visualization
Now we will get a look at what Tableau can do. Suppose you are working for a big box store, and you have been tasked with visualizing some data from this dataset. For your first task, you simply need to create a bar chart that displays the _Profit_ earned by _Sub-Category_. 

1. A good first step here is to add _'Sub-Category'_ which is a **Dimension** to the **Columns** shelf and _'Profit'_, which is a **Measure** to the **Rows** shelf. Once you have these two elements in place, you should see a default graph shown for this data which turns out to be the bar chart you were tasked with creating.

<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson3/tab-1.png" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center> </div>
<br>

2. This looks great, but it is a little difficult to read the sub-categories at the bottom of the chart. 

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson3/tab-2.png" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center> </div>
<br>

One simple fix for this instance would be to swap the axes so the sub-categories become the rows and the profit becomes the columns. Find the swap-axis button and click it to see how it affects the visualization. 

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson3/tab-3.png" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center> </div>
<br>

3. That's a bit better, but now it looks cramped.  Tableau provides a menu option to change how the visualizations fit in the workspace. 
> You can find this **Fit** option in the top toolbar where it will display the _Standard_ view option.  Click on the drop-down menu and select _Entire View_ to stretch the visualization to fit the entire screen view.

<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson3/tab-4.png" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center> </div>
<br>

4. Great! Now that we have a good-looking bar chart, we can make it a little more informative. For instance, we would likely want the profit sorted so that it is easier to quickly find the highest or lowest profit-earning sub-categories. Fortunately, Tableau has a tool for this!
> Use the **Sort Descending** button in the toolbar and apply it to the bar chart. And, just like that, we have a graph that helps us to find the information we are looking for.

<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson3/tab-5.png" alt="This is the alt-text for the image." height=350/>
</td></tr></table>
            </center>
</div>

5. With so many sub-categories, it may be a bit difficult to connect the sub-category with the corresponding value.
> To fix this we can add some additional information to the graph. From the **Data Pane** drag _Sub-Category_ and _Profit_ one at a time and drop them on the _Label_ icon in the **Marks Card**.

<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson3/tab-6.png" alt="This is the alt-text for the image." height=350/>
</td></tr></table>
            </center>
</div>

6. You can change the type of visualization that is rendered with the **Show Me** menu in the upper right-hand corner.  

> There are a few important things to know about the Show Me pane:
> * The specific visualizations which can be rendered with the data you have dragged into the workspace will be highlighted and the others will be diffused in color. 
> * You will also notice at the bottom of the show me the menu, there are tips for which data types would be necessary to generate the selected graph.


<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson3/tab-8.png" alt="This is the alt-text for the image." style="height: 400px;"/>
</td></tr></table>
    </center> </div>
<br>

> Try changing the data that you have placed in the workspace and look at the different types of graphs available for the different data types. Once you change the visualization, you will need to adjust the display options such as the _Labels_.

## Customizing Your Worksheet

### Add a Title
Having a visualization is great, but we want to make it look professional and make it convey the information that is being shared by the visualizations. To do this, we will give the worksheet a meaningful title. 
1. The default name of the worksheet is the default name of the tab you are working in, but we can customize this. 
> If you right-click or double-click on the title of the visualization, which at the moment should be _Sheet1_, you will be able to change it. 
2. In the dialogue box that appears, you can see that the name of the worksheet is forced as the _&lt; Sheet Name&gt;_. 
> Change the name by simply replacing the default _&lt;Sheet Name&gt;_ with **"Profits by Sub-Category"**. Change the color to blue. 
3. Click _apply_ and _OK_ to save the changes.

<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson3/tab9.png" alt="This is the alt-text for the image." height=350/>
</td></tr></table>
            </center>
</div>

## Save and Publish to Tableau Public
Now that you have a basic visualization, you will want to share it with your stakeholders so they can see the work you have done. 

1. To do this, simply click on the **Save** icon in the top toolbar and follow the prompts.

2. If you have not connected your Tableau Public account yet, you will be prompted to sign in.

3. After authentication, you will be prompted for a name for the workbook. Name this workbook `learn-wb-YYYY-MM-XX`, where `YYYY` = Current year, `MM` = Current Month, and `XX` = your initials.

Now your workbook is uploaded and saved to Tableau Public!

## Summary
In this lab, we loaded a data set to Tableau and create a workbook. Then, we created a worksheet and formatted a basic Tableau visualization Finally, we saved and published the worksheet to Tableau Public.

Now that we have mastered the basics, we will explore some of the most essential data visualizations that you can create with Tableau. In the coming lessons, we will dive deeper into the more advanced features that Tableau has to offer.
