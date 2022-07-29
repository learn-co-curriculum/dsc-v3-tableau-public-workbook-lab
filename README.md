# Tableau - Customizing Worksheets - Lab

## Introduction
Now that you have gotten a taste of some of the features Tableau has to offer, it is time to put that knowledge to work and test out the features. To ensure that you will be working with the correct data set, we have provided the file for you. Click on the _Superstore Excel File_ link below to download the file if you do not have it from the previous lesson.

<a href="https://github.com/learn-co-curriculum/dsc-tableau-customizing-worksheets-lab/raw/main/data/sample_superstore.xls" download target="_blank" download="sample_superstore.xls">Superstore Excel File</a> 

## Objectives
You will be able to: 
* Change and apply _Color_ and other attributes of the _Color_ card
* Add customized descriptive information using _Label_ and _Tooltip_
* Customize the color, size, and font of various components of the viz

## Load the Data
To start on this lab, you will need to open _Tableau Public_ and load the data. In this lab we will use the _Orders_ sheet again, so you will need to select that sheet and drop it into your workspace. Once you have loaded the data and selected the _Orders_ sheet, we are ready to create a basic viz to apply our these new customization tools to.

## Create the Viz
Now that you have the data, create a bar chart of total sales by _Sub-Category_. Your chart should look like the one below.

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/bar_chart_lab.png" alt="Image of what the bar chart should look like" height="350px">

## Customize the Title
The default title of the worksheet is the name of the worksheet which was assigned by Tableau to be _Sheet 1_. This title does not help the viewer understand what information you are attempting to convey, so you will want to change it to something more descriptive. There Are two ways you can change it, one is to rename the _Sheet 1_ tab in the bottom of the interface, which is as simple as right clicking on the tab and selecting _Rename_. Change the name of the sheet now to something that will help you in a presentation, such as _Profit Bar Chart_. This method will accomplish the task, but you'll notice that the _Title_ has now changed as well. What if you want the tab name and the title to be different? In this case, you can simply navigate to the _Title_ in the workspace and right click on it and select _Edit Title.._ The window that pops up will allow you to customize the _Title_ however you wish. Notice that the field for the text of the title is populated with __&lt;Sheet Name&gt;__, this gets the title from the name in the worksheet tab at the bottom of the workspace.

Click into the text field and change the name to something more descriptive like _"Profit by Sub-Category"_. At this point, you can change the _color, font, size, and justification to whatever you like to improve the aesthetics of the viz. Aside from any color, or font changes you decided to add, your title should now look something like the one below.

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/title_lab.png" alt="Image of the title after changing the name" height="50px">

You can find more customization options in the menu bar at the top of the workspace under _Format>Title and Caption_. Get creative and make your title look great for the viewer.

## Adding in Some Color
The viz you have this far is a bit monochromatic and does not help to highlight any of the data. Suppose your stakeholders would like to easily see which category is at the top of the profit scale. At the moment, we can only see the _Profit_ by _Sub-Category_. Use the _Color Card_ to color each _Sub-Category_ by _Category_. Get creative and set the _Color Palette_ to what you like. Once you have done that, make the viz a little more organized by sorting the data in _Descending_ order. Once you have done this, your viz should look something like the one below.

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/color_sort_lab.png" alt="Image of the viz with the color and sort changes applied" height="450px">

## Adding Descriptive Information
Because the negative numbers move the other bars away from the axis, it may be difficult for the viewer to associate the correct bar with the label. Use the _Label_ card and add some labels to the bars so each bar shows the _Sub-Category_ and _Profit_. Currency values such as _Profit_ are not formatted as currency by default, add a `$` before the value in the _Profit_ label.

Let's make the _Sub-Category_ stand out by increasing the font and making the text __bold__. Feel free to take some artistic license here and use all of the features to make the labels look pleasing. Once you have done these tasks, your viz should look something like the one below.

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/label_lab.png" alt="Image of the viz with the addition of labels and label formatting." height="450px">

## Adding Additional Information
The labels have some good information, but your stakeholders may want to know the _Sales_ of a certain category while looking at the _Profit_. This can be done by adding the _Sales_ measure to the _Tooltip_ card. Add the _Sales_ to the _Tooltip_ and format the _Tooltip_ so that _Category_ is larger than the others, and make it __bold__. Let's change the name of the _Category_ label to _Department_ to align with the wishes of our stakeholder. Our stakeholder also likes the _Profit_ numbers to be __italicized__, so let's make that change as well, and while we are at it, we need to add in the `$` for the currency values. Once you make these changes your _Tooltip_ should look like the one below.

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/tooltip_lab.png" alt="Image of the tooltip with the changes applied" height="150px">

## Final Product
After making all of the changes and customizations, you now have a much more informative and user friendly visualization that will provide the necessary information to all who view it.  Below is an example of the completed viz from this lab.  Yours should look similar, but may be different due to choices you made on some of the customizations. 

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/finished_lab.png" alt="Image of the final product of all of the changes and customizations made in this lab" height="450px">

## Summary
Part of making a useful visualization is ensuring that you highlight the necessary information. In this lab you were able to apply many of the tools Tableau has to offer to customize you viz and make it fit your specific use case. Now that you know the basics of Tableau, we will dig deeper into the many other visualizations and features Tableau has to offer.
