# Text-Summarization
Using Spacy and NLTK module with TF-IDF algorithm for text-summarisation. This code will give you the summary of inputted article. You can input the text by typing (or copy-paste) or from Txt file, PDF file or from Wikipedia Page Url.

## Purpose :- 

To save time while reading by summarizing a large article or text into fewer lines. 


## Description :-

It usage Term Frequency-Inverse Document Frequency (TF-IDF) algorithm for summarising the article.

## Features :-

You can read the text of your long article in 4 ways :-

![InputTextWays](https://user-images.githubusercontent.com/56812557/212475484-5bd0addf-1b14-4820-b4e2-b21565de8b71.png)

  - By typing text on your own (or copy-paste).
  - Reading the text from **.txt file**.
  - Reading the text from **.pdf file**.(You can choose either to get summary of entire pdf or select any page interval).
  
  ![PdfInput](https://user-images.githubusercontent.com/56812557/212475479-d012f433-8ebd-4283-9c18-c1ebf552accf.png)

  - Reading the text from **wikipedia page** (All you have to do is to provide the url of that page. Program will automatically scrap the text and summarise it for you).
  
Don't worry about Code length xD. It might look lengthy but there are lot of comments for explaination of code(almost 70 comments) and extra spacing for more readability.

 
 ## Output :- 
 
   - This is some of the summary text return by the program. Main article was loaded by Wikipedia Page Url -> https://en.wikipedia.org/wiki/Artificial_intelligence
   
   ![Summary](https://user-images.githubusercontent.com/56812557/212475483-5fe99afd-5016-428e-877d-e1e0b9406786.png)
   
   - Comparison of Original Content vs Summarized content.
   
   ![OriginalvsSummaryWordCount](https://user-images.githubusercontent.com/56812557/212475485-d06beadf-1805-49e2-a906-a2745d06b832.png)
   


  
## Requirements :-

- Python3 
- Spacy Module (short, medium, or long any type is sufficient)
- NLTK Module
- PyPdf2
- Beautiful Soup (bs4)
- urllib (already available with python itself, no need for external installation)


## How to install Requirements :-

1. Python3 can be installed from their official site https://www.python.org/ . Or you can use anaconda environment.
2. Spacy can be installed by
For Anaconda Environment > 
```
conda install -c conda-forge spacy

python3 -m spacy download en
```
For other environments > 
```
pip3 install spacy

python3 -m spacy download en
```
3. NLTK can be installed by
For Anaconda Environment > 
```
conda install -c anaconda nltk
```
For other environments > 
```
pip3 install nltk
```

4. PyPdf2 can be installed by
For Anaconda Environment > 
```
conda install -c conda-forge pypdf2
```
For other environments > 
```
pip3 install PyPDF2
```

5. Beautiful Soup (bs4)
For Anaconda Environment > 
```
conda install -c anaconda beautifulsoup4
```
For other environments > 
```
pip3 install beautifulsoup4`
```
## Getting Started :-

- Download or clone repository.

- Open cmd or terminal in same directory where **Text-Summarizer.py** file is stored and then run it by followng command :- 
```
python3 Text-Summarizer.py
```
- Now just follow along with the program.


## Bugs and Improvements :-

- No known bugs. Summary can't be as perfect as humans can do.
- Audio feature will be added soon, so that you can listen the summary too if you want.


## Dev :- Prakash Gupta
