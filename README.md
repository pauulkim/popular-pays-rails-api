# Popular Pays Rails REST API
## Running the Application
install dependencies
```
bundle install
```

start the postgres database
```
sudo service postgresql start
```

create the database
```
bundle exec rails db:create
```

migrate tables
```
bundle exec rails db:migrate
```

start the app 
```
rails s
```



This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...