ssh axif570@login.toolforge.org
become scribe-server
show databases;
CREATE DATABASE s55569__scribe_server_p;
USE s55569__scribe_server_p;
show tables;

HY9it939py7hv7Bq

cat config.yaml
sql tools
SELECT SUBSTRING_INDEX(CURRENT_USER(), '@', 1);
show databases;

chmod +x start-script.sh
toolforge webservice stop
git pull origin main
go build -o Scribe-Server .
toolforge webservice --mem 4Gi --cpu 2 jdk17 start /data/project/scribe-server/Scribe-Server/start-script.sh
 
