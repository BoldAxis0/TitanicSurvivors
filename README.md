# TitanicSurvivors
Basic ML algorithms on the Titanic survivors dataset 

Current Top Score -> Random Forests with just Fare -> 70%

Other Scores: 

Log Reg with just fare -> 64%

Log Reg with fare + Pclass -> 69% (good growth, probably means log reg performs better with higher dimentional data)

Random Forests with Fare and Pclass -> 69% (slight decay, maybe attributable to randomness. In any case, more data/dimensions doesnt improve Random Forests, it seems)

Could try next -> other algorithms, using more fields (preferably numeric, not categorical), working NN sometime in the future
How much accuracy is too much accuracy?

Should probably measure performance using cross validation, and only use test for final analysis, to prevent chances of indirect overfitting through my own finetuning? but this is my first project so its okay for now. Someday we will revisit this and do better.  

I post my solutions file for this problem directly to the Kaggle competition(https://www.kaggle.com/competitions/titanic/overview), so scores are based directly on their test dataset solutions.
