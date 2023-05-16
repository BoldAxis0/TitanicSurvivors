# TitanicSurvivors
Basic ML algorithms of the Titanic survivors dataset 

Current Top Score -> Random Forests with just Fare -> 70%

Other Scores: 

Log Reg with just fare -> 64%

Log Reg with fare + Pclass -> 69% (good growth, probably means log reg performs better with higher dimentional data)

Random Forests with Fare and Pclass -> 69% (slight decay, maybe attributable to randomness. In any case, more data/dimensions doesnt improve Random Forests, it seems)

Next to try -> other algorithms, using more fields (preferably numeric, not categorical), working NN sometime in the future
How much accuracy is too much accuracy?

Should probably measure performance on a subset of training, and only use test for final analysis, to prevent chances of indirect overfitting through my own finetuning? 

Nah, we'll think about overfitting later. 

