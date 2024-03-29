# Overview

This guidebook describes the data and coding standards and processes we follow at the Aberdeen Centre for Health Data Science, that enable us to collaborate and create reproducible research.

It is being developed by existing team members, to help new members get started.

## Rationale

There are many exciting things to consider when starting a new health data science project. For example: What is the purpose of the project? What data do you need to answer your questions? What is the best type of visualisation that will allow you to convey your message? What is the most suitable statistical analysis?

The analysis, the visualisation - these are the fun and interesting aspects of the project, that you want to spend all your time doing. So you quickly create a folder called "project", put your data in a file called "data", and your analysis code in a file called "analysis". After a bit of work you save this as "analysis_2", because you've updated it but don't want to lose the original. When you receive an updated version of the input data, you realise that your analysis code no longer works, so you copy and paste the parts that do work into a new file what you call "new_analysis"...

By the end of the project you have a folder full of files with variations of similar, generic names that (hopefully) make perfect sense to you at that point in time. But it is completely unhelpful for everyone else, including yourself a few months into the future.

If you had just spent a bit more time organising your project in the beginning, choosing sensible names, keeping good track of your changes, documenting and testing your code, you would have ended up with a project that was not only useful to you just when you finished it, but for many years later, to you and other researchers.

But deciding how to organise a project, how to write tests and documentation is not only rather boring, but it's also not something researchers are taught how to do. That's why we are all tempted to skip it... So the point of this guidebook is to explain what you need to do and how to do it, to ensure your project can be used and reproduced by others. We hope you find it useful!

## Sections

Our guidebook is work in progress, and everyone is invited to contribute. The sections we have thought about including so far are:

* [Things to consider when planning your project](project-planning.md)
* [How to organise your project (to keep data, methods and outputs separate)](project-organisation.md)  
* [How to name your files (so they are human & machine readable, and can be ordered well)](filenames.md)
* [Data Storage and Backup](data-storage.md)
* [How to document your data (what information to include about the dataset creators, description, license, variables, etc.)](data-documentation.md)
* [Basic data quality control (what to use for missing values in datasets, standard checks on range of values, value types, number of expected observations, etc.)](data-quality.md)
* [Good practice for coding and collaboration](good-coding.md)
* [Resources for learning R](learn-R.md)
* [Publishing your project](publishing.md)

We are focusing on R, as it is a very commonly used programming language in data science. If you use a different language such as Python, it would be great to add some non-R resources!
