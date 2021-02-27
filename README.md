# Survival-Analysis
## Abstract
Basketball players have been prominent figures in social media. People often talk about
their career in the field. Our project focuses on the questions: does round of drafting have an
influence on the players’ longevity of their career? How does position have an influence on the
players’ longevity of their career? Overall how does our covariates affect career length
changed over time? We build a Cox proportional Hazards model to see if there is a significant
difference between players who are round draft and players who are picked elsewhere.
## Data source and Background information
https://www.basketball-reference.com/
 Our data mainly focus on the NBA dataset which center around 1998 (Vince Carter’s draft
class), 2004 (Lebron/carmelo’s draft class) and lastly 2009 - Steph Curry, James Harden draft
class.
We have three fixed covariates: draft year of the player, position of the player on the team, and
lastly draft round, an estimated of the player’s skill on the game.
The variables are: draft year of the player (1998 ,2003 ,2009), position of the player on the team
(Consolidated positions into Smalls (guards) and Bigs (everyone else), draft round, skill of the
player (1 or 2) to proxy for skill
We consider an observation to be censored if the player is still active, or if they have played
fewer than five games in the NBA. Our research question is concerned primarily of the career
length of players who have made a living as a professional basketball player, which is not the
case if they were cut from the NBA before 5 games. Then our dataset contains 165 players, 31 of
whom are censored.
## Research Question
We are interested in how long does NBA careers last. What degrees does, does the round of the
player, the position of the player and lastly draft year impact career length of the player impact
on career length?
Moreover, we are interested in whether there is a relationship between NBA careers duration and
these covariates, then we predict the NBA careers given their covariates combination.
