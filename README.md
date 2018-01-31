# slackr
Slackr

Setup

** Application can only run on OSX **

1. Git clone repo
2. docker-compose up -d
3. pip install slackr (Recommend using a virtualenv)
4. Open Kibana and verify interface is available at http://localhost:5601
5. Run the python init file under slackr. (Use nohup to demonize -- EG: nohup python __init__.py)
6. Click on kibana dashboard "Slackr" to view your app usages.