# TP-Ecobici-using-R-and-Power BI
Final project of Data Science elective course @UBA as part of my Engineering degree

You may find attached (https://github.com/blascasado/TP-Ecobici-using-R-/blob/main/CDD%20Trabajo%20de%20aplicaci%C3%B3n.pdf) the final project document in which the devolpment and the algorithms applied are explained. At end you may find the R language code used.

The main objective of the project was to do a clustering of the bicycle trips from the Ecobici system in the year 2018. EcoBici is a station-based bicycle-sharing system in Buenos Aires, Argentina which began operating in 2010. The service is free of charge to both residents of the city and tourists, and is available 24 hours a day. The government of Buenos Aires city has an open data website (https://data.buenosaires.gob.ar/dataset/) where you can dowload +500 free datasets of different topics. For this project we used the trips from 2018 (http://cdn.buenosaires.gob.ar/datosabiertos/datasets/bicicletas-publicas/recorridos-realizados-2018.csv). We also did a JOINT of this database with a historical climate database from the year 2018 as to consider this variables in the clustering too. To do the clustering we used two different algorithms: K-MEANS and CLARA. After running both algothims we defined a number of ten groups and compared them as to finally reach to conclusions in which algorithm was more useful for this case. The final objective was to have this segments of trips identified as to do a better realocation of the bicycles considering the climate conditions and the location of the stations. 

