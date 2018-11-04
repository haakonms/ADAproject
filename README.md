# Title

# Abstract
Over the last several years there has been an attempt from Russian trolls to spread propaganda and fake news over social media in order to spread political ideas among the general population both nationally and internationally. Can these attempts be regarded as undermining the democracy of the affected countries? 
 
In this project we are going to analyze a great number of these russian tweets and look into their motivations for this meddling. We will mainly look into their overall political goals in the US, and examine how these goals change over time. Have the trolls achieved their goals? We will also look into how the trolls organize and operate with the hope of finding patterns in the madness. Such patterns can hopefully help the general population to indicate that a tweet is originating from a troll. As the Russian efforts are increasing every year, a solution is needed to defend the democracy.

# Research questions
- Which themes does the propaganda mainly revolve around? Which issues should people be particularly careful not to believe everything they read?
 
- Does the trolls advocate for a common political stance in each specific country? If so which leaning do they have? If not, how polarized are the tweets between left leaning and right leaning?
 
- Are the trolls organized as a unit? Do they interact with each other (retweets, etc)?
 
- Were the tweets united with a common political leaning in the period after the primaries in the US elections?
 
- Was the original mission of the Russian trolls for the US election to make sure that Clinton was not elected, or to get Trump elected?
 
- Is there a way for people without a technical background to determine if a tweet is coming from a Russian troll?

# Dataset
IRA russian twitter trolls - Three million tweets amounting to 175 Mb, along with a detailed description of the dataset https://www.kaggle.com/fivethirtyeight/russian-troll-tweets 
 
This dataset contains around three million tweets and retweets from 2848 unique twitter users. Each tweet has several attributes, some of them are extracted from the tweet itself. For instance the author, content, and time stamp. Other attributes are later added. An example of such attributes is category of the troll, e.g. RightTroll, NewsFeed, etc.
 
There are many factors that we can examine in the dataset. Looking at given features like timing could be very interesting to find patterns. We also intend to add features, in order to make the dataset more suitable for our analysis. As every data point contains the whole tweet itself, it is possible to perform a broad analysis on the content. This could be used to determine whether a certain person or word is mentioned, and add the overall theming as a feature.  Another example would be a feature stating whether a tweet is a retweet of another troll, unique, or identical to another tweet in the set. 
 
The data set it pretty small so it should be pretty manageable to process with pandas, but spark could also be used.


# A list of internal milestones up until project milestone 2
### 9th of November:
- Create a skeleton for our project
- Import and clean the data. 
- Look into whether or not processing data on the cluster will be necessary.
 
### 16th of November:
- Process the data set and make new features.
- Perform most of our analysis and answer our research questions.
- Figure out a good way to visualize results.
 
### 23rd of November:
- Finish all of our analysis.
- Visualize our findings.
- Make sure our code is fully commented and debugged.
- Add readable analysis of our findings that a stranger could understand. 


# Questions for TAa
Add here some questions you have for us, in general or project-specific.
