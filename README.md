## Skill involved:
<ol>
  <li>Google BigQuery</li>
  <li>Python Pandas</li>
  <li>Python Visualization, matplotlib</li>
</ol><br>
The dataset has been stored in Google BigQuery project pyquery, and Google API in nPython will be used for connecting to the cloud environment and call the API for query. Finally, the dataset will integreted and some visualizations will be done in Python.
<br><br>

## Background
![image](https://github.com/user-attachments/assets/9947a546-6274-4501-b50d-21bd00876d24) <br>
From the above graph, it is obvious that Chelsea faced a large dropback back in 22/23 Season since the handover to new owner. Regardless of the factor outside the pitch, it is easy to observe that the major reason of the dropback is poor performance in goal scoring. In 22/23 season, Chelsea were having much lower goals and net goals compared to the other Big Six team in PL. Thus, scouting an efficient finisher is the first priority for Chelsea to back in the old glory.
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
![image](https://github.com/user-attachments/assets/1a71a4bb-e89d-45bc-87b6-61b0cd10bbd0)
| Player                | Goal Per Game  | Assist Per Game |
| --------------------- |--------------- | ----------------|
| Randal Kolo Muani     | 0.569620       | 0.421024        |
| Marcus Thuram	        | 0.533729       | 0.233506        |
| Niclas Füllkrug	      | 0.535515       | 0.200818        |
| Christopher Nkunku    | 0.757409       | 0.296378        |
| Amine Gouiri          | 0.512563       | 0.211055        |
| Gonçalo Ramos	        | 0.726240       | 0.322773        |
| Lautaro Martínez      | 0.611948       | 0.240408        |

## Playtime
![image](https://github.com/user-attachments/assets/a2102ea0-9f2e-4bba-a243-c1c57fd4b89e)
![image](https://github.com/user-attachments/assets/f4a6ebbe-31d9-4950-bce8-43ddb0dbcf99)

### Finance
![image](https://github.com/user-attachments/assets/c6f2722e-80a2-4e31-a5c9-139d5d19a2fd)

