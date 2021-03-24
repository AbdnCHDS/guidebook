---
title: "Getting started"
author: "DBlana"
date: "23/07/2020"
output: html_document
---

# Getting started

## Naming files and folders {#names}

There are three main principles for good file names. They should be:

**1. Human readable**

+ Choose names that are related to the content of the file. Is it a file of demographic data? Don't call it "Dimitra's data.csv". Call it "demographics.csv".
+ Use hyphens "-" to separate words so the file names are easier to read. For example, if you have a file with code that loads and cleans your demographic data, you could call it "load-clean-demographics.r". It's easier than "loadcleandemographics.r". And it's definitely more relevant than "Dimitra's data analysis.r" 

**2. Machine readable**

+ Avoid spaces, punctuation, and any unusual characters.
+ Use underscores "_" as delimiters to separate units of metadata. For example, if you have data from different groups, dates and clinics in separate files, you have three units of metadata (group, date and clinic), and a good file name would be: "2020-08-04_group01_clinic04.csv"  

**3. Sortable**

+ If you have a date in your file name, put the date first, and make sure it's in the YYYY-MM-DD standard, so your files are ordered chronologically.
+ If you have numbers, pad with zeros (01,02,...,09,10,11,... instead of 1,2,...,9,10,11,...) to make sure they are ordered correctly.



## Project organisation {#folders}

There are many ways to organise your project, but the main recommendation is to keep input data, methods and outputs separate. So the main folder structure should reflect this.

**1. Inputs**

The Inputs folder contains:

+ Input data
+ A metadata file, which is a file that describes the data, for example who created it, when, usage rights, etc. [See chapter on data documentation](#metadata).
+ A definitions file, which explains what each variable in the dataset is

<div class="warning">
<p>It might not be possible to include your actual input data in your project folder.</p>
</div>

This could be because: 

+ It is too large, and it is stored somewhere else online, so there is no reason to copy it locally. In that case, you need to include a clear explanation of where the data is stored, and what you need to do to access it (for example, you may need to create an account). It would be great to include a small subset of the data, to demonstrate what it looks like, and to allow you to develop and test your analysis code on it without having to access the remote data.
+ It is private and cannot be publicly shared (you have permissions to access it in a secure environment such as the Grampian Data Safe Haven). In that case, create a dummy dataset that contains the same variables as the real dataset, but fake data. The purpose of this is again to demonstrate what the real data looks like, and allow you to develop and test your analysis code.

**2. Methods**

The Methods folder contains:

+ Analysis code, including code to input and test the quality of your input data. See [chapter on data quality](#dataquality).
+ Documentation of code. It is possible to combine code and documentation in a single document, using tools such as [R Markdown](https://rmarkdown.rstudio.com/){target="_blank"}. See chapter on code documentation.
+ Code tests, to make sure your code does what you want it to do. See chapter on code testing.

**3. Outputs**

Outputs may be different for each project, depending on the project aims. They could be:

+ A manuscript for publication, including figures, bibliography, etc.
+ A new dataset, which needs to be accompanied by a metadata file and a definitions file, and short examples of code for accessing and using the new dataset
+ A new computer model or analysis method, which should include documentation and examples of use

<div class="info">
You can create your folder structure on your local computer, but you need a good backup system, and you also need to keep your code under version control (which means keeping track of changes you make). So we recommend you create your project as a Github repository. See chapter on version control.  
</div>