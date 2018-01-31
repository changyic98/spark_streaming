# spark_streaming 
## File describtion 
Local streaming is using two local treads. Spark can do wordcount on the input of another tread.

new streaming is using web scrabing to get the headline of CNN last 50 news with certain keyword. The data is pulled locally and stored in a txt file under log dir. Spark streaming regularly check the new file that generated in this folder and do wordcount. 
## Environment setup
python 2.7

pyspark 2.2.1
