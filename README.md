****
MMORPG Legend player behavior data set (MLPBD)
==============================================


1.Data source
====================




The research is based on the data collected from a real MMORPG game “Legend”. In the game, the players have many candidate roles to take part in a team and fight against others to gain virtual currency as a reward. And they also have multiple ways to consume their virtual currency, such as purchasing equipment, upgrading skills, upgrading equipment, sending gift to team members, etc. The UI of the game is shown in Fig.1.
<div align=center>
	<img width="300" height="500" src="https://github.com/game-account-protection/MMORPG-Legend-player-behavior-data-set-MLPBD/blob/master/img-folder/1(1).png"/>
	<img width="300" height="500" src="https://github.com/game-account-protection/MMORPG-Legend-player-behavior-data-set-MLPBD/blob/master/img-folder/2(2).png"/>
</div>
<div align=center><label>Fig. 1. MMORPG “Legend”</label></div>




The data collection process is shown in Fig.2. All the game data and compositions are stored in the game server. When the user login in through network connection to the game, the user’s personal data is searched and return from the game data server to construct its game scenarios in the client end. Therefore, we embed data collection nterfaces in the games servers to collect player’s behavior features, including login habit, fight ability, and consume preference and social behaviors. These features are submit to the detection server to analysis the user behaviors and prevent the account from illegal users. And then volunteers are invited to play games for two weeks, and we abstract 80 records for each user, which recorded the user operation habit and preference.  
![Image text](https://github.com/game-account-protection/MMORPG-Legend-player-behavior-data-set-MLPBD/blob/master/img-folder/2.png)
<div align=center><label>Fig. 2. Data collection model</label></div>

	
2.Introduction  of  player’s  behavior features
====================
The features of the player's behavior are introduced as follows：

<div align=center font-weight:bold><label>Table 2  The  features of player’s behavior</label></div>

|Feature|Description|Unit|
|---|---|---
|pk_acount_average|The number of participated in the battle between players during one unit of time.|Times/hour
|time_length|The online duration time after game login|Hours
|speak_acount_average|The number of messages sent in one unit of time.|Times / hour
|boss_acount_average|The number of challenged game BOSS during one unit of time.|Times/hour
|upgrade_equipment_money_average|The amount of money spent on upgrading the equipment during one unit of time.|Game currency / hour
|improve_skill_money_average|The amount of money spent on upgrading the game skills during one unit of time.|Game currency / hour
|lottery_money_average|The amount of money spent on game gambling during one unit of time.|Game currency / hour
|login_time|The login time  of the player |Time
|hero_decoration_money_average|The amount of money spent on decorative items during one unit of time.|Game currency / hour
|buy_equipment_money_average|The amount of money spent on new equipment during one unit of time.|Game currency / hour
|copies_acount_average|The number of  participated in game copies（a special scene of battle） during one unit of time.|Times/hour
|recharge_acount_average|The amount of money the player recharge the game currency during one unit of time.|Game currency / hour



Taking the first data as an example, the following table shows the corresponding attributes of each value. 

<div align=center><label>Table 3  An example of the data</label></div>

|login_time|time_length|recharge_acount_average|boss_acount_average|pk_acount_average|copies_acount_average|buy_equipment_money_average|upgrade_equipment_money_average|improve_skill_money_average|hero_decoration_money_average|lottery_money_average|speak_acount_average|label|
|---|---|---|---|---|---|---|---|---|---|---|---|---
|14:02|2.33|0.00|5.00|5.00|40.00|0.00|100.00|60.00|0.00|20.00|13.00|1.00 
****
