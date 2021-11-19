# Naming files

There are three main principles for good file names. They should be:

**1. Human readable**

+ Choose names that are related to the content of the file. Is it a file of demographic data? Don't call it "my data.csv". Call it "demographics.csv".
+ Use hyphens "-" to separate words so the file names are easier to read. For example, if you have a file with code that loads and cleans your demographic data, you could call it "load-clean-demographics.r". It's easier than "loadcleandemographics.r". And it's definitely more relevant than "my data analysis.r"

**2. Machine readable**

+ Avoid spaces, punctuation, and any unusual characters.
+ Use underscores "_" as delimiters to separate units of metadata. For example, if you have data from different groups, dates and clinics in separate files, you have three units of metadata (group, date and clinic), and a good file name would be: "2020-08-04_group01_clinic04.csv"  

**3. Sortable**

+ If you have a date in your file name, put the date first, and make sure it's in the YYYY-MM-DD standard, so your files are ordered chronologically.
+ If you have numbers, pad with zeros (01,02,...,09,10,11,... instead of 1,2,...,9,10,11,...) to make sure they are ordered correctly.

### [Next: Data Storage](data-storage.md)
[Previous: Project organisation](project-organisation.md)

[Index](index.md)
