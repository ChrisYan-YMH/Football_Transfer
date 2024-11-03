## Skill involved:
<ol>
  <li>Google BigQuery (SQL)</li>
  <li>Python Pandas</li>
  <li>Python Visualization, matplotlib & seaborn</li>
  <li>Python Google API</li>
</ol><br>

The dataset has been stored in Google BigQuery project pyquery, and Google API in nPython will be used for connecting to the cloud environment and call the API for query _**(FootballTransfer.ipynb)**_. Finally, the dataset will integreted and some visualizations will be done in Python _**(TopScorer_Viz.ipynb)**_.
<br><br>

## Background
![image](https://github.com/user-attachments/assets/91070d9c-b689-410f-bfe8-83538ea07f6a) <br>
From the above graph, it is obvious that Chelsea faced a large dropback back in 22/23 Season since the handover to new owner. Regardless of the factor outside the pitch, it is easy to observe that the major reason of the dropback is poor performance in goal scoring, the continous absence of certain players due to injury also plays a big role here. In 22/23 season, Chelsea were having much lower goals and net goals compared to the other Big Six team in PL. Thus, scouting an efficient finisher, also with good health record, is the first priority for Chelsea to back in the competition.
<br><br>

## Project Aim
This project aims to find a good striker for Chelsea FC which have been not efficient and clincial in front of goal
<br><br>

## Data Description
The timeframe of the dataset used in this project is until **22/23 season**. <br>
Source: https://www.kaggle.com/datasets/davidcariboo/player-scores
<img width="533" alt="image" src="https://github.com/user-attachments/assets/9c5bd3b6-0b54-4375-92cc-06643244b5db">
<br><br>

## Methodology
The whole dataset will first be consolidated into one table TopLeaguePlayer which consists of front line players with follwing details in the top 6 football league in the world (Premier League, Bundesliga, La Liga, Ligue 1, Serie A, Liga Portugal) in only 19/20, 20/21, 21/22 and 22/23 season.
<ol>
<li>Player Personal Details - Name, Age, Club, Preferred foot, Height, Main position, Sub position</li>
<li>Player Match Stats - Goals per season, Assists per season, Yellow cards per season, Red cards per season</li>
<li>Market Valuation</li>
</ol><br>
Then, Assist Per Game and Goal Per Game will be calculated as the metrics used for evaluation of his output as a striker. With consideration of money cost as well as the age, top 13 front players will be selected out for further evaluation.
<br><br>

## Result
### Performance
![image](https://github.com/user-attachments/assets/1a71a4bb-e89d-45bc-87b6-61b0cd10bbd0) <br>
In term of goal per game and assist per game, only player whose goal per game is higher than the median will be selected, here is the list of player: <br>
| Player                | Goal Per Game  | Assist Per Game |
| --------------------- |--------------- | ----------------|
| Randal Kolo Muani     | 0.569620       | 0.421024        |
| Marcus Thuram	        | 0.533729       | 0.233506        |
| Niclas Füllkrug	      | 0.535515       | 0.200818        |
| Christopher Nkunku    | 0.757409       | 0.296378        |
| Amine Gouiri          | 0.512563       | 0.211055        |
| Gonçalo Ramos	        | 0.726240       | 0.322773        |
| Lautaro Martínez      | 0.611948       | 0.240408        |


## Playtime & Finance
![image](https://github.com/user-attachments/assets/0c6bed8b-701a-4cfe-a7c5-739ea31b8e8f) <br>
Christopher Nkunku had a quit bad attendtance rate in his club career, only around 60% which can be considered a great risk with his price tag ($80M) depsite his excellent performance on the pitch. <br><br>
Lautaro Martínez can be a good choice. However, with such price tag, this purchase can be risky considering the attendance rate and its assist per game. <br>
The Final List of Player: <br>
|Rank | Player                | Goal Per Game  | Assist Per Game| Market Value        | Attendance Rate  | Age |
| --- | --------------------- |--------------- | ----------------| ------------------ | ---------------- | --- |
| 1   | Randal Kolo Muani     | 0.569620       | 0.421024        | 80000000.0         | 0.865033         | 24  |
| 2   | Marcus Thuram	        | 0.533729       | 0.233506        | 32000000.0         | 0.822876         | 25  |
| 3   | Niclas Füllkrug	      | 0.535515       | 0.200818        | 13000000.0         | 0.810131         | 29  |
| 4   | Amine Gouiri          | 0.512563       | 0.211055        | 35000000.0         | 0.901634         | 21  |
| 5   | Gonçalo Ramos	        | 0.726240       | 0.322773        | 50000000.0         | 0.753595         | 22  |

### Conclusioin & Action Plan
| Plan | Main Player       | Subsitute Player            | Expenditure  |
| -----| ----------------- | --------------------------- | ------------ |
| A    | Randal Kolo Muani | Amine Gouiri/ Gonçalo Ramos | 115M to 130M |
| B    | Marcus Thuram     | Amine Gouiri/ Gonçalo Ramos | 67M to 82M   |
| C    | Niclas Füllkrug   | Amine Gouiri/ Gonçalo Ramos | 48M to 63M   | 

Randal Kolo Muani will be my first choice with decent goal, assist per game and attendance rate. Marcus Thuram can be his back-up if Randal Kolo Muani deal collapse.<br>
For the players at rank 3 or below, they can be the second purchase and serve as a substitue of either Randal Kolo Muani or Marcus Thuram during the season to grow to be better for future main player or resale. <br>

