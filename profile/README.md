<img
  src="shoes.jpeg"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">


# Git Shoes!


## Project Description
This is a Natural Language Processing project that undertakes the task of predicting the main coding language used in repositories. In particular, we have chosen to go through 100+ repositories that are the related to shoes and are the "most starred". It is being conducted at Codeup, Data Science programme, Noether cohort, March 2023.


## Initial Thoughts
Intial thoughs is that Java will be the most common language, followed by python. As for the predictory words, shoe company brands or shoe types will be the most common words.

## The Plan
1. Acquire data
2. Initial exploration.
3. Clean data.
4. Create questions.
5. Split data.
6. Explore data on train set.
7. Model using Classification.


## Data Dictionary
| Feature | Definition |
| :-- | :-- |
| repo | repository of readme file |
| readme_contents | text content of readme file |
| clean | text content cleaned by: <br> - lowercase all words,<br> - unicode "NKFD",<br> - encode "ASCII", <br> - decode "UTF-8" |
| stemmed | all text from the "clean" column stemmed | 
| lemmatized |  all text from the "clean" column lemmatized |


## Acquire
- Data acquired from Github.
  - Query for 'shoes' in search bar. Filter by 'Most Stars'.
- 198 Readme files acquired.
- Each row represents a repository.
- Columns represent the repository, language, and readme contents.


## Prepare
- Dropped nulls. 
  - 13 values dropped.
- Cleaned text contents:
  - lowercased
  - unicode "NKFD"
  - encode "ASCII", decode "UTF-8"
- Create stemmed and lemmatized columns.
- Split into train, validate, and test sets (56/24/20).


## Explore
- Search for most common words.
- Use bigrams and trigrams to find text trends. 
- Create bar plots and word plots to visual trends.


## Conclusion


## Next Steps


## Steps to Reproduce
1. Clone this Repo.
2. Use functions in acquire.py file.
3. Use functions in prepare.py to clean and prep data.
4. Use same configurations for models.


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
