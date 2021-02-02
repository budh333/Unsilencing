# Unsilencing

This project was carried out by Thijs Vorstenburg, Clare Shutt, Saskia Virginia Noot under the supervision of Prof. Dr. Charles Jeurgens and Mrinalini Luthra at the University of Amsterdam working with the Nationaal Archief.

Description of this repository:

## Data

The VOC testaments can be downloaded via this [link](https://eur04.safelinks.protection.outlook.com/?url=https%3A%2F%2Fzenodo.org%2Frecord%2F4383748%2Ffiles%2FHTR%2520results%25201.04.02%2520Oost-Indische%2520Testamenten%2520TXT.zip%3Fdownload%3D1&data=04%7C01%7CK.J.P.F.M.Jeurgens%40uva.nl%7C51825423027b4c0266e308d8a7284871%7Ca0f1cacd618c4403b94576fb3d6874e5%7C1%7C0%7C637443138748083031%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&sdata=tgANxUkk8eeyjf7rxEDoI8rL0KNmP6loNXfDwA0rP60%3D&reserved=0)

- **Annotations** : this folder contains annotations from BRAT. While this folder contains 1202 files (from the folder 6847), around 200 of them actually contain annotations.
- **Corpus**: this folder contains 1202 transcribed pages from the folder 6847
- **Corpus_6848** contains all transcribed pages from folder 6848

## BRAT Guideline

This file introduces the reader to our entities and relations in BRAT used to annotate the testaments. 

## Indexing!

This is the main result of our project. This code collects all our BRAT annotations, extract list of terms used to describe men, women and indigenous peoples and createds and index "**qualifierbasedindex.xlsx**"!

## NER on Testaments

In this folder one can find some code on creating a pipeline to perform NER on the testaments, and two indices created on the basis of NER. 

### NER on Testaments Improvements 

We explore feeding in corrections into our pipeline, to see if we can improve the results of the NER.

### NER spaCy retraining

Some code to retrain spaCy — needs more work.

