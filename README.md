# Movie Data Analysis

### Overview

<img src="microsoft.png" width="600" height="600" align="center"/>

This project analyzes film data with respect to the genres, budgets and release dates. The data is primarily sourced from two formats, one a CSV and the other a database. Analysis of the data will demonstrate that select genres rate higher than others, the production for these select genres and that certain months are more ideal for a film premier. Microsoft can use these insights to select genres, plan their budgets and set release dates for their films.

### Business Problem

<img src="cinema1.jpeg" width="600" height="600" align="center"/>

A stakeholder needs data driven recommendations for Microsoft's new movie studio. Microsoft does not have industry experience in financing, producing or releasing films and therefore needs direction. Three recommendations formulated from film-based data are proposed to address these issues so Microsoft can confidently navigate the film industry.

### Data Understanding

<img src="film_data.png" width="600" height="600" align="center"/>

IMDB data from [IMDB](http://www.imdb.com) stored in a SQLite database is used for analysis and contains films from 2010 to 2019. Tables movie_basics and movie_ratings are joined together to provide insight regarding genres and average ratings. A CSV movie budgets document from [The Numbers](https://www.the-numbers.com) is also used for analysis and contains films from 1975 to 2016. This document includes film data for release date, production budget, worldwide gross, etc.

![avg_rating_genre](https://user-images.githubusercontent.com/96359837/190866641-62cb75cc-9032-454a-b86f-6c244ae268ba.png)

### Analysis

As can be seen above, the genres with the highest ratings are short films, documentaries, game-shows, news, biography, music, history and sport, before noticeably decreasing in average rating. Although Microsoft cannot control the consumer's response to a film, Microsoft can focus their efforts on genres which are more receptive compared to other genres. Strategically, Microsoft should first focus on making short films, which are likelier to have favorable ratings, to establish credibility. Microsoft should then produce documentaries to maintain high ratings.

Financially speaking, the aforementioned films are relatively less costly to produce than block-buster films and therefore less risky. Subsequently, if these films prove successful, it is only then that Microsoft should produce a blockbuster film, such as a history-based film. By then, Microsoft will have garnered high ratings and earned the loyalty of their audiences so their box office earnings should prove promising.


**This rating metric should be considered in light of not having data available on box office by genre which requires further analysis**

### Recommendation
*Based on this analysis, Microsoft's first film should be a short film followed by a documentary, both of which are likely to rate favorably. This will establish Microsoft's credibility and earn them viewers which leads to consumer loyalty translating to recurring revenue.*

![prod_budget](https://user-images.githubusercontent.com/96359837/190866739-7d57f79c-aa58-4996-892f-048d0ac189d0.png)


### Analysis
No outliers in the graph above demonstrates that these blockbuster production budgets are not factored into the new non-blockbuster production budget median. This boxplot shows the production budget median at 13 million and the 25th percentile at 400,000 and the 75th percentile at 30 million.

### Recommendation
*According to the median of these non-blockbuster production budgets, the recommended budget for short films and documentaries is 13 million USD.*

![roi_release_date](https://user-images.githubusercontent.com/96359837/190866818-af3832ff-19e4-4d20-a98d-c051134a0ef1.png)

### Analysis

As can be seen above, the months with the highest ROI median are July, June, November and May. Therefore, Microsoft should release their films during these four months.
These findings align with typical consumer behavior since the summer months are usually when most consumers go shopping because of nicer weather. Also, November is a month associated with peak holiday shopping at malls and commercial centers, so shoppers are likelier to stop by the cinema to watch a film.

### Recommendation
*According to this analysis, Microsoft should release their films in July, June, November and May.*

### Conclusions

In summation, the three recommendations Microsoft should implement for their new movie studio are:
* The first few films should be low-budget short films or documentaries before producing a block-buster film
* The production budget for these low-budget films should be 13 million dollars, give or take
* The release dates of these films should be in July, June, November or May

### Next Steps

Further analysis to better understand the film industry to improve recommendations:
* **The trend of the production budget over the last few decades**. Are films becoming more or less costly to produce? 
* **Films in a language other than English**. Are there any languages which are growing in popularity with respect to highly rated films?
* **The effect, if any, a film's run time has on ratings**. Do longer films have higher ratings because they allow greater time to tell a more cohesive story?
