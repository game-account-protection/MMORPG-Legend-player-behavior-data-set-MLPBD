****
MMORPG Legend player behavior data set (MLPBD)
==============================================


1.Data source
====================




The research is based on the data collected from a real MMORPG game “Legend”. In the game, the players have many candidate roles to take part in a team and fight against others to gain virtual currency as a reward. And they also have multiple ways to consume their virtual currency, such as purchasing equipment, upgrading skills, upgrading equipment, sending gift to team members, etc. The UI of the game is shown in Fig.1.
(<div align=left><img width="150" height="300" src="https://github.com/game-account-protection/MMORPG-Legend-player-behavior-data-set-MLPBD/blob/master/img-folder/1(1).png"/></div>)
(<div align=right><img width="150" height="300" src="https://github.com/game-account-protection/MMORPG-Legend-player-behavior-data-set-MLPBD/blob/master/img-folder/2(2).png"/></div>)


 


The data collection process is shown in Fig.2. All the game data and compositions are stored in the game server. When the user login in through network connection to the game, the user’s personal data is searched and return from the game data server to construct its game scenarios in the client end. Therefore, we embed data collection nterfaces in the games servers to collect player’s behavior features, including login habit, fight ability, and consume preference and social behaviors. These features are submit to the detection server to analysis the user behaviors and prevent the account from illegal users. And then volunteers are invited to play games for two weeks, and we abstract 80 records for each user, which recorded the user operation habit and preference.  
![Image text](https://github.com/game-account-protection/MMORPG-Legend-player-behavior-data-set-MLPBD/blob/master/img-folder/2.png)
	
2.Introduction  of  player’s  behavior features
====================


Taking the first data as an example, the following table shows the corresponding attributes of each value. The unit of the attribute and its meaning have already been introduced in the paper.




	

|login_time|time_length|recharge_acount_average|boss_acount_average|pk_acount_average|copies_acount_average|buy_equipment_money_average|upgrade_equipment_money_average|improve_skill_money_average|hero_decoration_money_average|lottery_money_average|speak_acount_average|label|
|---|---|---|---|---|---|---|---|---|---|---|---|---
|14:02|2.33|0.00|5.00|5.00|40.00|0.00|100.00|60.00|0.00|20.00|13.00|1.00 
****
