# Python-Writing-Personality-Score

CLASS ASSIGNMENT

### ⚠️ <span style = "color:red"> Dataset: Student personality scores and writing style </span>

This data record includes 

* File name and word count
* 4 summary language variables
    * analytical thinking      - clout      - authenticity             - emotional tone
* 3 general descriptor categories
    * words per sentence   - % of target words captured by the dictionary    - % of words longer than six letters
    
* 21 standard linguistic dimensions
    * % of words that are pronouns, articles, auxiliary verbs, etc.
* 41 word categories tapping psychological constructs 
    * affect   - cognition    - biological processes   - drives
* 6 personal concern categories 
    * Ex, work   - home   - leisure    - activities
* 5 informal language markers 
    * assents   - fillers   - swear words   - netspeak)
* 12 punctuation categories 
    * periods   - commas, etc. 

Each dictionary entry additionally defines one or more word categories or subdictionaries. 

* Ex - "Cried" is part of five word categories: sadness, negative emotion, overall affect, verbs, & past focus. 
    * If "cried" is found, each of the five subdictionary scores will be incremented
    * All sadness words, belong to “negative emotion” category,& “overall affect words” category 

* Word stems can be captured 
    * Ex -  Dictionary includes stem hungr*. Target words that match the first five letters are counted as an ingestion word - hungry, hungrier, hungriest 
        * The asterisk, denotes acceptance of all letters, hyphens, or numbers following its appearance
        
