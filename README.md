# Hi!

This is the main page I'll be using to run the session.

# Agenda:

## 08.30 am: Intro, career paths in data and questions
   1. [This](https://docs.google.com/presentation/d/e/2PACX-1vRbfvQpTP4ARbARRWhOL6WZ6koCKSHvf5OxFyHcJjn8GHXG3OpuneEH6uMYlpxKX0H_sEfHB6KAKrkq/pub?start=true&loop=false&slide=id.g29007063b8d_0_118) is how my career is progressing so far
   2. [Here](https://docs.google.com/presentation/d/e/2PACX-1vQp61itveaNmpuS4UMXIfaQshjMYBqywRP2aMWZjMlZy5v-iNOUouDMn_-z33RBwi2TeauhgEzGoep-/pub?start=false&loop=false)'s some information about career paths in data
   3. What [problems](https://padlet.com/kohwyhow/what-problems-do-you-want-to-solve-gjcypqiq99ko1wke) do you want to solve?

## 09.00 am: Looker Studio
   1. Create a Google account (you can use your personal one too, if you prefer)
   2. Head to [Looker Studio](https://datastudio.google.com/), using another tab
   3. Download as [CSV](https://docs.google.com/spreadsheets/d/1IaonaJj-c5Ud76Uc9WeRiMSlKLTNnbg-BCUxOoZrXn0/edit?usp=sharing) from here and upload to Looker Studio
   4. Build a few charts and filters
       - What are the total `sales` by `category` and `year`?
       - What are the total `profit` by `category` and `year`?
       - Which `cities` have generated the highest `sales`?
       - What are the `margins` by `segment`?
       - Make your dashboard look better using a [color palette generator](https://coolors.co/)
    5. Practice by creating another page named `Customer`, and using any chart/table:
       - What is the name of the Customer with the Highest Sales in New York City?
       - What Sub-Category did this Customer buy, and how much Sales and Profit did this Customer generate for the company?
       - Open question: Is the business doing better or worse off from 2014 to 2017?
    
   - Source: Superstore sample data from [Tableau](https://community.tableau.com/s/question/0D54T00000CWeX8SAL/sample-superstore-sales-excelxls)
___
## 10.30 am: Break
___
## 10.50 am: Google Colab and Seaborn
   1. Using either your new Google account or your personal account, open [Google Colab](https://colab.research.google.com/) in another tab
   2. Google Colab's interface and functions:
     - Tools >> Settings >> 
         - Editor >> Show line numbers (check if you prefer)
         - Miscellaneous >> Corgi mode, Kitty mode (turn on if you like)
      - Test with some basic code:
         - Click Connect at top right
         - Write simple definition	
         - Test simple math problem
      - Runtime settings
         - Run cells
         - Reset
      - Code and text cells
      - Save
   3. More about Colab’s Markdown here
   4. Refer to [colab_intro.ipynb](https://github.com/atlas-github/2023fstep25/blob/main/colab_intro.ipynb)
   5. Open a new notebook on [Google Colab](https://colab.research.google.com/)
   6. Try out a few plots on Seaborn:
      - [histplot](https://seaborn.pydata.org/generated/seaborn.histplot.html#seaborn.histplot)
      - [displot](https://seaborn.pydata.org/generated/seaborn.displot.html#seaborn.displot)
      - [boxplot](https://seaborn.pydata.org/generated/seaborn.boxplot.html#seaborn.boxplot)
      - [lmplot](https://seaborn.pydata.org/generated/seaborn.lmplot.html#seaborn.lmplot)
    7. Practice:
      - Load the [CSV](https://docs.google.com/spreadsheets/d/1IaonaJj-c5Ud76Uc9WeRiMSlKLTNnbg-BCUxOoZrXn0/edit?usp=sharing) into Colab
      - Create a [displot](https://seaborn.pydata.org/generated/seaborn.displot.html#seaborn.displot), where x-axis represents `Region`
      - Create a [catplot](https://seaborn.pydata.org/generated/seaborn.catplot.html#seaborn.catplot), where x-axis is `Profit` and y-axis is `Sub-Category`
      - Adjust the size of charts by `sns.set(rc={'figure.figsize':(25.7,8.27)})`
      - Create a [boxplot](https://seaborn.pydata.org/generated/seaborn.boxplot.html#seaborn.boxplot) where x-axis is `Sales`, and y-axis is `Region`
___   
## 12:30 pm: Break
___

## 1:30 pm: [data.gov.my](https://data.gov.my/dashboard)
   1. Using either your new Google account or your personal account, sign up for [Postman](https://www.postman.com/)

___    
## 2:00 pm: Break
___
    
## 2.15 pm: Send emails of weather data using Python
   1. 
    
## 4.15 pm: Wrap up
   1.  Data visualization and coding skills help to automate routine tasks - worth picking up to save time
      - Looker Studio / Power BI
      - [Exam PL-300](https://learn.microsoft.com/en-us/certifications/exams/pl-300/): Microsoft Power BI Data Analyst 
      - [Python Crash Course](https://nostarch.com/pythoncrashcourse2e)
   2. Get certified for cloud computing
      - [Google Cloud](https://cloud.google.com/certification)
      - [Azure](https://docs.microsoft.com/en-us/learn/certifications/)
      - [Amazon Web Services](https://aws.amazon.com/certification/)

