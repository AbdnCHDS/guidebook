---
title: "Data Documentation"
author: "BScheliga, CDBell"
date: "11/2020"
output: html_document
---

# Documentation and Metadata {#metadata}

Good research practice includes the provision of information about the data you have collected/generate and the research processes you have undertaken. This information is essential to ensure your research remains repeatable, transparent, discoverable and citable.  It may seem like an onerous task but the steps given below should bring you quickly towards having documentation on your project available in formats which can be read by humans and machines.  If you do not have a background in coding or data management do not fear! Help with this task is just an email away.  Contact either [Bernhard Scheliga](b.scheliga@abdn.ac.uk) or [Claire Bell](claire.bell@abdn.ac.uk).

## What is Metadata?

Metadata is "[...] the information we create, store, and share to describe things, allows us to interact with these things to obtain the knowledge we need." [Riley 2017](https://groups.niso.org/apps/group_public/download.php/17446/Understanding%20Metadata.pdf)

One problem is, the term metadata "[...] is used in so many different contexts and applied to so many different things that it sometimes seems to convey very little meaning."
[Day 2005](https://www.dcc.ac.uk/sites/default/files/documents/resource/curation-manual/chapters/metadata/metadata.pdf) 

This guide tries to avoid the more generic use of the term metadata as it can lead to confusion.  

So when the term 'metadata' is used, it refers simply to the schema used to **encode** the information, for example Dublin Core.

The term **documentation** will be used to refer to detail both about the project (its aims, coverage and methodology) as well as object level information (such as the file format of the resulting output of the project). To ease communication within ACDHS the following two terms are used to discuss the overarching information given about a research project:

## ACHDS Metadata Template
To encourage creation of high quality project and object level metadata, ACHDS has created a template for you to use throughout your project from inception to conclusion.  Although you might not be able to fill out the entire template at the beginning of the template, it is important that you start this work at the planning stage of your project.  It will help alert you to some of the decisions needing made, such as the creation of variable names to be used in data collection and, importantly, help keep track of these decisions.  In the long run, starting early can save alot of time and administrative burden.

The university's Data Librarian and the team of Data Stewards are available to help you as you work through this.  Once complete the librarian will take the free text entries and add controlled vocabularies and coding to the document and generate both a human readable 'Readme' file and a machine readable file. These two documents should accompany your data set in the repository of your choice and provide a helpful information to other researchers learning from your project or considering re-using your data.

To obtain a copy of the template form please contact either [Claire Bell](claire.bell@abdn.ac.uk) or [Bernhard Scheliga](b.scheliga@abdn.ac.uk).

## Use Controlled Vocabulary

***TO DO: Add examples for controlled Vocabulary***

If you are analysing secondary data, it is likely the variable names for your dataset will already have been created and defined.  However, if you are creating a new dataset, it is recommended that you use a Controlled Vocabulary when choosing the names for your data variables. This will mean that your dataset can be joined with other datasets using the same vocabulary with greater ease and much less work. So what is a controlled vocabulary?

"Broadly speaking, Controlled Vocabularies can range from a short list of clearly defined, mutually exclusive, and exhaustive terms, which are the only choices for usage in a specific context (e.g., populating certain DDI elements or attributes) through a classification to something as complex as a thesaurus with thousands of terms and term relationships." https://ddialliance.org/taxonomy/term/167

Once you have chosen a vocabulary to use to name your variables, please ensure that the choice is documented in the Dataset section of the ACHDS template.

Much of the information you provide at project level also benefits through use of controlled vocabulary.  The Data Librarian is happy to help you by converting the free text you have provided into vocabulary from controlled standards.
 
For example, for subject keywords, you can use a controlled vocabularl as well as free text.  It is recommended that terms provided by the [Library of Congress Authorised Subject Headings](https://authorities.loc.gov/cgi-bin/Pwebrecon.cgi?DB=local&PAGE=First) and [MESH medical subject headings](https://meshb.nlm.nih.gov/search) are used.

The language of a document can also be encoded using a standard. This aides discoverability on online searches. ISO 639-2 schema provides a list of internationally recognised codes for languages that can easily be understood by a computer.

## Creating a persistent identifier for your dataset and project
The creation of a persistent identifier (PID) for your dataset ensures that others can both cite and access your dataset. This is important as it helps you to show your contribution to research and increases the findability and accessibility of your data.  

A commonly used PID is the Digital Object Identifier (DOI). There are different ways to obtain a PID:
1. Many repositories automatically create a DOI for you when you deposit your dataset making this one less step to think about.
2. If your chosen repository does not create a DOI or other form of PID for you, you can enter your dataset into the university's repository using Pure. This will create a DOI for you without needing you to deposit your information in the respository.   For help entering a dataset into Pure, please contact the Copyright Librarian [Mary Mowat](mary.mowat@abdn.ac.uk).


## References
The preceding guidelines have been adapted from several sources, including:

* [Riley J,Understanding Metadata: What is Metadata, and What is it For?, National Information Standards Organization](https://groups.niso.org/apps/group_public/download.php/17446/Understanding%20Metadata.pdf)
* [Day M, (November 2005), "Metadata", DCC Digital Curation Manual, S.Ross, M.Day (eds)](http://www.dcc.ac.uk/resource/curation-manual/chapters/metadata/),Retrieved <date>
* [Cessda Documentation and metadata](https://www.cessda.eu/Training/Training-Resources/Library/Data-Management-Expert-Guide/2.-Organise-Document/Documentation-and-metadata)
* [Cornell University Guide to writing "readme" style metadata](https://data.research.cornell.edu/content/readme)
* [How to FAIR: metadata](https://howtofair.dk/how-to-fair/metadata/)
* [RDA COVID-19 Recommendations and Guidelines on Data Sharing](https://zenodo.org/record/3932953#.X3HHy-17mM9)
* [Clinical Data Interchange Standards Consortium](https://www.cdisc.org/standards)
* [UK Data Service:  Catalogue Metadata](https://www.ukdataservice.ac.uk/manage-data/document/metadata.aspx)