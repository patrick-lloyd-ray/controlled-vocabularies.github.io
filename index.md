## BICCN Controlled Vocabularies for Data Submission

This is the page for viewing acceptable terms (comprising a controlled vocabulary) for BICCN data submitters.

Use the following links to navigate to tables containing terms, synonyms, and definitions that are acceptable for submitting BICCN data.

### Categories

#### [Techniques](/techniques_table.csv) (methods, protocols, ways of conducting experiments)

#### [Specimens](/specimens_table.csv) (certain targets of experimental methods).

Specimens are roles that material entities may have. To say that something is a specimen is simply to say that it bears the specimen role. The role of specimen for a material entity is gained via a process (a specimen collection process). Typical examples of specimens are blood taken from an animal, where the blood has the specimen role (blood specimen) and the animal does not bear that role (i.e., the animal is not a specimen). However, the specimen role can also be borne by whole organisms. 

Formally, asserting that some material entity is a specimen asserts the following:

  'inheres in' some ('material entity' and (is_specified_output_of some 'specimen collection process'))
  
where the 'material entity' slot is occupied by the various specimen level entities (e.g., cell, organism, organ, tissue). 

Specimens are modeled using the [OBI framework of specimen modeling](https://user-images.githubusercontent.com/67486986/132926068-ed64efe0-61f1-468a-a2ae-e0a9db499f23.png)

Detailed descriptions of these relations (and other relations regarding specimens) can be found here: [helpful relations relevant to specimens](https://docs.google.com/spreadsheets/d/1pB0upuCYl2JFvNYHIuo7qSsZtKqMByd8LoskFmFPV6I/edit?usp=sharing).

#### [Modalities](/modality_table.csv)

#### [Species](/species_table.csv)

#### [File Types](https://docs.google.com/spreadsheets/d/1E8RYBaveFaTMgAv3j_Ut4mdLFnm5rmGLXCzDwpLvNk0/edit?usp=sharing)

### Contact

If you need any assistance or have any questions, feel free to email the [data curation team](data.curation@alleninstitute.org) and we will respond in a timely manner.
