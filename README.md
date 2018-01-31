# slackR
SlackR

SlackR is a desktop, python based app that utilizes the power of docker, elastic search and kibana to collect, store 
and visualize your daily desktop apps usage. 

With the help of the above tools and some code you can be aware of the amount of time you spend on different apps, the 
longest uninterrupted time you spend on a specific apps day on a daily basis.

With a little poking around you can also build your own dashboards based on what you desire.


Setup

** Application can only run on OSX **

1. Git clone repo
2. docker-compose up -d
3. pip install slackr (Recommend using a virtualenv)
4. Open Kibana and verify interface is available at http://localhost:5601
5. Run the python init file under slackr. (Use nohup to demonize -- EG: nohup python __init__.py)
6. Click on kibana dashboard "Slackr" to view your app usages.


Dashboard Views

![alt text](https://github.com/anushjay/slackr/blob/master/screenshots/slackr_readme.png)

Search

![alt text](https://github.com/anushjay/slackr/blob/master/screenshots/slackr_readme_search.png)

Viz

![alt text](https://github.com/anushjay/slackr/blob/master/screenshots/slackr_readme_viz.png)
