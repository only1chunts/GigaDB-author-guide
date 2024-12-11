---
name: New prepare-dataset curation
about: When a new MS is added to the prepare dataset list
title: Include MS Submission ID, Dataset DOI number, userbox, name/ID, curator name in title
assignees: 
projects: Dataset-Prep-tracking project
---



# Checklist (handling curator)
Please check the boxes to confirm each of the following items have been done:
- [ ] Userbox name is provided in ticket title
- [ ] Checked if user email address is already in GigaDB
  - [ ] If user exists in GigaDB, do their name(s) and affiliation(s) exactly match the details in the spreadsheet?
- [ ] Dataset type(s) are spelt correctly 
- [ ] Author list format is as expected
- [ ] Funding details are formated correctly with no additional commas or semi-colons
- [ ] Sample tab includes ONLY 1 header row (plus sample rows) 
- [ ] Sample attributes are from the controlled vocabulary present in GigaDB attributes table
- [ ] All filenames ONLY include the characters a-z A-Z 0-9 _ - + .  nothing else
- [ ] File list exactly matches the files in the relevant userbox
> [!NOTE]  
> readme_DOI.txt will be in files tab of spreadsheet but not in userbox
> 
> DOI.md5 and DOI.filesizes will appear in userbox but not in files tab of spreadsheet
    
- [ ] There are no hidden/system files included in userbox (nor spreadsheet), e.g `.DS_store` or similar.
- [ ] File types are selected from the dropdown menu
- [ ] Files only have 1 attribute per file
> [!NOTE]  
> Only 1 attribute will be added by upload tool, but all attributes can be included in spreadsheet to ease curation tracking.

- [ ] Userbox have DOI.md5 and DOI.filesizes files present and correct
- [ ] Attach spreadsheet file [here]

# Additional comments

# Checklist (2nd curator)
- [ ] Dataset type(s) are spelt correctly 
- [ ] Author list format is as expected
- [ ] Funding details are formated correctly with no additional commas or semi-colons
- [ ] Sample tab includes ONLY 1 header row (plus sample rows) 
- [ ] Sample attributes are from the controlled vocabulary present in GigaDB attributes table
- [ ] All filenames ONLY include the characters a-z A-Z 0-9 _ - + .  nothing else
> [!NOTE]
> Filenames should not start with "./" or "/"
- [ ] File types are selected from the dropdown menu