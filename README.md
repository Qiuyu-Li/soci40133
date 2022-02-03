# Assignments for SOCI 40133 - Computational Content Analysis

## Data for Week 2: Twitter misogyny

I intend to explore social media misogyny, with scrapped tweets as the primary data.

In [Maloney (2021)](https://www.economics.uci.edu/files/docs/2021/gradjobmarket/maloney_elizabeth.pdf), the author exploited google search terms as the data source for exploring misogyny. She used 12 words/phrases as the keywords for identifying misogyny, and classifyed these keywords into 4 categories. Specifically, the keywords are:

1. Derogatory: bitch, cunt, whore, thot, twat;
2. Manosphere: misandry, men's rights, sjw;
3. Violent: rape, gangbang;
4. Reactionary: sexual harassment; workplace harassment.

In this project, I plan to collect tweets containing the above keywords with the `snscrape` package. To make my life easier, for now I will only use one keyword ("bitch", "misandry", "rape", "harassment") in each category, and only collect 1000 tweets with each keyword. I may expand the dataset in the final project.

## Data for Week 3: Politically skewed media

I scrapped 1,000 tweets under the account of "CNN", "BBC", and "Fox News", and played around with the techniques and tools I learned from this week.
