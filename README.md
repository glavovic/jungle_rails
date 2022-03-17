# Jungle

A mini e-commerce application built with Rails 4.2

## Setup

1. Run `bundle install` to install dependencies
2. Run `bin/rake db:reset` to create, load and seed db
3. Run `bin/rails s -b 0.0.0.0` to start the server

## Stripe Testing

Use Credit Card # 4242 4242 4242 4242 for testing success scenarios.
Any date after current date and any 3 digit security number

More information in their docs: <https://stripe.com/docs/testing#cards>

## Dependencies

* Rails 4.2 [Rails Guide](http://guides.rubyonrails.org/v4.2/)
* PostgreSQL 9.x
* Stripe
* capybara
* poltergeist
* database_cleaner
* rspec-rails
* sass-rails
* bcrypt
