# Twitter trolls - how Russia meddles with western democracies

## Overview of the content in the repo.
Milestone2.ipynb is the file we had ready for the second milestone. This file is a part of the process of doing this project and can be looked at to compare the difference between our steps in working with this project. 

Milestone3.ipynb is the final milestone file with all of our preprocessing, analysis and thoughts regarding the project. The file is categorized and numbered in different parts, the first three of them including all our code. 

The final data story contains visualizations of what we feel are our most interesting findings. To look at every little detail, please look at Milestone3.ipynb.

The data story for this project can be found at [this link](https://haakonms.github.io/ADAwebsite/).
The git repo for the data story can be found [here](https://github.com/haakonms/ADAwebsite).

# Abstract
Over the last several years there has been an attempt from Russian trolls to spread propaganda and fake news over social media in order to spread political ideas among the general population both nationally and internationally. Can these attempts be regarded as undermining the democracy of the affected countries? 
 
In this project we are going to analyze a great number of these russian tweets and look into their motivations for this meddling. We will mainly look into their overall political goals in the US, and examine how these goals change over time. Have the trolls achieved their goals? We will also look into how the trolls operate and organize themselves, trying to find patterns in the madness. Such patterns can hopefully help the general population to indicate that a tweet is originating from a troll. As the Russian efforts are increasing every year, a solution is needed to defend the democracy.

# Research questions
- ~~Does the trolls advocate for a common political stance in each specific country? If so which leaning do they have? If not, how polarized are the tweets between left leaning and right leaning?~~
 
*To check other languages was an idea we were initally eager to do, but after a conversation with the TA and looking into it ourself we found out that this became more difficult than initially thought. A lot of foreign languages were not correctly identified, and it made more sense to just focus on the english content regarding the american election.*

- ~~Which themes does the propaganda mainly revolve around? About which issues should people be particularly careful not to believe everything they read? ~~

*We used libraries with text classifiers to look at this, but did not really get the result we wanted. We still want to look harder into it, to maybe extract some information for the last research question*

- Were the trolls united with a common political leaning in the period after the primaries in the US elections? **Answered**
 
- Was the original mission of the Russian trolls for the US election to make sure that Clinton was not elected, or to get Trump elected? **Answered**
 
- Are the trolls organized as a unit? Do they interact with each other (retweets, etc)? **Answered**

- Is there a way for people without a technical background to determine if a tweet is coming from a Russian troll? **Answered**

# Dataset
[IRA russian twitter trolls](https://www.kaggle.com/fivethirtyeight/russian-troll-tweets) - Three million tweets amounting to 175 Mb, along with a detailed description of the dataset 
 
This dataset contains around three million tweets and retweets from 2848 unique twitter users. Each tweet has several attributes, some of them are extracted from the tweet itself. For instance the author, content, and time stamp. Other attributes are later added. An example of such attributes is category of the troll, e.g. RightTroll, NewsFeed, etc.

We also have used a second dataset that Twitter released the autumn of 2018. 

# Contributors
Håkon Grini: Preprocessing second dataset, analysis of our main research questions. 
Håkon Sveen: Preprocessing the first dataset, preliminary analysis of the datasets, visualization, creating the data story.

