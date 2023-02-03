# SQL-Golden-Era-for-Games
## This is the data that has been downloaded from kaggle.com. In this project we will use Games data to analyze the Data of Games,Gamers and Reviewers.
 ![Golden era of ganes](https://github.com/agajan1197/SQL--Golden-Era-for-Games/blob/fe55ca91caa1627426da1128412e2d8f2fa0f151/Screenshot%202566-02-02%20at%2018.37.00.png)
 ## 1.Firstly let's have a look at top 10 games.
 ### we can decide that these are top 10 games by ordering them by number of games sold.
 ![Query of top 10 games](https://github.com/agajan1197/SQL--Golden-Era-for-Games/blob/fe55ca91caa1627426da1128412e2d8f2fa0f151/Screenshot%202566-02-02%20at%2018.38.09.png)
 ## 2.Years that game reviewers have loved
 ### In this query I have joined game_sales table with reviews. By doing that I was able to Query years and reviews of gamers together
 ![Game reviewers](https://github.com/agajan1197/SQL--Golden-Era-for-Games/blob/fe55ca91caa1627426da1128412e2d8f2fa0f151/Screenshot%202566-02-02%20at%2018.39.21.png)
 ## 3.In the next query we will look at the top rated years with more than 4 games a year
 ### The reason we are doing it is because some years have only 1 game in a year, I think it wouldn’t be a good idea to put the year with less games at the top.
 ![](https://github.com/agajan1197/SQL--Golden-Era-for-Games/blob/fe55ca91caa1627426da1128412e2d8f2fa0f151/Screenshot%202566-02-02%20at%2018.39.43.png)
 ## 4. Now let's have a look at years that got dropped from the rankings
 ### At the 3rd query we dropped the years which had less than a 4 games a year, now let's have a look at what years have been droppped
 ![](https://github.com/agajan1197/SQL--Golden-Era-for-Games/blob/fe55ca91caa1627426da1128412e2d8f2fa0f151/Screenshot%202566-02-02%20at%2018.40.02.png)
 ## 5. Now let's have a look at the years where game players loved
 ### In this query the scores are given by video games players 
 ![](https://github.com/agajan1197/SQL--Golden-Era-for-Games/blob/fe55ca91caa1627426da1128412e2d8f2fa0f151/Screenshot%202566-02-02%20at%2018.40.26.png)
 ## 6. Years that both video game players and reviewers like 
 ### In this query we have used "intersect" command to query the years that exists in both top_critic_years_more_than_four_games and top_user_years_more_than_four_games
 ![](https://github.com/agajan1197/SQL--Golden-Era-for-Games/blob/fe55ca91caa1627426da1128412e2d8f2fa0f151/Screenshot%202566-02-02%20at%2018.40.57.png)
 
 ## 7. Sales of the best games.
 ### After analysing the data we came to conclusion that 2008,1998,2002 are best years as years are both in top rankings of reviewers and gamers.Now let's look at sales of that particular years.
 ![](https://github.com/agajan1197/SQL--Golden-Era-for-Games/blob/fe55ca91caa1627426da1128412e2d8f2fa0f151/Screenshot%202566-02-02%20at%2018.41.24.png)
