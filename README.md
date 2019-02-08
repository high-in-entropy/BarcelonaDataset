# BarcelonaDataset
This repository aims at analyzing various datasets which are published under Barcelona Datasets in Kaggle.
At first we will analyse the accidents dataset [2017]. 

# Some of the major inferences we derived out of the data are as follows :

* Fridays record the most number of accidents almost 0.95(STD) above the average accidents per weak.
* Saturday, Sunday encounter the least. Sunday lower among the both. What might be the reason? No Jobs ? Not sure. Sundays also mean more amount of outings. But still, since weekends are seeing a sudden decline in number of accidents, it might be due to no job goers.
* Interestingly, all the days in the week follow almost a similar distribution of accidents during afternoon, morning, and night. This distribution is nearly [50,40,10]% respectively.
* This also means afternoons are more prone to accidents.
* For analysis, a month was divided into 4 quarters. The first 3 quarters registered almost similar proportion of accidents however, the 4th quarter saw a sudden increase in the number of accidents.
* By following the above discussion we can say Week 4 Friday Afternoons are more prone to witness a small or big accident.
* If we look only the "Serious Accidents" data we see that nights actually witness more proportion of serious injuries than afternoons and morning.
* Mornings witness the least, maybe due to attentive minds of drivers during morning.
* Interestingly, although sundays are less prone to accidents in general, they witness more proportion of serious accidents than any other day. 

## There are some DataFrames we came across, which were giving deceptive results. More indepth analysis had to be performed to gain proper insights out of them. This is what statisticians call "Simpson's Paradox". In this notebook you see several times this paradox blinding us from the reality.

So next time you are in Barcelona, remember, 4th week Friday afternoons are more prone to accidents. Also remember, if you're out at night on a sunday, you are at more risk of having to face a "Serious Accident"! Take care:)
