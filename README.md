# Future Me
This is the final project for the Nov -16 cohort from Craft Academy Bootcamp.

### Pivotal Tracker
[Pivotal](https://www.pivotaltracker.com/n/projects/1968195)

### Build
[![Build Status](Travis URL)

### Coverage
[![Coverage Status](Coveralls URL)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

<!-- To be able to install and run the application you need to have Rails 5 and PostgreSQL installed. -->

### Installing

Fork and clone repo, then run:
```
$ bundle install
```

And then:

```
$rake db:migrate db:seed
```

## Running the tests

End with an example of getting some data out of the system or using it for a little demo

```
$ rake
```

## Deployment

We are using [Travis](https://travis-ci.org) for continous integration and Heroku](http://heroku.com/) for deployment.

For deployment, change the information in the `.travis.yml` file. For API-key;

```
$ travis encrypt $(heroku auth:token) —add deploy.api_key
```

### Deployed at [https://homechefs.herokuapp.com/](https://homechefs.herokuapp.com/)

## Built With

  * [Travis](https://travis-ci.org) - Used for continous integration
  * [Coveralls](https://coveralls.io) - To track code coverage
  * [Heroku](http://heroku.com/) - For deployment
  * [Ruby on Rails](http://rubyonrails.org) — Web Framework

For testing purposes we used:

  <!-- * Pry
  * Pry-byebug
  * Rspec-rails
  * Shoulda-matchers
  * Factory_girl_rails
  * Cucumber-rails
  * Database_cleaner
  * Capybara
  * Capybara-screenshot
  * Poltergeist -->

## Authors
  * **Craft Academy** - [CraftAcademy](https://github.com/CraftAcademy)
  * **Ebba Aniansson** - [aniansson](https://github.com/aniansson)
  * **Kristoffer Karlsson** - [kriizjones](https://github.com/kriizjones)
  * **Philip Zudemberg** - [Philippoes](https://github.com/Philippoes)
  * **Rodrigo Muños** - [rmzse](https://github.com/rmzse)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
