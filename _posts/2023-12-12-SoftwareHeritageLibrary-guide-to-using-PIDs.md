---
layout: post
title: Software Heritage Library (SHL)
subtitle: Guide to using the Software Heritage Library (SHL) SWHIDs in Giga papers (and GigaDB).
cover-img: /assets/img/SWHID-banner.png
share-img: /assets/img/SWHID-banner.png
tags: [GitHub, Software, SWHID, PID]
comments: true
---

# Guide to utilising Software Heritage Library (SHL)

In cases where the only thing that would go into a GigaDB dataset is the GitHub snapshot then we should NOT create a dataset page. Instead we should ensure that the GitHub repo is in SHL and cite the PID given by the exact version.

For example, if we published a paper about GigaDB.org, and wanted to include the repository in the paper;
1. Goto https://www.softwareheritage.org/ 
2. Under the menu heading "Archive" select the button "Save Code Now" which takes you here: https://archive.softwareheritage.org/save/
3. Pick the origin type as "git" (this can be used for GitHub or GitLab)
4. Then copy and paste the URL of the relevant repository that you want to add to the SHL, in this example we want the GigaDB website repo https://github.com/gigascience/gigadb-website
5. Click "Submit"
You will see the notification : 
~~~
The "save code now" request has been accepted and will be processed as soon as possible.
~~~
6. Find the status of that request by browsing the save code requests: https://archive.softwareheritage.org/save/list/
7. What for the status to be "Succeeded", it has then been saved to SHL and you can click the link in the URL column of that table to take you to the archived page, in this example it is:
https://archive.softwareheritage.org/browse/origin/directory/?origin_url=https://github.com/gigascience/gigadb-website&timestamp=2023-12-11T08:11:03.622289%2B00:00
8. On that page, look on the right hand side, there is a pull out tab called "Permalinks", click that.
9. Select the "Snapshot" tab within the permalinks:
10. Then click the copy permalink button , e.g. copy 
https://archive.softwareheritage.org/swh:1:snp:dcf6d006361fca8e099de2ab7f5c9d5033d867af;origin=https://github.com/gigascience/gigadb-website
OR you can remove the last part of the URL after the ; as that is just human readable metadata and not required as part of the PID.
11. you can create a full data citation string using that URL combined with the authors (repository owners, or associated publication authors if there is one), following the standard reference guidelines of the relevant journal or publisher, e.g. for a GigaScience reference this would look something like:
SSoftware with persistent identifier (Software Heritage)
Fang S, Cao L, Yang C, Hu L et al. (2023) SGAE: Deciphering spatial domains from spatially resolved transcriptomics with Siamese Graph Autoencoder (Version 1). [Computer software]. Software Heritage, https://archive.softwareheritage.org/swh:1:snp:19c3ac3c492b5b4c6aca5451eeea9efb52a3ad9d;origin=https://github.com/STOmics/SGAE


Additionally, they offer a Widget iframe view (example below), which we should be able to include in GigaDB or in GigaByte. 

<iframe style="width: 100%; height: 500px; border: 1px solid rgba(0, 0, 0, 0.125);"
        src="https://archive.softwareheritage.org/browse/embed/swh:1:dir:e894fed8e927eec1eda9080f9db475b8b4c68dd7;origin=https://github.com/gigascience/gigadb-website;visit=swh:1:snp:dcf6d006361fca8e099de2ab7f5c9d5033d867af;anchor=swh:1:rev:cc89605c6bd7fc208d8221c76fa21932b6578291/">
</iframe>

