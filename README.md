# Dockernize your rails with postgres and nginx

## what's in it
- ruby 2.4
- nginx
- rails 5.1.4

## Steps
- Clone the repository
- Copy your rails app to the correct folder, located in the project
- run docker-compose build
- docker-compose run app bundle exec rails db:create db:migrate RAILS_ENV=production
- docker-compose up -d

If you want to stop the containers, run:
- docker-compose down
