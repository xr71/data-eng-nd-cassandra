# Apache Cassandra Data Modeling Project for Udacity Data Engineering Nanodegree

This project leverages Apache Cassandra to model a NoSQL database in order to answer key analytical questions for Sparkify, a music streaming service. 

## Database Design
* Three different tables answering different analytical questions
  * artist_song
  * user_artist_sort_song
  * user_song 
* Three three tables make different use of PRIMARY KEY (partition and clustering)


## Instructions
This notebook was developed locally in a Cassandra Docker Container.  
If you do not have a Cassandra server with development access and would like to re-run using Docker locally, please run this command first:
```
(sudo) docker run -p 127.0.0.1:32779:9042 --name cassandra -d cassandra:latest
```

Make note here that the default Cassandra port of 9042 is mapped locally to port 32779 in my Docker container. 

After your container is up and running, please proceed to run through the Project IPython Notebook to understand the various schema DDL's, insertions, and analytical queries. 

All query descriptions are written in the notebook and table designs are modeled after the user needs.