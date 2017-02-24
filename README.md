# [Spoken Conversation Search](http://jtrippas.github.io/spoken-conversational-search/)

This repository contains the dataset created by observing participants solve information needs of different complexity


# Overview

The file ConversationalSearchDataSet.csv contains a set of 115 transcribed conversations to solve information needs based on backstories.

These transcripts were authored in 2016 collectively by:

**Johanne R. Trippas, Damiano Spina, Lawrence Cavedon, and Mark Sanderson**


## Provided files
We provide all the releasable data in different files:
 * Transcripts
 * Backstories
 * Code book


## Transcript file structure

The file contains 10 columns:

1. **Start time**: Start time of the utterance.
2. **Stop time**: Stop time of the utterance.
3. **Query**: The reference to the information need participants are solving.
4. **Query complexity**: One of three leverls, referencing the task complexiy type (remember, understand, and analyze).
5. **Role**: Which of the participants is talking in that particular utterance. The roles are annotated as A_User (participant who has the information need which needs to be solved) and B_Receiver (person who has access the the computer and search engine).
6. **Action**: The action the participant takes in that utterance, these actions are described in the code book and allow for reproduction of the results.
7. **Transcript**: Transcript of the utterance of the particular user in that particular times lot.
8. **Notes**: Comments such as the particular search is stopped by the user or researcher or extra notes which relate to the action of the participant regarding the search session.
9. **Query counter**: A counter which keeps track of how many turns there have been between the participants in that conversation. For the initial data release only the first two turns are given. However, the first three turns are presented if the second turn is classified under the _Meta-communcation Theme_ (See CHIIR 2017 paper for further information).
10. **File name**: Indicating the group number (2-14) and the date of the experiment.

## Backstories file structure

The file backstories_ConversationalSearchDataSet.csv contains a set of nine selected information needs or topic backstories for this Spoken Conversational Search study that were authored in 2014 collectively by: Peter Bailey, Alistair Moffat, Falk Scholer, Paul Thomas. 

Further information about the selected backstories can be found in [Moffat, Bailey, Scholer, and Thomas (2014)](https://data.csiro.au/dap/landingpage?pid=csiro:14550&v=2&d=true).
 
## Preliminary Analysis

The resleased data is of a prelimiary analysis of a spoken conversational search experimental setup. Please note that coding the data set is an iterative process and therefore has changed for consecutive analysis. We are planning on releasing the full data set and with updated code book once this is finalized.

# Abstract

We present preliminary findings from a study of mixed initiative conversational behaviour for informational search in an acoustic setting. The aim of the observational study is to reveal insights into how users would conduct searches over voice where a screen is absent but where users are able to converse interactively with the search system. We conducted a laboratory-based observational study of 13 pairs of participants each completing three search tasks with different cognitive complexity levels. The communication between the pairs was analyzed for interaction patterns used in the search process. This setup mimics the situation of a user interacting with a search system via a speech-only interface.

# Citation

Please cite the article below if you use this resource in your research:

[How Do People Interact in Conversational Speech-Only Search Tasks: A Preliminary Analysis](http://www.johannetrippas.com/papers/Trippas%20et%20al-CHIIR2017.pdf) <br>
Johanne R. Trippas, Damiano Spina, Lawrence Cavedon, and Mark Sanderson <br>
The ACM SIGIR Conference on Human Information Interaction and Retrieval (CHIIR), Oslo, Norway, 2017. (to appear) 

## BibTex
```
@inproceedings{trippas2016how,
  title={How Do People Interact in Conversational Speech-Only Search Tasks: A Preliminary Analysis},
  author={Trippas, Johanne R and Spina, Damiano and Cavedon, Lawrence and Sanderson, Mark},
  booktitle={Proceedings of the 2017 ACM on Conference on Human Information Interaction and Retrieval (CHIIR)},
  year={2017},
  organization={ACM}
}
```



#   Acknowledgment

This research is partially supported by Australian Research Council Project LP130100563 and Real Thing Entertainment Pty Ltd.

The authors were employed by RMIT University when these transcripts were created.





For more information, please contact [Johanne Trippas](http://www.johannetrippas.com/).





<!--- -->
## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/JTrippas/Spoken-Conversational-Search/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/JTrippas/Spoken-Conversational-Search/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
