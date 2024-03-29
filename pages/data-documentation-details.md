# Data Documentation Details

## Citing stuff
https://guides.lib.umich.edu/c.php?g=439304&p=2993299


## Metadata Issues for Discussion

### What do we mean by the term?

Metadata is such an all encompassing term. 'Data about data' could be just about anything.  So within ACHDS we need a short hand way to know what people are referring to when they use the term 'metadata'.  A common approach to this is to divide the term into categories.

(HowToFair - Denmark)[https://howtofair.dk/how-to-fair/metadata/]
_We distinguish between three main types of metadata:  
    **Administrative metadata** are data about a project or resource that are relevant for managing it; for example, project/ resource owner, principal investigator, project collaborators, funder, project period, etc. They are usually assigned to the data, before you collect or create them.  
    **Descriptive or citation metadata** are data about a dataset or resource that allow people to discover and identify it; for example, authors, title, abstract, keywords, persistent identifier, related publications, etc.  
    **Structural metadata** are data about how a dataset or resource came about, but also how it is internally structured. Structural metadata describe, for example, the unit of analysis, collection method, sampling procedure, sample size, categories, variables, etc. Structural metadata have to be gathered by the researchers according to best practice in their research community and will be published together with the data. Descriptive and structural metadata should be added continuously throughout the project._

(Cessda)[https://www.cessda.eu/Training/Training-Resources/Library/Data-Management-Expert-Guide/2.-Organise-Document/Documentation-and-metadata]
_The **project-level** documentation explains the aims of the study, what the research questions/hypotheses are, what methodologies were being used, what instruments and measures were being used, etc.
**Data-level or object-level** documentation provides information at the level of individual objects such as pictures or interview transcripts or variables in a database. You can embed data-level information in data files. For example, in interviews, it is best to write down the contextual and descriptive information about each interview at the beginning of each file. And for quantitative data variable and value names can be embedded within the data file itself._

(RDA IG Metadata)[https://www.rd-alliance.org/groups/metadata-ig.html]
_metadata modalities of description, restriction, navigation, provenance, preservation and the use of metadata for the purposes discovery, contextualisation, validation, analytical processing, simulation, visualisation and interoperation._

(UK Data Service use DDI)
_"* **study description** - information about the context of the data collection such as bibliographic citation of the study and data, scope of the study (topics, geography, time), methodology of data collection, sampling and processing, data access information, and information on accompanying materials
* **data file description** - information on data format, file type, file structure, missing data, weighting variables and software
* **variable descriptions**"_

##there are a number of standards, that we can follow:  Dublin Core, Data Catalog, DataCite, Schema??

Standards to make our resource findable on the website.
Standards to make our data more easily shared, such as use of controlled vocabulalies and research coding.

Dublin Core https://dublincore.org/
Data Documentation Initiative (DDI) https://ddialliance.org/
Datacite Schema https://schema.datacite.org/meta/kernel-4.3/

## Current Standard

Currently we are following the Dublin Core
"A basic, domain-agnostic standard which can be easily understood and implemented, and as such is one of the best known and most widely used metadata standards.

Sponsored by the Dublin Core Metadata Initiative, Dublin Core was published as ISO Standard 15836 in February 2009." [Source] (https://www.dcc.ac.uk/resources/metadata-standards/dublin-core)


## XML vs. RDF for publishing metadata 'readme' file?

##Clinical Data Standards - not really for documentation about the project rather guides for the researchers as they record their questions and results.
* (CDISC Clinical Data Interchange Standards Consortium)[https://learnstore.cdisc.org/Home/index] Hard to get an overview of.  Training costs money.  Not quite sure what sort of thing the standards apply to.
* (HL7 FHIR Fast Healthcare Interoperability Resources)[https://www.hl7.org/fhir/overview.html]


## Which controlled vocabulary?
*Administrative terms*:  
* [CESSDA Vocabulary for describing data elements](https://vocabularies.cessda.eu/#!discover) e.g. analysis unit, data type, mode of collection, etc.
* [https://ddialliance.org/controlled-vocabularies](https://ddialliance.org/controlled-vocabularies)  Difference between this and CESSDA?

*Subject terms*:  
* [Library of Congress Authorised Subject Headings](https://authorities.loc.gov/cgi-bin/Pwebrecon.cgi?DB=local&PAGE=First)  In use in library already
* [MESH medical subject headings](https://meshb.nlm.nih.gov/search) are used.
* [International Classification of Diseases (ICD)](https://www.who.int/classifications/icd/en/)
* [Systematised Nomenclature of Medicine Clinical Terms (SNOMED CT) ](http://www.snomed.org/)  Expensive

*Identifiers for health measurements and observations*:
* LOINC (Logical Observation Identifiers Names and Codes)  "LOINC is a common language (set of identifiers, names, and codes) for identifying health measurements, observations, and documents. If you think of an observation as a "question" and the observation result value as an "answer."  LOINC provides the code for the question.

*Languages*:  
* Library of Congress ISO 639-2
* SIL ISO 369-3

*Country codes*:
* [ISO-3166](https://www.iso.org/obp/ui/#search)

and LOINC (Logical Observation Identifiers Names and Codes).

*Data Type*:
[DDI Alliance Controlled Vocabulary for Data Type @ Cessda](https://vocabularies.cessda.eu/vocabulary/DataType?lang=en)
**String** Finite sequences of characters.
**NormalizedString**Type of string in which any occurrence of whitespace (including tabs, line feeds, and carriage returns) is replaced by a single space.
**Boolean** True or false. Can be represented by 1 and 0 correspondingly.
**Decimal** A subset of real numbers, which can be represented by a finite-length sequence of decimal digits (0-9) separated by a period as a decimal indicator. An optional leading sign is allowed. If the sign is omitted, "+" is assumed. Leading and trailing zeroes are optional. If the fractional part is zero, the period and following zero(es) can be omitted. For example: -1.23, 12678967.543233, +100000.00, 210.
**Integer** Whole numbers, the infinite set of integers, no minimum or maximum value.
**DateTime** Integer-valued year, month, day, hour and minute, plus decimal-valued second property, and time zone hour and minute (e.g., 2002-10-10T12:00:00-05:00).
**Time** Left-truncated dateTime, e.g., 13:20:00-05:00 (1:20 pm for Eastern Standard Time U.S.).
**Date** Integer-valued year, month, day, and time zone hour and minutes, e.g., 2003-06-30-05:00 (30 June 2003 Eastern Standard Time U.S.).


_Removed from draft of guidebook_

***NOTE:*** follow the *dumb-down*- & *one-to-one*- princinple
*dumb-down*-princinple: leave out what is not needed
*one-to-one*- princinple:

## Human readable metadata - A Readme file
Create a simple Readme document to accompany your dataset in the repository.  Use a plain text file wherever possible and avoid using proprietary formats.  This will aid sharing.
Name the Readme file so that it is easily associated with the data file(s) it describes.
Keep the layout of the document clear so that it is easy to understand, (e.g avoid lengthy paragraphs).
The content section below outlines the type of information to include.

## Metadata for machines
You will also need to create another information file but this time for machines rather than humans.  There are a range of metadata standards available to enable you to do this.  

Dublin Core is an example.  It is a domain agnostic, basic and widely used metadata standard.

Fortunately there is choice of tools available to help you create the appropriate metadata in a machine readable format.  This will save you having to learn new metadata standards and controlled vocabularies.
*[Dublin Core Metadata Generator](http://nsteffel.github.io/dublin_core_generator/)
