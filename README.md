# BigdataE2E_Project
It is a POC for interview point of view
01fetchApi folder

1)python File featch the data from the api 
2)Load the data in json formate in output.json


02filterData folder

1)load the data from outPut.json and filtered in to required formate
2)Filtered data is dump in to filtered_data.json

03spark folder

1)Read the data from filtered_data.json
2)connecting with  sqlLite server
3)copy the sqlite-jdbc-3.30.3.jar to ~/.local/lib/python3.8/site-packages/pyspark/jars/
4)test db is created with required table formate

04graphApi

1) server start
2)query is selected for ploting graph
3)Connecting with test db 
4)From the input of HTML dropdown we need to query the data from the DB
5)Converting as json value 
 

05Visulization
1) Index html is created and importing highChars api
2)Import the Bootstrap cdn
3)using the click events a action is triggred to fach the quesy table and show as numeric ponts X and Y asix
4)To view the graph we need to open the index.html change the drop down to view differnt graph




Note 

1) I try to scheduled the job in Airflow but i dont have enough time to learn and to implement with in one day
2) I know Oozie for scheduled job 

Thanks


