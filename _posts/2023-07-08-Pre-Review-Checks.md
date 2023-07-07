---
layout: post
title: Pre-review checks
subtitle: Before peer-review the data needs to be available somewhere, this guide explains the checks carried out by GigaScience Press staff prior to send the manuscript to peer-review
cover-img: /assets/img/checklist-banner.jpg
share-img: /assets/img/checklist-banner.jpg
tags: [curation, checklist]
---

## The current manuscript workflow

At present, we do a pre-peer-review data check of manuscripts at the request of the editorial team. The authors submit a manuscript, the editors look at it to check it meets journal policy and standard. If they think it is suitable for peer-review they flag it to the curation team to do what we call a "pre-review-data-audit" where we check for data availability prior to sending it to peer review.

## The process
One of the key statistics that matter for Editorial is the "time to first decision" which is the length of time from when the author clicks "submit manuscript", to the point where the editorial team give a first decision on that manuscript, that could be a reject (before review), or any of; reject, accept with minor changes, accept with major changes, or accept. The "get data" step for GigaDB falls within that time frame for anything that goes to review. This is why we try to keep the pre-review-data-audit (get data) stage brief.


Here we outline the generic process: 
* Check the Methods for clarity and expectation of what input/output files to expect to see.
* Check the results section for what results to expect to see.
* Check the Data Availability section for what they have already provided access to.
* Check the supplemental figures/tables/files for stuff that should be data files or that is a summary of data files.
* For data that has a suitable public repository, ensure that those data have been submitted there and have adequate access for reviewers, e.g. for Seq data, ensure the sequences have been submitted to the INSDC/SRA in a suitable format (i.e. de-multiplexed) and that they have provided reviewer access or made it public.


Our curators have a checklist of items that need to be completed to help ensure consistency over time, we include that checklist here so that you can make sure you are ready for any data requests that may result from it:


* Are there any GitHub Repositories associated with this manuscript?
   * If so, do they have OSI-approved licenses?
* Are all input, ouput, test and/or Benchmarking data for software papers publicly available from a stable repository?
   * If so, do they have relevant licenses?
* For Machine Learning papers have the DOME-ML annotations been provided to the DOME registry?
   * If so, what is the application number?
* Are any and all sequence data are available from INSDC (either public or by reviewer access)?
   * If so, what are the accession numbers & reviewer login details (if applicable).
* Is it likely that the data associated with this manuscript will need to be split into multiple datasets (e.g. full genome assemblies of multiple species would each require their own dataset)
* For Genome assembly papers, has BUSCO been applied?
   * If so, has the most recent version been used?
* Are there Additional Data DOI links (e.g. Zenodo) associated with this manuscript (if so, provide them)
   * If so, do they have a relevant open license?
* Do any of the Supplemental files submitted with the manuscript contain large data tables or other data that should be in GigaDB instead of with MS?
* For Imaging papers - are raw images suitable for submission to BioImage Archive or EMPIAR?
   * If not, are they available in a stable repository or will they be hosted in GigaDB?
* Does the MS involve ANY human sample data collection (sequences, images, questionaires, metabolomics etc.)?
   * If so, verify all ethics and consent forms have been collected. We should obtain a copy of consent form in private userbox and translating it to ensure its actually consent to publish data
   * If there are Human data generated as part of this study, where is that data shared? provide url and details of review access if available.
   * Has a second Curator or Editor confirmed the consent is suitable for GigaScience publication.
* Do any of the files associated with the manuscript use proprietary formats? 
   * If yes explain why thats OK, or if they need to be changed to an Open Format before acceptance.
* Compressed archive file supplied by authors have been unpackaged to check content.
* A readme file including file descriptions is available with dataset(s)


Once all of the checks have been completed and the curator is satisfied that the reviewer is able to access everything that maybe required to replicate the study then we send an email to the authors to confirm that we have completed the initial data checks. This email should include the full list of external locations of data items available from public sources, as well as the details of GigaDB private data location where the reviewers can access the additional data files provided.



