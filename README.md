# dockers
image or files for docker

docker-compose.yml files can use after make directory for sw. (redmine, mattermost directory)
ex.
---/opt/redmine/docker-compose.yml
---/opt/mattermost/docker-compose.yml

-> first, go in each /opt/sw/
-> second, docker-compose up -d : active the containers(redmine-app, redmine-db)
-> third, docker-compose down : inactive the containers(mattermost-app, mattermost-db)
