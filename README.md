Tento kód predstavuje praktickú časť bakalárskej práce v oblasti umelej inteligencie, nazývanej "Porovnanie rôznych metód vysvetliteľnosti modelov umelej inteligencie na zvolenej množine dát"

Hlavným cieľom tejto práce je zvýšiť dôveru ľudí voči systémom umelej inteligencie pomocou metód Explainable AI (XAI). 

Na tento účel bol vyvinutý model umelej inteligencie, založený na dátach <a href="https://www.kaggle.com/datasets/averkiyoliabev/home-equity-line-of-creditheloc?resource=download">HELOC</a> od spoločnosti <a href="https://community.fico.com/s/explainable-machine-learning-challenge">FICO</a>, a jeho výsledky boli analyzované pomocou metód XAI, aby sa zabezpečilo pochopenie a vysvetlenie rozhodnutí prijatých modelom.

<br>

Praktická časť zahŕňa dva oddiely:

- bp_xai.ipynb: obsahuje hlavný kód na analýzu údajov HELOC (heloc.csv), trénovanie modelu XGBoost, použitie metód XAI a objektívnych metrík na ich hodnotenie.

- survey_analyse.ipynb: obsahuje kód na analýzu výsledkov prieskumu (survey_results.csv) na hodnotenie XAI pomocou subjektívnych metrík.
