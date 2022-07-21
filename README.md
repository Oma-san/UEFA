# (Data exploration of Top flight football teams in Europe)
## by (Omasan Akperi)


## Dataset

> This dataset contains the points that each team in the top 6 leagues in Europe got between 2014 and 2019 and other metrics of the teams in the top flight in that period. The data was gotten from kaggle (https://www.kaggle.com/datasets/slehkyi/extended-football-stats-for-european-leagues-xg)


## Summary of Findings

> The distribution of goals scored, wins and points were right skewed, while the distribution of loses and goals conceded are normal distributions

> As expected, pts had a very positive relationship with pts_per_game, wins, scored and passes but points had a negative relationship with loses, conceded, passes allowed and ppda_coef. The most points were gathered in the EPL when considering just points but when it is considered that some leagues play more matches than others, so there would be chances for more points in some leagues when compared to the others, the point per match plot shows that all the leagues have similar points. This same analogy goes for win, scored, loses and conceded. The Bundesliga and RFPL are at a disadvantage because they play less matches, so they win less and lose less, so new per match features were engineered and plotted and it was discovered that all the leagues had similar points, wins and loses per match but more goals were scored and conceded on average in the Bundesliga while the RFPL had less goals scored and conceded,

> The points gotten directly correlated with wins, regardless of the league or year but the correlation of points with goals scored was not as strong because it takes more than scoring goals to get points!

> It was interesting that the EPL had more passes close to the opponents goal than the other leagues.

> The most crucial predictor of points was win, followed by scored, and then passes and the passes feature is interesting; this means that the more passes are made close to the opponents goal, the higher the chances that a goal would be scored and the more goals are scored, the higher the chances that there would be a win.


## Key Insights for Presentation

> The distribution of both wins and goals scored is skewed to the right, most teams score between 25 and 60 goals per year, while the best teams score over 100 goals and the same goes for wins, most teams win between 7 and 17 matches but the best teams win around 30 matches.

> The most important factor that gives a team more points is wins, the more a team wins, the more points it gets and the more it loses, the less point it gets.

> Another important factor is goals scored, the more goals the team scores the more it is likely to win and the more it is likely to win, the more points it gets.

> Passes closes to the opposition box is another important factor; it the team has more passes close to the opponent's goal, then the team is more likely to score and win and get points but if the team allow the opponent to pass the ball close to its goal then it is more likely to lose.

> The EPL has more passes close to the opponents goal than the other leagues.