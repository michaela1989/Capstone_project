#Codebook for "affect.csv"

The data in <u>affect.csv</u> represent data emailed to me by random participants, as well as current Eastern Oregon University students seeking extra credit, following their participation in my YouTube video experiment, beginning with [Informed Consent for Emotion and Recall](https://www.youtube.com/watch?v=iphxvoAOpE4)
and the completion of other videos following the initial consent. These data were compiled using the preprocessing.R R script and are suitable for data analysis.

The data file includes 10 columns of information. There were only 3 variables however: valence, affect, and number of correct responses. 

The extra data was used to ensure accurate condition number chosen by participants, as well as ensuring an equal range of sex, age, and conditions, to reduce the risk of bias results.

The variable of interest is memory as measured by word recall. 
There are two factors being studied: valence and arousal. 
And each factor has two levels: valence (negative and positive) and arousal (high and low).


* **subject**: We numbered the individual participants in no particular order aside from the order they were received.

* **affect**: NL=negative valence, low arousal; NH=negative valence, high arousal;
              PL=postive valence, low arousal; PH=postive valense, high arousal

* **condition**: The condition number assigned to each affect. There were 4 condition options and participants were to select the condition number labeled with their month of birth.

    * Condition 1=January, May, September
    * Condition 2=February, June, October
    * Condition 3=March, July, November
    * Condition 4=April, August, December
    
    The condition numbers were randomly assigned to each affect. Condition 1 was         assigned to Negative Low, Condition 2 was assigned to Positive Low, Condition 3 was assigned to NegativeHigh, and Condition 4 was assigned to Positive High.

* **valence**: A factor variable identifying the emotion being induced from the conditioned video assigned.

* **arousal**: A factor variable indicating the level of emotion being induced.

* **total**: The total number of words provided in the video.

* **thought**: We asked participants to provide us their entire list of words so we couldcompare what they recalled to the actual list to ensure accurate responses, thus the number"thought" is the number of words they listed out as believing they remembered from the video.

* **correct**: After comparing the "thought" recalled words with the actual list of words, this is the correct number recalled.

* **sex**: Participants gender.

* **age**: Age of participants.