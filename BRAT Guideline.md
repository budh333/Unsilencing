Find our BRAT environment [here](https://brat.create.humanities.uva.nl/index.xhtml#/). 
To login, contact Mrinalini: m.luthra@uva.nl, she will provide you with the login credentials.

The BRAT annotations were made within bundle 6847 of the 1.04.02 inventory of the Dutch United East India Company (VOC) archive. The bundle 6847 encompasses 1202 pages of transcribed testaments. From which roughly 200 are annotated (see annotations folder).  

Below is a list of entities and relations that we defined for our case study: 

### ENTITIES

- **Person**: Name of Person \
Eg: Benjamin Heynen (There are often multiple spellings of the same name, these can be annotated as aliases.)


- **Men, Women, Indigenous**: terms (such as titles and kinship terminology) that help us classify peoples \
Eg: m:r, heer, moeder, vrije Christian vrouw, oom \
Note: pronouns (such as mij, haar, zij) can be ignored \ 
Job titles relating to men such as koopman shouldn’t be annotated - testateur is an exception to this guideline. \

- **Number**: to signify number of entities \
Eg: mark 8 as Number entity in the example of 8 sisters or 3 for three children. \
Note: we’ve debated about whether it is useful to focus on the number of mentions (say Women) rather than the exact number (of women mentioned in these archives). For this case study, we have focused on the latter.

- **Group**: to mark out specific groups benefiting from the will where no names are listed. \
Eg. slaven

- **GPE**: geopolitical entity \
Eg: Jaccatra

- **Organisation**  \
Eg: Nederlands Oost Indies Compagnie or Hoge Regering Nederlands India


## RELATIONS 
(roughly in order of importance for our project)

- **Is** Arg1:Person, Arg2:Indigenous|Women|Men|Group \
Relation goes from person name to men/women/indigenous \
Eg: “Benjamin Heynen” to “heer”


- **Origin** Arg1:Organization, Arg2:GPE \
Eg: 

- **Number_of**  Arg1:Women|Men|Indigenous|Group, Arg2:Number \
Note please note the distinction between “Number” for entity and "Number_of" for relation \
Eg: sisters(“women”) to eight(“number”)

- **Alias**  Arg1:Person, Arg2:Person, <REL-TYPE>:symmetric-transitive \
When a person has two names or multiple spellings of the same name. \

Note: We do not focus on family relations such as family, mother of, sister of, etc in this case study.

- **Employment**  Arg1:Person|Indigenous|Women|Men|Mixed_ppl|Group, Arg2:Organization \
When person name is stated, use Person otherwise choose other entities such as men, women, indigenous \
Eg: “Benjamin Heynen” --employment--“VOC”


- **Location**  Arg1:Person|Indigenous|Women|Men|Mixed_ppl|Group|Organization, Arg2:GPE \
When a person’s name is stated, use Person otherwise choose other entities such as men, women, indigenous \
Eg: “Ms”(women) --is-- “Jamila van Nias” (Person) --Location--“Nias” (GPE) \
“VOC”(Organization) --Location-- “Batavia”(GPE)

- **Geographical_part**  Arg1:GPE, Arg2:GPE \
Eg: "Amsterdam" --geographical_part--"Nederlands"


