# BU1106 Task R Files

## Introduction

### Overview

We'll be working with R again. This time you get to work with script files.  

### Editing

You can create documents and edit them directly in GitHub's web interface. This is a very convenient way of creating and editing the files. 
In most cases, the preferred way of working is to create and edit the files on your own machine. 

This week we want to work in R Studio, so getting the file, i.e. the whole repository to your computer, will make your work so much easier. You do this, as discussed previously, using GitHub Desktop (**which is now available in the Application Catalogue!**) . 

## Task Explanation

Below is today's task. 

If you want to have another look at what we did previously you can [watch parts of the first R class on YouTube](https://youtu.be/UoAGqb1J4FQ) (you can even turn on subtitles).

**Commit early, commit often** - that way you can go back if you have made a mistake and I can see all the work you have done. It doesn't matter if your early commits contain mistakes.  

Once you are done be sure to commit your changes (that will save them to the repository) and to push them to GitHub (so that I can see the work you have done).

## Your Tasks

You have to work on these tasks by yourself. Please work on these tasks in RStudio. 
Pay attention to the auto complete options RStudio is offering you and use them to explore how R commands work. Also remember how useful the cursor keys and the Tab key can be. 
As shown in last week's class pressing F1 will bring up the documentation for the selected command in the Help tab. 

#### Task 1 

Set the correct Working Directory.

`Hint: I showed you how to do this in last week's class. It can be done with a command or through the GUI (Graphical User Interface).`

#### Task 2

`Background: A CSV file (CSV = comma-separated values) is a file that stores tabular data in plain text format. If you haven't worked with CSV files before you can imagine them as files similar to Excel files, but they are easy to handle and will work in many systems and with many programmes.`

The command to read a CSV file in R is read.csv(). Use RStudios built-in help to find out how to use this command and read the bt1005.csv file that came with this repository. Store it in the object bt1005.

#### Task 3

The names of the bt1005 columns don't look so great. This was a copy and paste mistake from before the csv file was created. Change the names of the columns to absence and grades.

`Hint: If you are not sure what the name of the command is try to remember what we did last week and the week before. We have used this command in both weeks.`

#### Task 4

Use the summary function to show result summaries of the bt1005 data frame. 

#### Task 5

Store the commands from Task 1-4 as an R Script. This allows you to run the commands again without having to type them all again, as shown in last week's class. 

You can start a new R Script with `File / New File / R Script`. 

Then add all your commands. 

Then save the file. Use an appropriate file name and the file extension `.R`.