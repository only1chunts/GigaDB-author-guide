---
layout: post
title: GigaDB curator training material
subtitle: 
cover-img: /assets/img/.jpg
thumbnail-img: /assets/img/.jpg
share-img: /assets/img/.jpg
tags: [curation, GigaDB, ]
---
# GigaDB training

Table of Contents

[Introduction	2](#_toc140661939)
[General understanding of principles of data publishing.	2](#_toc140661940)
[Recommended reading:	2](#_toc140661941)
[How GigaScience and GigaDB fit into the data publishing landscape	2](#_toc140661942)
[Recommended reading:	3](#_toc140661943)
[GigaDB mission	3](#_toc140661944)
[Data review	3](#_toc140661945)
[Data availability check (Pre-manuscript review)	5](#_toc140661946)
[Worked example of the Initial Data Availability Check step:	6](#_toc140661947)
[Your turn	7](#_toc140661948)
[Suggested file list	8](#_toc140661949)
[Full data assessment (Post-manuscript review)	9](#_toc140661950)
[Data publishing	9](#_toc140661951)
[The role of GigaDB curators	10](#_toc140661952)
[Video transcripts:	11](#_toc140661953)
[YouTube video describing the importance of data sharing	11](#_toc140661954)




# <a name="_toc140661939"></a>**Introduction**
## <a name="_toc140661940"></a>**General understanding of principles of data publishing.**
A key foundation needed to support reproducible research is the proper handling of research outputs. There are a number of best practices and tools available to researchers to ensure that their data is sufficiently FAIR (Finable, Accessible, Interoperable, and Reusable), all of which require the publication of data in some way.

The peer review process of the standard narrative text of more traditional publishing has been demonstrated to be fallible with many examples of false publications being made to aid financial gains of the authors. The additional step of publishing the data associated with the traditional narrative makes the publication of false or made up manuscripts more difficult for authors, therefore promoting trustworthiness of the journal.

For the authors, data publishing can aid uptake of the associated manuscript with one study estimating an increased citation rate of 20% (<https://doi.org/10.7717/peerj.4375>) for manuscripts that also share the data openly. In addition, the explicit open sharing of data can also lead to more collaborations for the authors.

The FAIR (<https://doi.org/10.1038/sdata.2016.18>) movement has been instrumental in promoting the best practices in open data publishing and sharing, with almost all open data repositories aiming to meet the FAIR principles.

#### <a name="_toc140661941"></a>*Recommended reading:*
<https://www.go-fair.org/fair-principles/>  The FAIR website describing the FAIR principles

<https://web.archive.org/web/20180331100123/https://www.youtube.com/watch?v=8Sg536Rgbjk&gl=US&hl=en> Youtube video describing the importance of data sharing (transcript of video is included at the bottom of this thread)

<http://datadryad.org/pages/reusabilityBestPractices> Dryad’s best practices guidelines

<http://www.repronim.org/module-FAIR-data/00-Introduction-to-Module/> A tutorial on data sharing for Neuroscience. Introduction and Lessons 1,2, 3 only (NB. lessons 4 and 5 are more in depth that required here but feel free to look through them anyway!)

<https://data.mendeley.com/archive-process>


### <a name="_toc140661942"></a>**How GigaScience and GigaDB fit into the data publishing landscape**

GigaScience started GigaDB in 2011, it was the first journal to start its own repository for the storage of data associated with its manuscripts, and indeed was launched around the same time as FigShare. Prior to 2011 there were a number of topic specific databases such as those hosted by the NCBI and EBI, but very few general purpose repositories. 

GigaDB is still unique in that we manually curate all datasets to ensure they contain all necessary and sufficient data and metadata in relation to the linked manuscript.


#### <a name="_toc140661943"></a>*Recommended reading:*
The GigaDB announcement paper <https://doi.org/10.1186/2047-217X-1-11> 

The most recent GigaDB paper <https://doi.org/10.1093/database/baz016>

## <a name="_toc140661944"></a>**GigaDB mission**

GigaDB aims to be the primary body of well curated and indexed life science data associated with any open access publication. Initially started as the host repository for GigaScience journal article datasets we aim to expand this to offer our services to any authors publishing their manuscripts in any open access journal. 

The close collaboration with GigaScience will continue with the journal article processing costs covering the inclusion of data in GigaDB. For manuscripts being published in other journals we will initially be offering the GigaDB services for free to gauge levels of interest, after a set period of time we will need to review the funding and usage to set an appropriate Data Publication Charge (DPC) that will be charged for our services. 

The aim is to provide datasets that are sufficient to enable readers to reproduce the work published in the associated article. To accomplish this it is necessary for authors to have a complete manuscript ready for assessment (data review) by our curators to allow us to ensure the data is sufficient.

## <a name="_toc140661945"></a>**Data review**
The most important part of the GigaDB curators role is to carry out the data review. This is where we add value over other data archives who simply offer a place for users to host their data (e.g. FigShare). By having data experts (our in-house curators) examine the accompanying manuscript we can ensure that the dataset is complete and sufficient for reproducibility.

The review of data is currently split into two parts; pre and post manuscript review (as shown in Figure 1 below). The initial review of the first draft manuscript to ensure all data are made available to the peer reviewers, and; the final data audit and curation to ensure that the data is still complete for the revised manuscript and correctly archived with open access to everyone. The reason for this is to reduce the unnecessary work of the full data review on manuscripts that do not pass the manuscript peer-review process.

In structure a data review can be thought of in much the same way as a manuscript peer review , just with a tighter focus on the methodology and results rather than the discussions and conclusions. For a recap or overview of manuscript review technique you may wish to watch this video (https://youtu.be/2mWahIGO1Lk).



Fig1. The current standard workflow from manuscript submission to dataset and manuscript publication, highlighting the 2 parts of the Data Review. ([Workflow video](http://../Chapter4/Submission_workflow_including_GigaDB_status_changes.ppsx))

### <a name="_toc140661946"></a>**Data availability check (Pre-manuscript review)**
The goal of the data audit before review of the manuscript is to help ensure; 

(1) all of the data underpinning the manuscript is available to the reviewer (and eventually the public), 

(2) the data are in appropriate formats, and 

(3) the methods and data are understandable and transparent. 

The peer reviewers (not curators) are responsible for determining the methods used are appropriate to the task, while data auditing ensures what has been done is clear, so that it would be possible for others to reproduce the study..

One of the key statistics that matter for Editorial is the "time to first decision" which is the length of time from when the author clicks "submit manuscript", to the point where the editorial team give a first decision on that manuscript, that could be a reject (before review), or any of; reject, accept with minor changes, accept with major changes, or accept. The "get data" step for GigaDB falls within that time frame for anything that goes to review. This is why we try to keep the pre-review-data-audit (get data) stage brief.

The curator will be expected to read the article (primarily the methods and results sections) to assess the completeness of the methods described and to ascertain the location of the input data, scripts/software, and any data produced. 

Where appropriate the curator will communicate with the author(s) to ensure the relevant information is made available either publicly or via a temporary private location for review purposes prior to publication, including instructions to the authors on the submission of data to the most appropriate public archives.

All data uploaded to the GigaDB repository is complete (including integrity checks), named and annotated appropriately to enable reviewers to understand it, usually a list of the md5sum values of the files and a readme file are sufficient at this stage.

This can be a time-consuming process so here we present some ways to streamline the process and provide some general tips and techniques to help recognise which are the important bits to read when skimming.

Firstly, know what to expect! This comes from experience and background knowledge of the subject, so it’s either something you have or you don’t! There is no substitute for experience. However, there are a number of things that can help, for example, familiarity with the checklists we have prepared for the common dataset types.

Secondly, keep in mind the sorts of information that will be required, for example the type of experiments performed, genomic sequencing, transcriptomic sequencing, genome assembly etc…

While every paper is different there are some features of life sciences papers that tend to be consistent, most will have a Title, Abstract, Introduction, Methods, Results, Discussion and Supplemental materials. It’s a good idea to start with the title and abstract, this will give a general feel for the subject material to expect in the article. If required, you can go back to the checklists to refamiliarise yourself with the expected materials before continuing with reading the article.

Usually the next most important parts to look at are the methods, followed by the results. Often it’s not even necessary to look at the introduction or discussion sections, and only if the methods and results sections leave things unclear might you need to delve into those sections at all.

If the paper is very long, even when reduced to just the methods and results sections you may wish to employ some more general speed reading techniques like: try to detect the main idea in the introductory paragraphs or section titles, which can help you decide early on whether the section is worth reading in detail, read the first sentence in each paragraph and then decide whether the rest of the paragraph deserves a read. If it doesn’t, move on.

You don’t necessarily even need to read complete sentences, if the start of a sentence holds no promise of the sentence giving you the information you want, skip to the next sentence.
###
## <a name="_toc140661947"></a>**Worked example of the Initial Data Availability Check step:**
Lets look at a relatively common dataset type a genome paper. Download the version of the manuscript as submitted to *GigaScience* here:

[giga-d-18-00410_original_submission.pdf](https://oup.silverchair-cdn.com/oup/backfile/Content_public/Journal/gigascience/8/6/10.1093_gigascience_giz071/1/giz071_giga-d-18-00410_original_submission.pdf?Expires=1568408164&Signature=epuHAjPhOCKHjWo3fPUDXktix1CpkWSwuhFoSZ--NQqdRkXWO9QbbYpgYJhKyoppfiKSp1~iAqsrrIE2H-HyVWvQUy9RCqcD1-gZ-FNEzSs4CX6Dwscwf9SoAGcKKIZomnnpT2oyIzPrcwTe0~MJWEZHqYeKAiGoJMOSYOTA~vtcs2U6Ouc0CzZlY6sHj3MWUDV8AvH~iB1RRBBrXeQBa~EuSmnx~yRz7PK8YpOHcvRKhf7yawQwjq0XezL-IkMoQZpvNMpEJfyNwl32RQdbFTAttryEsQmd0KILOdrtyhaiunTW99-BOYhjOMDDX5gUhPnNGpVyOGKvME5kT-vYkA__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA) 

Note- this is the original version before any review and corrections where made during the review process. It represents the sort of manuscript that we generally see for *GigaScience* submissions.

Before the *GigaScience* Editors will send the manuscript for review they will ask GigaDB curators to do the initial data review/check to ensure that all the data files are available to enable the reviewers to do the manuscript review.

Since we already know what dataset type we’re dealing with here (genomic) you might wish to review the submitter guidelines for what we expect in Genomic datasets (<http://gigadb.org/site/guidegenomic>) 

For the purposes of the Data Availability Check, you will need to scan read the manuscript to check what files you would expect to be available. 

As reminder here is an outline the generic process: 

- Check the Methods for clarity and expectation of what input/output files to expect to see.
- Check the results section for what results to expect to see.
- Check the Data Availability section for what they have already provided access to.
- Check the supplemental figures/tables/files for stuff that should be data files or that is a summary of data files.
- For data that has a suitable public repository, ensure that those data have been submitted there and have adequate access for reviewers, e.g. for Seq data, ensure the sequences have been submitted to the INSDC/SRA in a suitable format (i.e. de-multiplexed) and that they have provided reviewer access or made it public.

To assist the curators we have created a checklist of the common things encountered during the pre-review:

- Are there GitHub Repositories associated with this manuscript?
  - If so, do they have OSI-approved licenses?
- Check availability of Input, test and/or Benchmarking data for software papers
- Sequence data are available from INSDC (either public or by reviewer access)
- BUSCO - most recent version (5) used - check in the submitted file
- Are there additional Data DOI links (e.g. Zenodo) associated with this manuscript
  - If so, are they assigned a CC0/public domain license? 
- For Imaging datasets - are raw images suitable for submission to BioImage Archive or EMPIAR?
- Does the MS involve ANY human sample data, if yes, verify all ethical issues and consent 
- Do any of the files provided use proprietary formats, if yes explain why thats OK, or if they need to be changed before acceptance
- Compressed archive file supplied by authors have been unpackaged to check content (yes/no) if no explain why. 
- Readme file with file descriptions provided
- File integrity (MD5) checks complete
- Any additional comments to aid the Post-review Curator


### <a name="_toc140661948"></a>**Your turn**
Please now take a look at the manuscript and make some brief notes of the files that you would expect to be available if you had been asked to review the manuscript?

When you have your own list, compare it to [this](#17dp8vu);


### <a name="_toc140661949"></a>**Suggested file list**
<a name="17dp8vu"></a>The expected files from original manuscript would be:

- Raw genomic sequence data in SRA (EBI or NCBI) provide accessions
- Raw Transcriptomic sequence data in SRA (EBI or NCBI) provide accessions
- BioNano optical map files x2 (these are now also accepted at EBI-SRA)
- Assembled genome sequence (fasta)
  - Contig level
  - Scaffold level
  - Chromosome level
- BUSCO output file (complete output not just summary table)
- Coding gene sequence annotation file (GFF, CDS fasta and CDS amino acid fasta)
- Repeat annotations (GFF)
- Comparative genomics sequence alignment files (multi-fasta)
- Phylogenetic tree files (newick)
- RNA expression level matric (FPKM tables)

Infact it is almost exactly as we list in the submitter guidelines, its worth pointing out some points here about the sorts of files we expect and where we expect them to be;

<a name="_3rdcrjn"></a>The raw sequence data must be in an INSDC recognised data archive, GigaScience will not publish a manuscript that hasn’t deposited their data in the SRA. However, some authors are overly cautious about making their data open to the public before the manuscript has been accepted. While we believe there is no reason for concern we have to respect those wishes, for that reason we are willing to allow authors to keep the SRA accessions set to private on the condition that they can provide access to those data to our reviewers upon request. NCBI do offer a review access by secure login if requested by the submitter, EBI currently don’t offer such a service. If the authors are unwilling to release the data publicly for review and are unable to gain secure reviewer access we can offer to host the data for them for the review process.

It should also be noted that many authors appear to be unaware of the requirement to also submit the RNA sequence data to the SRA, so its important that as curators we check what data is actually available in the SRA submission. Often authors have only used the RNA seq data to assist with the gene prediction, hence they don’t think of the data as important, but it is. In this case they also used the RNA seq data to show gene expression levels, so we need to make sure we have the expression level data table(s).

Recently the EBI SRA have started accepting BioNano optical map data as well, so if the authors had submitted data there it would have been possible to ask them to submit those data as well, in this case the authors had used NCBI so do not have that option, we therefore need to have those files in GigaDB.

The assembled genome sequence can sometimes be tricky, it is acceptable for authors to also submit that to the GenBank or ENA archives but we do not mandate that as it can sometimes be a complex process. Even in cases when the authors have already submitted it to the archive we still request a copy in GigaDB for ease of user access (those files are relatively small anyway), along with the accompanying annotation files for repeats, coding genes, non-coding features etc…

Whenever you see phylogenetic trees in a manuscript you know that they have been generated from a sequence alignment, its important that we get those alignments as that is only way for a reviewer to check that the tree is a true representation of the alignment. In addition we ask for the tree file in Newick format as that will allow us (in the future) to provide a visualisation of trees in the GigaDB website (we hope).

Armed with the list of data files that you expect to be available, we then contact the authors with the standard (templated) “please supply your data” letter including details on how to upload their data files to our private FTP area.

At this point the initial curatorial step is almost complete, we are responsible for monitoring the data files uploaded and sometimes authors require clarification on things requested. Sometimes they need some further assistance with understanding the differences between GigaDB hosting data and the narrative information they usually supply with a manuscript as a supplemental file.  

Once the data are uploaded we run file integrity checks to ensure files are not corrupt, and if required reformat things, unzip things, remove spaces from file names etc, generally tidy the data directory. We then inform the Editors as soon as the data are available and responsibility for the paper reverts back to the editors who will arrange the formal peer review.

Only if the manuscript receives the approval of the peer reviewers and the editorial team, do the curation team see this paper again. If it is rejected then we are notified and we can delete any data held on our FTP area after 3 months. The reason we wait 3 months is incase of appeal by the authors at the rejection decision.


### <a name="_toc140661950"></a>**Full data assessment (Post-manuscript review)**
The full data assessment stage is the main role of the GigaDB Biocurator and is where some experience in the life science research environment may be useful. The process for each dataset will vary depending on the manuscript, for this reason the suggestions outlined here are not to be considered the complete and exact protocol for every dataset. Instead we can only provide a general set of guidelines that the curator will need to adjust on a case by case basis. 

In brief the curator will need to confirm all the input data, scripts/software and output data are complete and in appropriate formats with correct license details and metadata, taking into any revisions made during the peer-review process. On occasion the curator may need to perform some data transformations e.g. renaming files to remove un-acceptable characters, generating visualisations of data such as Sketchfab 3D rendered surface view, or JBrowse genome view. 

They will also need to generate the GigaDB dataset on GigaDB.org. To do  the curator will need to read the manuscript and extract all relevant metadata to input into GigaDB, at present this is achieved using an Excel spreadsheet as an intermediary to gather the relevant metadata for automated upload to the database via in-house scripts. The use of that spreadsheet and the specific details required in it are covered in a later section.

## <a name="_toc140661951"></a>**Data publishing**
The final stage of the process is to complete the publication of the dataset, which includes asking the author(s) to check and confirm the details, minting the DOI at DataCite, and ensuring the author(s) and publishers are fully aware of the correct way to cite the dataset. Set a release date if not immediate. 
## <a name="_toc140661952"></a>**The role of GigaDB curators**
In general the curator is expected to: 

- Ensure all relevant data are available for reviewers (Data Availability Check)
- Read the manuscript and extract all relevant metadata to input into GigaDB (BioCuration)
- **Confirm all the input data, scripts/software and output data are complete and in appropriate formats with correct license details and metadata.** 
- Input all relevant links into GigaDB, and confirm they are to stable long-term hosts, are public and correct.
- Perform any data integrity checks required, e.g. md5sum values. 
- Perform any data transformations that maybe required, e.g. renaming files to remove un-acceptable characters, generating visualisations of data such as Sketchfab 3D rendered surface view, or JBrowse genome view. 
- Publish the final dataset

The data availability check is the first stage that GigaDB curators get assigned, and we will focus on that for the rest of this chapter. Each of the other bullet points above will be addressed in more detail in the following chapters.



# <a name="_toc140661953"></a>**Video transcripts:**
### <a name="_toc140661954"></a>**YouTube video describing the importance of data sharing**
<https://web.archive.org/web/20180331100123/https://www.youtube.com/watch?v=8Sg536Rgbjk&gl=US&hl=en>

Data sharing is the practice of making data used for scholarly research available to other investigators. Replication has a long history in science. The motto of The Royal Society is 'Nullius in verba', translated "Take no man's word for it." Many funding agencies, institutions, and publication venues have policies regarding data sharing because transparency and openness are considered by many to be part of the scientific method. A number of funding agencies and science journals require authors of peer-reviewed papers to share any supplemental information (raw data, statistical methods or source code) necessary to understand, develop or reproduce published research. A great deal of scientific research is not subject to data sharing requirements, and many of these policies have liberal exceptions. In the absence of any binding requirement, data sharing is at the discretion of the scientists themselves. In addition, in certain situations governments and institutions prohibit or severely limit data sharing to protect proprietary interests, national security, and subject/patient/victim confidentiality. Data sharing may also be restricted to protect institutions and scientists from use of data for political purposes. Data and methods may be requested from an author years after publication. In order to encourage data sharing and prevent the loss or corruption of data, a number of funding agencies and journals established policies on data archiving. Access to publicly archived data is a recent development in the history of science made possible by technological advances in communications and information technology. To take full advantage of modern rapid communication may require consensual agreement on the criteria underlying mutual recognition of respective contributions. Models recognized for improving the timely sharing of data for more effective response to emergent infectious disease threats include the data sharing mechanism introduced by the GISAID Initiative. Despite policies on data sharing and archiving, data withholding still happens. Authors may fail to archive data or they only archive a portion of the data. Failure to archive data alone is not data withholding. When a researcher requests additional information, an author sometimes refuses to provide it. When authors withhold data like this, they run the risk of losing the trust of the science community. Data sharing may also indicate the sharing of personal information on a social media platform.
