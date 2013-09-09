Baseline
=======

8/20/13

This baseline app provides out of the box support and modest integration of

CanCan,
Devise,
Omniauth-google on top of devise,
Bourbon,
Neat on top of Bourbon

A user model has been created and a single user has been created on that table.

Recommended next steps for good deployment practices:
In Gemfile, uncomment test gems (rspec and cucumber with capybara)
Search in files and rename from "Baseline" to whatever your new project is to be called.
Change to mysql or something not sqlite3.
Register app with Google to implement omniauth-google-oauth2.
Changes roles depending on needs of app
Use the unicorn gem for performance issues

After that, start developing your app, writing tests as you go.


YOU MUST
update your gems and ensure that everything is kosher for whatever version of rails and ruby you are developing on. This gemfile assumes that the master branch from rubygems is adequate (no specific branches from github) and it is passing.


