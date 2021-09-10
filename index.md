## BICCN Controlled Vocabularies for Data Submission

This is the page for viewing acceptable terms (comprising a controlled vocabulary) for BICCN data submitters.

Use the following links to navigate to tables containing terms, synonyms, and definitions that are acceptable for submitting BICCN data.

### Categories

#### [Techniques](/techniques_table.csv) (methods, protocols, ways of conducting experiments) [Google Sheet Format](https://docs.google.com/spreadsheets/d/1C5Ok_5GOROCVHESazgqRYi72QMqaJFvc1nuUGnCqGro/edit?usp=sharing)

#### [Specimens](/specimens_table.csv) (certain targets of experimental methods). [Google Sheet Format](https://docs.google.com/spreadsheets/d/1pB0upuCYl2JFvNYHIuo7qSsZtKqMByd8LoskFmFPV6I/edit?usp=sharing)

Specimens are roles that material entities may have. To say that something is a specimen is simply to say that it bears the specimen role. The role of specimen for a material entity is gained via a process (a specimen collection process). Typical examples of specimens are blood taken from an animal, where the blood has the specimen role (blood specimen) and the animal does not bear that role (i.e., the animal is not a specimen). However, the specimen role can also be borne by whole organisms. 

Formally, asserting that some material entity is a specimen asserts the following:

  'inheres in' some ('material entity' and (is_specified_output_of some 'specimen collection process'))
  
where the 'material entity' slot is occupied by the various specimen level entities (e.g., cell, organism, organ, tissue). 

Detailed descriptions of these relations (and other relations regarding specimens) can be found here: [helpful relations relevant to specimens](/specimens_relations_table.csv).

### Contact

If you need any assistance or have any questions, feel free to email the [data curation team](data.curation@alleninstitute.org) and we will respond in a timely manner.
