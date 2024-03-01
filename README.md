**Classifying a corpus as 'Ham' or 'Spam'** <br>
<br> **Step 1:** *Loaded data from the csv file - spam.csv* <br> 
<br> **Step 2:** *Preprocessing: <br> 
<br> 1. Remove HTML tags and new line characters using BeautifulSoup <br> 
<br> 2. Remove punctuation using Spacy <br> 
<br> **Step 3:** *Feature Engineering* <br> 
<br> Created columns for <br> 
<br> 1. Number of words <br> 
<br> 2. Number of characters <br> 
<br> 3. Number of digits <br> 
<br> 4. Number of exclamation marks <br> 
<br> 5. Adding adjectives <br> 
<br> 6. Convert the "label" column values to numerical representation(0 for "spam",1 for "ham") <br> 
<br> **Step 4:** *Oversample using SMOTE* <br> 
<br> **Step 5:** *Modelling the data* <br> 
