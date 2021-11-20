# Project organisation
The folder structure is designed from the ACHDS researcher perspective with Grampian Data Safe Haven (DaSH) elements incorporated as appropriate.  The folder names and overall structure would be the same across ACHDS and DaSH.

Further details of the contents of each folder can be found in the table at the bottom of this document.

## Projects not related to DaSH
* PrimaryResearchData
  * Data Documentation Template
* Methods
* ProcessedData
  * Data Documentation Template (updated from Primary Research Data template)
* PermissionsDocumentation
* ProjectRelatedInformation
* Outputs
  * Fake Datasets
  * Data Documentation Template for processed data or fake dataset if published
  * Publications

## DaSH Internal Structure (Modified structure for use within DaSH)
* DaSH_PrimaryResearchData  
  * DaSH_ Release_Folders (Repeatable)
  * DaSH_SummaryStatistics
  * DaSH_DataDocumentation
* DaSH_Methods
* DaSH_ProcessedData
  * Data Documentation Template for DaSH Processed Data (updated from file provided as part of primary data.)
* DaSH_Outputs

## DaSH Related Projects (Full structure for researchers)
* DaSH_PrimaryResearchData
  * DaSH_ Release_Folders (Repeatable)
  * DaSH_SummaryStatistics
  * DaSH_DataDocumentation
* PrimaryResearchData
* DaSH_Methods
* Methods
* DaSH_ProcessedData
  * Data Documentation Template (updated from file provided as part of primary data.)
* ProcessedData
* PermissionsDocumentation
* ProjectRelatedInformation
* DaSH_Outputs
* Outputs
  * Fake Datasets
  * Data Documentation Template for processed data or fake dataset if published.
  * Publications

## Folder Contents & Associated Terminology
|Folder | Contents |
|------------ | -------------|
|DaSH_SummaryStatistics | Information that can be directly extracted from the dataset. For example, names of variables, range of variables and a note of missing data.  <br/>(Please note that the range is based on information in the dataset itself, so any errors in the dataset could lead to errors in the intended range.) <br/>Formerly known as ‘DaSH_Metadata’. |
|DaSH_DataDocumentation | Readme File and/or Data Documentation Template for Primary Data.<br/>See: https://github.com/AbdnCHDS/DataDocumentationTemplate  
|DaSH_Methods | Code and documentation |
|DaSH_Outputs | Data given to DaSH by the researcher after analysis, checked by DaSH and turned into an ‘output’. This means it can come out of the Safe Haven and put in the researcher folder. |
|DaSH_PrimaryResearchData | Data which is not yet processed by researcher.<br/>Data processed and linked by DaSH and then released to researchers – Files not to be amended. May be versioned as the researcher and analyst clarify what information is needed and updates are provided. |
|DaSH_ProcessedData | Files prepared by the researcher for transferring out of the Safe Haven.  DaSH team check the files and then transfer them. |
|DaSH_ Release_Folders | One folder per release usually associated with a date.<br/>Release folders may each need their own Metadata and Definitions subfolders as the merging of datasets is sometimes done by analysts and sometimes done by researchers.<br/>A Release = anything put in a folder on behalf of a researcher. The file given to the researcher as an output.  Might be a linkage of many datasets from different points and is merged.
|Methods | Code and documentation |
|Outputs | DaSH Outputs worked on by researcher.  Final version for publication. This folder only lives outside of DaSH. |  
|PermissionsDocumentation | For example, North Node Privacy Advisory Committee (NNPAC), Privacy and Public Benefit Panel (PPBP).<br/>NNPAC is an example of a “local” permissions body (LPAC) and PPBP is an example of a national permissions provider. |
|PrimaryResearchData |Data not sourced from DaSH. Files not to be amended. |
|ProcessedData | Data that has been processed by the researcher, for example, cleaning prior to analysis.|
|ProjectRelatedInformation | Grants etc., financial records, important emails, private information. |

### [Next: Naming files](filenames.md)
[Previous: Project planning](project-planning.md)

[Index](index.md)
