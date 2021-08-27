# [Spoken Conversation Search](http://jtrippas.github.io/Spoken-Conversational-Search/)

This repository contains the dataset created by observing participants addressing information needs of different complexity in an acoustic setting.


# Overview

**Updated August 2021**: the [SCSdata_v1.csv](https://github.com/JTrippas/Spoken-Conversational-Search/blob/master/SCSdata_v1.csv) is the full dataset used in Trippas, Spina, Thomas, Sanderson, Joho, and Cavedon (2020). The _SCSdata_ has been updated with completed data.

**Updated January 2019**: the SCSdataset.csv is the full dataset used in Trippas, Spina, Cavedon, Joho, and Sanderson (2018). The SCSdataset now contains all utterances and has the same format, but does not include "notes", as the ConversationalSearchDataSet.csv.

The file ConversationalSearchDataSet.csv contains a set of 101 transcribed conversations to solve information needs based on backstories in Trippas, Spina, Cavedon, and Sanderson (2017a).

The collection and transcription process is described in Trippas, Spina, Cavedon, and Sanderson (2017a) and Trippas, Spina, Cavedon, and Sanderson (2017b), along with an initial analysis.
Further analysis of the transcriptions and observations are published in Trippas, Spina, Cavedon, Joho, and Sanderson (2018).


## Citation

Please cite the articles below if you use this resource in your research:

-[Towards a Model for Spoken Conversational Search.](https://www.sciencedirect.com/science/article/pii/S030645731930425X) <br> Johanne R. Trippas, Damiano Spina, Paul Thomas, Mark Sanderson, Hideo Joho, and Lawrence Cavedon. <br>
Towards a model for spoken conversational search.Information Processing & Management, 57(2):1–19, 2020
 
-[Informing the Design of Spoken Conversational Search: Perspective Paper.](http://www.johannetrippas.com/papers/Trippas_CHIIR_2018.pdf) <br> Johanne R. Trippas, Damiano Spina, Lawrence Cavedon, Hideo Joho, and Mark Sanderson. <br>
In Proceedings of the 2018 Conference on Human Information Interaction & Retrieval (CHIIR '18). pp. 32-41. ACM, 2018.

-[How do people interact in conversational speech-only search tasks: A preliminary analysis.](http://www.johannetrippas.com/papers/Trippas%20et%20al-CHIIR2017.pdf) <br>
Johanne R. Trippas, Damiano Spina, Lawrence Cavedon, and Mark Sanderson. <br>
In Proceedings of the 2017 Conference on Conference Human Information Interaction and Retrieval (CHIIR'17), pp. 325-328. ACM, 2017a.

-[A conversational search transcription protocol and analysis.](http://www.johannetrippas.com/papers/Trippas%20et%20al-CAIR2017-protocol.pdf)
<br>
Johanne R. Trippas, Damiano Spina, Lawrence Cavedon, and Mark Sanderson. <br>
In Proceedings of SIGIR 1st International Workshop on Conversational Approaches to Information Retrieval (CAIR’17), CAIR. 2017b.

## BibTex
```
@article{trippas2020towards,
author = {Johanne R. Trippas and Damiano Spina and Paul Thomas and Hideo Joho and Sanderson, Mark and Cavedon, Lawrence},
title = {Towards a Model for Spoken Conversational Search},
journal = {Information Processing \& Management},
year = {2020},
volume = {57},
number = {2},
issn = {0306-4573},
url = {https://doi.org/10.1016/j.ipm.2019.102162},
doi = {10.1016/j.ipm.2019.102162},
pages = {1--19}
 }

@inproceedings{trippas2018informing,
 author = {Trippas, Johanne R. and Spina, Damiano and Cavedon, Lawrence and Joho, Hideo and Sanderson, Mark},
 title = {Informing the Design of Spoken Conversational Search: Perspective Paper},
 booktitle = {Proceedings of the 2018 Conference on Human Information Interaction \& Retrieval},
 series = {CHIIR '18},
 year = {2018},
 location = {New Brunswick, NJ, USA},
 pages = {32--41},
 numpages = {10},
 doi = {10.1145/3176349.3176387},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {conversational search, empirical, spoken conversational search, voice interaction},
}

@inproceedings{trippas2017how,
 author = {Trippas, Johanne R. and Spina, Damiano and Cavedon, Lawrence and Sanderson, Mark},
 title = {How Do People Interact in Conversational Speech-Only Search Tasks: A Preliminary Analysis},
 booktitle = {Proceedings of the 2017 Conference on Conference Human Information Interaction and Retrieval},
 series = {CHIIR '17},
 year = {2017},
 location = {Oslo, Norway},
 pages = {325--328},
 numpages = {4},
 doi = {10.1145/3020165.3022144},
 publisher = {ACM},
 address = {New York, NY, USA}
}

@inproceedings{trippas2017conversational,
  title={A conversational search transcription protocol and analysis},
  author={Trippas, Johanne R and Spina, Damiano and Cavedon, Lawrence and Sanderson, Mark},
  booktitle={Proceedings of SIGIR 1st International Workshop on Conversational Approaches to Information Retrieval (CAIR’17), CAIR},
  year={2017}
}
```


## Provided files
We provide all the releasable data in different files:

 * (**Updated August 2021**) Transcripts and codes as described in [Trippas et al. (2020)](https://www.sciencedirect.com/science/article/pii/S030645731930425X): [SCSdata_v1.csv](https://github.com/JTrippas/Spoken-Conversational-Search/blob/master/SCSdata_v1.csv)
 * Transcripts [(ConversationalSearchDataSet.csv)](https://github.com/JTrippas/Spoken-Conversational-Search/blob/master/ConversationalSearchDataSet.csv) and [(SCSdataset.csv)](https://github.com/JTrippas/Spoken-Conversational-Search/blob/master/SCSdataset.csv)
 * Backstories [(backstories_ConversationalSearchDataSet.csv)](https://github.com/JTrippas/Spoken-Conversational-Search/blob/master/backstories_ConversationalSearchDataSet.csv)
 * Code book [(CodeBook_CHIIR.pdf)](https://github.com/JTrippas/Spoken-Conversational-Search/blob/master/CodeBook_CHIIR.pdf)

## [SCSdata_v1.csv](https://github.com/JTrippas/Spoken-Conversational-Search/blob/master/SCSdata_v1.csv) file structure (**Updated August 2021**)
The file contains 10 columns:
1. **Start_time**: Start time of the utterance.
2. **Stop_time**: Stop time of the utterance.
3. **Query**: The reference to the information need participants are solving.
4. **Query_complexity**: One of three levels, referencing the task complexity type (remember, understand, and analyse).
5. **Role**: Which of the participants is talking in that particular utterance. The roles are annotated as Seeker (participant who has the information need which needs to be solved) and Intermediary (person who has access the the computer and search engine).
6. **Sub_themes**: Subthemes based on codes as described in [Trippas et al. (2020)](https://www.sciencedirect.com/science/article/pii/S030645731930425X)
7. **Code**: The action the participant takes in that utterance, these actions are described in [Trippas et al. (2020)](https://www.sciencedirect.com/science/article/pii/S030645731930425X)
8. **Query_counter**: A counter which keeps track of how many turns there have been between the participants in that conversation.
9. **Transcription**: Transcripts of the utterance of the particular user in that particular timeslot.
10. **Actor_pair**: 13 different pairs completed three tasks. This column distinguishes the different pairs for each task (1-13)



## Transcript file structure

The file contains 10 columns:

1. **Start time**: Start time of the utterance.
2. **Stop time**: Stop time of the utterance.
3. **Query**: The reference to the information need participants are solving.
4. **Query complexity**: One of three levels, referencing the task complexity type (remember, understand, and analyse).
5. **Role**: Which of the participants is talking in that particular utterance. The roles are annotated as A_User (participant who has the information need which needs to be solved) and B_Receiver (person who has access the the computer and search engine).
6. **Action**: The action the participant takes in that utterance, these actions are described in the code book and allow for reproduction of the results.
7. **Transcript**: Transcripts of the utterance of the particular user in that particular times lot.
8. **Notes**: Comments such as the particular search is stopped by the user or researcher or extra notes which relate to the action of the participant regarding the search session. *not included in the "SCSdataset.csv"
9. **Query counter**: A counter which keeps track of how many turns there have been between the participants in that conversation. For the initial data release only the first two turns are given. However, the first three turns are presented if the second turn is classified under the _Meta-communcation Theme_ (See CHIIR 2017 paper for further information).
10. **File name**: Indicating the group number (2-14) and the date of the experiment.

## Backstories file structure

The file backstories_ConversationalSearchDataSet.csv contains a set of nine selected information needs or topic backstories for this Spoken Conversational Search study that were authored in 2015 collectively by: Bailey, Moffat, Scholer, and Thomas.

Further information about the selected backstories can be found in [Bailey, Moffat, Scholer, and Thomas (2015)](https://data.csiro.au/dap/landingpage?pid=csiro:14550&v=2&d=true).



## Preliminary Analysis

The data in "ConversationalSearchDataSet.csv" is of a preliminary analysis of a spoken conversational search experimental setup. Observational findings are published in <br>
[Informing the Design of Spoken Conversational Search.](http://www.johannetrippas.com/papers/Trippas_CHIIR_2018.pdf) <br>
Trippas, Johanne R., Damiano Spina, Lawrence Cavedon, Hideo Joho, and Mark Sanderson. <br>
In Proceedings of the 2018 Conference on Conference Human Information Interaction and Retrieval (CHIIR'18), 2018.

# Abstracts

We conducted a laboratory-based observational study where pairs of people performed search tasks communicating verbally. Examination of the discourse allowed commonly used interactions to be identified for Spoken Conversational Search (SCS). We compared the interactions to existing models of search behaviour. We find that SCS is more complex and interactive than traditional search. This work enhances our understanding of different search behaviours and proposes research opportunities for an audio-only search system. Future work will focus on creating models of search behaviour for SCS and evaluating these against actual SCS systems. (Trippas et al., 2018)


We present preliminary findings from a study of mixed initiative conversational behaviour for informational search in an acoustic setting. The aim of the observational study is to reveal insights into how users would conduct searches over voice where a screen is absent but where users are able to converse interactively with the search system. We conducted a laboratory-based observational study of 13 pairs of participants each completing three search tasks with different cognitive complexity levels. The communication between the pairs was analysed for interaction patterns used in the search process. This setup mimics the situation of a user interacting with a search system via a speech-only interface. (Trippas et al., 2017a)



#   Acknowledgments

This research is partially supported by Australian Research Council Project LP130100563 and Real Thing Entertainment Pty Ltd.
The data collection and release was reviewed and approved by RMIT University’s Ethics Board (ASEHAPP 08-16).

The authors were employed by RMIT University when these transcripts were created.


# Further Information

For further information and resources, please visit [Spoken Conversational Search at RMIT University's Information Storage, Analysis and Retrieval (ISAR)](http://www.rmit-ir.org/index.php/research-grants/spoken-conversational-search) or contact [Johanne Trippas](http://www.johannetrippas.com/).

You are free to share (copy and redistribute the material in any medium or format) and adapt (remix, transform, and build upon the material) the data under the [CC BY-NC 3.0 licence](https://creativecommons.org/licenses/by-nc/3.0/).

<!--- -->
