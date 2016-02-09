== README

Building demo blog by railstutorial.ru   Chapter 9.4 (add admin user, delete users)

hhttp://railstutorial.ru/chapters/4_0/updating-showing-and-deleting-users#top

* Ruby version 2.1.2

* Rails version 4.2.4

* Ubuntu 14.04

* Database postgres

* Deployment from http://railstutorial.ru/chapters/4_0/a-demo-app#top

- default admin user is "admin@railstutorial.org" with password: "foobar"
      to change - look at lib/tasks/sample_data.rake
      need to reset db -> rake db:reset
      and do ->           rake db:populate  for gem 'faker' to fill a db with data

- find a admin user at rails console -> User.where(:admin => true)

- do rake assets:precompile for working styles
- heroku run rake db:migrate --app


App at production -

