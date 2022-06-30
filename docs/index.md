---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

Data on this site is pulled from [Oregon Criminal Justice Information Records Inquiry System (CJ IRIS)](https://www.bpl-orsnapshot.net/PublicInquiry_CJ/EmployeeSearch.aspx).

CJ IRIS is one of many systems maintained by Oregon's [Department of Public Safety Standards & Training (DPSST)](https://www.oregon.gov/dpsst/pages/default.aspx).

Currently, data is pulled daily from CJ IRIS for current and former employees of the Portland Police Bureau.

A current summary/roster of active and inactive PPB employees is [here]({{ site.baseurl }}/content/ppb-roster).

TODO:

1. Automate scanning to find new DPSST numbers associated with PPB
2. Build rosters for the other agencies in Oregon
3. Output a daily change document created from the git diffs
4. Add created/modified timestamps to all the visible pages (relevant info is all in git)
5. Scrape the [DPSST Professional Standards/Economic Sanctions Database](https://www.oregon.gov/dpsst/cj/pages/cases.aspx) and link officers by DPPST number
