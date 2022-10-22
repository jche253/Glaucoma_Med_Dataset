# Glaucoma_Med_Dataset

**Dataset Description:** 481 Free-text clinical notes for 481 patients seen for glaucoma. These notes are de-identified for Protected Health Information (PHI). Censored PHI are replaced with asterisks (\*). A combined annototation file of all ophthalmic medication entities including name, route, freuqnecy, and dosage are included in a separate JSON file. 

**Participants:** Patients with glaucoma

**Institution:** Casey Eye Institute at Oregon Health & Science University

**Data Collection:** From 1/2019-8/2020

**Datasheets for datasets:** We have provided a structured healthsheet (Rostamzadeh et al) based on the standardized datasheet by Gebru et al.

**Citation:** Accepted as a Data Descriptor Article to TVST. Pending a DOI link!

## Example Excerpt from Note
```
***** *** ********* GLAUCOMA ** *** Progress Note **/**/****     PROBLEM-SPECIFIC ASSESSMENT & PLAN NOTES FOR CURRENT ENCOUNTER    Visual distortions of shape and size      Assessment & Plan Note:   (Assessment & Plan note Last Updated **/**/****)   Office Visit  Written **/**/**** by ****** * ***, MD   Red dots like red ****** in her vision OU.  Headache afterwards, but went away with tylenol.  Feels she still has some of those dots now, but way less than before.  
```

## Example annotation
```
{"id": 9989, "text": "Brimonidine BID, OU", "meta": {}, "annotation_approver": null, "comments": [], "labels": [[0, 11, "DRUG"], [12, 15, "FREQUENCY"], [17, 19, "ROUTE"]]}
```
