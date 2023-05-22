# Reannotated Estonian NER dataset

This is the Estonian NER dataset ([Tkachenko, 2010](https://core.ac.uk/download/pdf/16270382.pdf); [Tkachenko et al., 2013](https://aclanthology.org/W13-2412.pdf)) reannotated with a richer set of entities. 

## Dataset statistics

The dataset is divided into training, development and test sets. The annotations can be hierarchical, meaning that there can be one named entity inside another. The maximum number of levels in the hierarchical annotations is three. 

|                 | Train  | Dev   | Test  | Total  |
|-----------------|--------|-------|-------|--------|
| Documents       | 525    | 18    | 39    | 582    |
| Sentences       | 9965   | 2415  | 1907  | 14287  |
| Tokens          | 155983 | 32890 | 28370 | 217243 |
|1-level entities	| 13918	 | 2571	 | 2396	 | 18885  |
|2-level entities	| 987    | 223	 | 122	 | 1332   |
|3-level entities	| 40	   | 14	   | 4	   | 58     |

## Annotated entities

Originally, the Estonian NER dataset was annotated with PER, ORG and LOC entities only. The reannotated version is annotated with the following entities: 
* PER - person names
*	GPE - geopolitical entities
* LOC - geographical locations
* ORG - organizations
* PROD - products, things, works of art
* EVENT - events
* DATE - dates
* TIME - times
* TITLE - titles and professions
* MONEY - monetary expressions
* PERCENT - percentages

### Level 1 entities

|         | Train | Dev | Test  | Total |
|---------|-------|-----|-------|-------|
| PER	    | 3563	| 642	| 722	  | 4927  |
| ORG	    | 3215	| 504	| 541	  | 4260  | 
| LOC	    | 328	  | 118	| 61	  | 507   |
| GPE	    | 3377	| 714	| 479	  | 4570  |
| TITLE   | 1302	| 171 | 209	  | 1682  |
| PROD	  | 874	  | 161	| 66	  | 1101  |
| EVENT	  | 56	  | 13	| 17	  | 86    |
| DATE	  | 1346	| 308	| 186	  | 1840  |
| TIME	  | 456	  | 39	| 30	  | 525   |
| PERCENT	| 137	  | 62	| 58	  | 257   |
| MONEY	  | 291	  | 76 	| 153	  | 520   |
| Total   | 14945	| 2808| 2522  | 20275 |

### Level 2 entities

|         | Train | Dev | Test  | Total |
|---------|-------|-----|-------|-------|
| PER	    | 46    | 7	  | 4	    | 57    |
| ORG	    | 180	  | 31	| 12	  | 223   |
| LOC	    | 58	  | 12 	| 8	    | 78    |
| GPE	    | 745	  | 160	| 101	  | 1006  |
| TITLE	  | 6	    | 0	  | 0	    | 6     |
| PROD    | 3	    | 0	  | 0	    | 3     |
| EVENT	  | 5	    | 0	  | 0	    | 5     |
| DATE	  | 7	    | 34	| 1	    | 42    |
| TIME	  | 0	    | 0	  | 0     | 0     |
| PERCENT	| 1	    | 0	  | 0	    | 1     |
| MONEY   | 0   	| 0	  | 0	    | 0     |
| Total	  | 1051	| 126	| 244	  | 1421  |


### Level 3 entities

|         | Train | Dev | Test  | Total |
|---------|-------|-----|-------|-------|
| PER	    | 1     | 0	  | 0	    | 1     |
| ORG	    | 1	    | 0	  | 0	    | 0     |
| LOC	    | 0	    | 1 	| 0	    | 1     |
| GPE	    | 38	  | 13	| 4	    | 26    |
| TITLE	  | 0	    | 0	  | 0	    | 0     |
| PROD    | 0	    | 0	  | 0	    | 0     |
| EVENT	  | 0	    | 0	  | 0	    | 0     |
| DATE	  | 0	    | 0	  | 0	    | 0     |
| TIME	  | 0	    | 0	  | 0     | 0     |
| PERCENT	| 0	    | 0	  | 0	    | 0     |
| MONEY   | 0   	| 0	  | 0	    | 0     |
| Total	  | 40	  | 14	| 4	    | 58    |

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
