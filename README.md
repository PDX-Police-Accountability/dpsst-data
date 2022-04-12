# README

This repository holds publicly accessible data pulled the from [Oregon Criminal Justice Information Records Inquiry System (CJ IRIS)](https://www.bpl-orsnapshot.net/PublicInquiry_CJ/EmployeeSearch.aspx) pertaining to current and former members of the Portland Police Bureau.

CJ IRIS is one of many systems maintained by Oregon's [Department of Public Safety Standards & Training (DPSST)](https://www.oregon.gov/dpsst/pages/default.aspx).

Officer transcripts are pulled from CJ IRIS daily and stored in multiple formats in the [officers](./officers) directory:

* [markdown](./officers/markdown)
* [yaml](./officers/yaml)

Summary documents are created to help you find the transcripts you're looking for:

* [Sorted by DPSST identifier](./officers/summary/officer-transcripts-by-dpsst-identifier.md)
* [Sorted by name](./officers/summary/officer-transcripts-by-name.md)
* etc...

There are also downloadable tab-separated reports:

* [Officer transcripts](./officers/summary/officer-transcripts.tsv)
  * [Active officers only](./officers/summary/officer-transcripts-active.tsv)
  * [Inactive officers only](./officers/summary/officer-transcripts-inactive.tsv)
* [Officer training records](./officers/summary/officer-training-records.tsv) - NOTE this is a large file, likely over 25MB
