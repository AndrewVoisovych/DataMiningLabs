# DataMiningLabs
Repository for Data Mining Labs

# Overview
**Football Data: Expected Goals and Other Metrics (2014-2019)** <br>
Даний набір містить статистичні зведені дані про футбольні команди та їх ігри до кінця кожного футбольного сезону, починаючи з 2014 року, для топ 5 ліг УЄФА. <br>
La Liga, EPL, BundesLiga, Seria A, Ligue 1 <br><br>
Цей набір даних допомагає зрозуміти гру футбольних команд за певними наборами статистичних даних, та передбачити майбутні результати. Що власне й роблять, до прикладу, букмекерські контори. 
В стандартні параметри входять: позиція команди по сезону, команда, кількість матчів, перемоги, нічиї, поразки, забиті голи, пропущені голи та набрані очки. А також інші додаткові метрики.

**Додаткові метрики:**
* xG - expected goals metric, it is a statistical measure of the quality of chances created and conceded. 
    * показник очікуваних голів, це статистичний показник якості створених та пропущених шансів
* xG_diff - difference between actual goals scored and expected goals.
    * різниця між реально забитими і очікуваними голами
* npxG - expected goals without penalties and own goals.
    * очікувані голи без пенальті та автоголів.
* xGA - expected goals against.
    * очікувані голи противника
* xGA_diff - difference between actual goals missed and expected goals against.
    * різниця між пропущеними та очікуваними голами противника
* npxGA - expected goals against without penalties and own goals.
    * очікувані голи противника без пенальті та автоголів
* npxGD - difference between "for" and "against" expected goals without penalties and own goals.
    * різниця між npxG і npxGA
* ppda_coef - passes allowed per defensive action in the opposition half (power of pressure)
    * сила пресингу, чим нижче значення, тим вище рівень інтенсивності пресинга ( не менше 40 метрів від воріт)
* oppda_coef - opponent passes allowed per defensive action in the opposition half (power of opponent's pressure)
    * чим вище тим краще, скільки противник дозволяє робити передач після втрати. (пресинг противника)
* deep - passes completed within an estimated 20 yards of goal (crosses excluded)
    * скільки раз успішно доставили м’яч у 18 метрів від воріт ( без  навісів)
* deep_allowed - opponent passes completed within an estimated 20 yards of goal (crosses excluded)
    * скільки раз успішно супровтикник доставив м’яч у 18 метрів від воріт( без навісів)
* xpts - expected points
    * очікувані очки
* xpts_diff - difference between actual and expected points
    * різниця очікуваних очків та набраних
    
## XG    
Очікувані голи (xG) – це нова революційна футбольна метрика, яка дозволяє оцінювати продуктивність команди та гравця.
У грі з низькою кількістю очок, таких як футбол, підсумковий рахунок не дає чіткої картини продуктивності.
Ось чому все більше і більше спортивних аналітиків звертаються до передових моделей, як xG, що є статистичним показником якості створених і упущених шансів.
    
