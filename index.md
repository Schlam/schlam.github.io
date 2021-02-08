## Projects

**02/08/21:** Currently updating this page with my most current work,
check back soon for updates

---

### [Predicting $BTC-USD using sentiment from Reddit forums like r/WallStreetBets](/projects/btc.md)

![btc_year](images/btc_forecast_ALL.png)

Unlike the previous renditions, this model predicts behavior using the historical data alone. The performance benefit of synchronizing sentiment with stock trends in the multivariate analysis is nominal and certainly outweighed by the potential for adversarial attack (after inspecting the reddit data used, I noticed some agent was spamming "I love bitcoin :)" in intervals for reasons unknown.) The signal to noise ratio isn't what I'd hoped, but in almost any other context this problem is not as prevelant and seems to be mainly a bitoin thing.

---

### [Analysis, Language Detection, and ETL for Airbnb listings in Rio de Janeiro](/projects/rio.md)

Two notebooks are contained here.

The first shows an end-to-end cloud ETL pipeline on AWS (from S3 to RDS).

The second shows how to predict the language of unlabeled text data using a pretrained model from JohnSnowNLP. I belive this is a BERT model trained in a language-agnostic on various NLI tasks, and later fine-tuned for language prediction. See the ideas section for ideas for the AI/NLP aspect of this project.

The third (currently unfinished) part provides an in-depth analysis of Airbnb data considering this new "language" feature. If you can reasonably associate language with a certian world region, the you could hopefully find answers like:

Are international consumers a significant part of the usership in certain cities?

Are certain listings better at attracting people whose primary language is not english?

Are there patterns in sentiment across diffent languages/world regions?

This could power a number of design aspects at the platform level:

Rank listings shown to a visiting user according to their primary language
Find listings that have extremely negative sentiment reviews and rank them lower
Finally, this data can also be used by investors that seek to use Airbnb as an alternative flow of income by informing certain questions:

Are there differences in spending habits for international users?
Are there ways to name/describe your listing that make them appeal to a wider audience?

---