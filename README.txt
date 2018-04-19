Project Idea: 
In Eubacteria, the sigma factor (σ) binds with the RNA polymerase subunit (αββ 0 ω) to create RNA polymerase. 
Being part of the RNA polymerase holoenzyme, the sigma element acts as the connection between RNA polymerase and DNA. 
Thus, affinity between the RNA polymerase and DNA is mainly attributed to the bound sigma element. 
The goal of the competition is to predict the binding of an RNA polymerase with a given sigma factor to a DNA sequence.

There are a total of five sigma factors in the dataset (RPOS, RPOD, RPOH, RPON, RPOF). 
The final scoring metric is the averaged AUC over all the sigma factors. 
Thus, predictions which might be very good for one sigma factor (e.g. AUC of 0.80) and bad for other sigma factors (e.g. AUC of 0.50) will result in an overall poor score. 
Considering the dataset, it would be surprising if scores would reach as high as 0.80.


Source: 
kaggle.
https://www.kaggle.com/c/promoter-site-prediction
