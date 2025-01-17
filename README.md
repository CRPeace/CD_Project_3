# Movie Data Analysis, Hypothesis Testing and Data Visualizations
---
### Analysis and statistical testing of select factors that contributed to the financial success of US movies 2000-2022.
---
### <mark>**Quick Summary** 
* The analysis revealed that ***movies rated for general audiences (G to PG-13) financially outperformed movies for mature audiences.***
*  The analysis revealed the ***specific revenue drop during 2020-2021 due the pandemic*** when compared to 2018-2019.
* The analysis also suggests that ***the specific words used in a movie's title do not affect revenue in a statistically significant way.***
---

### Data Background:
* ### This project uses data from [IMDB](https://www.imdb.com/) (Internet Movie Database), combined with data obtained via API from [TMDB](https://www.themoviedb.org/?language=en-US) (The Move Database).
* ### The data were combined, cleaned, and filtered to select movies released in the US during the period 2000-2022, where sufficient financial data were present.
    
## Data Visualizations
![](https://github.com/CRPeace/Movie_Data_API_Stats_Analysis/blob/main/Data%20Viz/Median%20Movie%20Revenue%20by%20Rating.png)

* This visualization displays median revenue when the movies are grouped by MPAA rating.  We can see that movies for general audiences vastly outperform movies for mature audiences.  
* A Kruskal-Wallis ANOVA revealed the findings were statistically significant.
---
![](https://github.com/CRPeace/Movie_Data_API_Stats_Analysis/blob/main/Data%20Viz/Movie%20Title%20Samples.png)
* This visualization shows that movies that include common words in their titles (excluding words such as 'and', 'of', 'the', etc.) performed equally as well as movies whose titles used words less common in the dataset.
* An ANOVA revealed the findings were not statistically significant.
---
![](https://github.com/CRPeace/Movie_Data_API_Stats_Analysis/blob/main/Data%20Viz/Pandemic%20Effect.png)
* This visualization highlights the dramatic loss in average revenue due to the COVID-19 pandemic.

![](https://github.com/CRPeace/Movie_Data_API_Stats_Analysis/blob/main/Data%20Viz/Number%20Release%20per%20Year%20by%20Rating.png)
* This visualization shows the number of releases per year by rating

---
### For further information

For any additional questions, please contact CPeaceData@gmail.com
