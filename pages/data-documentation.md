# Documentation and Metadata

[![Watch the video](https://img.youtube.com/vi/N2zK3sAtr-4/hqdefault.jpg)](https://www.youtube.com/watch?v=N2zK3sAtr-4)

Good research practice includes the provision of information about the data you have collected/generated and the research processes you have undertaken. This information is essential to ensure your research remains repeatable, transparent, discoverable, citable and can be carried further by yourself or others at a later date. It may seem like an onerous task but the steps given below should bring you quickly towards having documentation on your project available in formats which can be read by humans and machines. If you do not have a background in coding or data management do not fear! Help with this task is just an email away: please contact [Bernhard Scheliga](b.scheliga@abdn.ac.uk).

## What is Metadata?

Metadata is:

> [...] the information we create, store, and share to describe things, allows us to interact with these things to obtain the knowledge we need." [Riley 2017](https://groups.niso.org/apps/group_public/download.php/17446/Understanding%20Metadata.pdf)

> One problem is, the term metadata "[...] is used in so many different contexts and applied to so many different things that it sometimes seems to convey very little meaning.
[Day 2005](https://www.dcc.ac.uk/sites/default/files/documents/resource/curation-manual/chapters/metadata/metadata.pdf)

This guide uses the term metadata to refer to the contextual information given to support the sharing and publication of datasets. The term metadata will also be used in conjuction with the term 'documentation' to ensure clarity. Both terms will refer to detail about the project (its aims, coverage and methodology) as well as object level information (such as associated files and variable name definitions).

## ACHDS Metadata Template
To encourage creation of high quality project and object level metadata, ACHDS has created a template for you to use throughout your project from inception to conclusion.  Although you might not be able to fill out the entire template right at the start, an early start is important.  It will help alert you to some of the decisions needing made, such as the creation of variable names and, importantly, help keep track of these decisions.  In the long run, starting early can save alot of time and administrative burden.

The university's Data Librarian and the team of Data Stewards are available to help you as you work through this.  This documents should accompany your data set in the repository of your choice and will provide helpful information to other researchers.

For a copy of the template form please click here:  [Metadata_Template](https://github.com/AbdnCHDS/DataDocumentationTemplate)

## Use Controlled Vocabulary

If you are analysing secondary data, it is likely the variable names for your dataset will already have been created and defined.  If this has come to you without a list of definitions for the terms used, you will appreciate the importance of providing a dictionary along with the dataset to enable it to be understood!

However, if you are creating a new dataset, you will be choosing your own variable names.  It is recommended that you use a controlled vocabulary to do this. Much of the information you provide at project level also benefits through use of controlled vocabulary.  Some benefits of using a controlled vocabulary are:
* It will enable others to quickly understand the definition and scope of the terms you use
* It will enable your dataset to be merged with other datasets using the same vocabulary with greater ease
* Your work becomes more findable by search engines. (Someone else has done the magic behind the scenes that enable computers to read and understand your terms and match it with search terms or other datasets.  You just need to use the words.)

So what is a controlled vocabulary?

>"Broadly speaking, Controlled Vocabularies can range from a short list of clearly defined, mutually exclusive, and exhaustive terms, which are the only choices for usage in a specific context (e.g., populating certain DDI elements or attributes) through a classification to something as complex as a thesaurus with thousands of terms and term relationships." https://ddialliance.org/taxonomy/term/167

Once you have chosen a vocabulary, please ensure that the choice is documented in the metadata template or whatever form of accompanying documentation you choose.  You may need to use more than one controlled vocabulary for different aspects of your project.  It is  a good idea to use vocabularies supported by a strong community so that you can rest assured that both the terms themselves and the technical work behind the scenes is kept up to date.

The Data Librarian is happy to help you by converting the free text you have provided into vocabulary from controlled standards.

Examples of controlled vocabularies (aka ontologies - we won't split hairs about the differences here):

* [Biomedical ontologies from the European Bioinformatics Institute](https://www.ebi.ac.uk/ols/index)
* [Bioportal](https://bioportal.bioontology.org/search?q=ICD&ontologies=&include_properties=false&include_views=false&includeObsolete=false&require_definition=false&exact_match=false&categories=)
* [University of Aberdeen, Health Services Research Unit - Glossary](https://www.abdn.ac.uk/hsru/what-we-do/qa/glossary-141.php)
* [LOINC - Logical Observation Identifiers Names and Codes](https://www.mayocliniclabs.com/test-catalog/appendix/loinc-codes.html)
* [MESH - U.S. National Library of Medicine Medical Subject Headings](https://meshb.nlm.nih.gov/search)
* [ICD-11 for Mortality and Morbidity Statistics](https://icd.who.int/browse11/l-m/en#/http%3a%2f%2fid.who.int%2ficd%2fentity%2f1435254666)
* [Library of Congress Authority Headings - Broad range of headings including life sciences](https://authorities.loc.gov/cgi-bin/Pwebrecon.cgi?DB=local&PAGE=First)
* and for the non-medical amongst us:  [Dictionaries from the British Geological Survey](https://www.bgs.ac.uk/information-hub/dictionaries/)

### [Next: Data quality](data-quality.md)
[Previous: Data storage](data-storage.md)

[Index](index.md)
