# weather-DBMS
Weather database management system with simple storm prediction.

W-DBMS is a java application,with integration with an sql database.All the data in the database is manually entered by the user,preferabaly on a daily basis.The UI is pretty basic,and does simple query generation to give info about average rainfall temperature etc.

Storm prediction:
Keeps track of average windspeed and airpressure of a particular region.The average airpressure and windspeed is dynamically compared with recent entries(past few days/hours) to find a trend indicative of an upcoming storm.

Database feature :Capable of handling data from multiple regions.Regions are differentiated by using user generated region code.
