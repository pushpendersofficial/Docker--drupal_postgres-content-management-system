# Docker--drupal_postgres-content-management-system
# thank you for watching this project 
# this is a Docker project to launch a drupal based content management system which runs on postgreSQL with following details stated:

# running this code includes steps to first install docker-compose
    https://docs.docker.com/compose/install/

# After installing :-
  just run 
  # docker-compose up 
    now check running container by typing:-
          # docker container ls 

# Drupal with PostgreSQL
#
# Access via "http://localhost:8081"
#   (or "http://$(docker-machine ip):8081" if using docker-machine)
#
# During initial Drupal setup,
 Database type: PostgreSQL
 Database name: postgres
 Database username: postgres
 Database password: redhat
# ------------MOST IMPORTANT-----------------
 ADVANCED OPTIONS; Database host: postgres
