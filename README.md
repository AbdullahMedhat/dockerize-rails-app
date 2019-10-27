# This is just a way to docrkize a rails app

- build all containers
- docker-compose build

- initialize your DB
- docker-compose run app rake db:create RAILS_ENV=production

- Create DB and run the migrations
- docker-compose run app rake db:migrate db:seed RAILS_ENV=production


- To run the app
- docker-compose up -d

- To watch and verify containers running
- docker ps


- To run rails console throught docker-compose
- docker-compose run app rails console
