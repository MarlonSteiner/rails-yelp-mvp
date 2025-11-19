# Rails Yelp MVP

Restaurant review platform where users can discover and rate local spots 🍽️

Le Wagon Bootcamp - Rails Project

## What it is

A Yelp-inspired restaurant review application where users can browse restaurants, read reviews, and share their dining experiences.

## Features

- **Browse restaurants** - View all restaurants with details
- **Restaurant profiles** - See info, ratings, and all reviews
- **Add restaurants** - Create new restaurant listings
- **Write reviews** - Rate and review restaurants (1-5 stars)
- **Delete reviews** - Remove your own reviews
- **Categories** - Filter by cuisine type

## How it works

A 2-model Rails app with restaurants and reviews:
- **Restaurants** - Name, address, phone, category, description
- **Reviews** - Rating (0-5), content, linked to restaurant

## Technologies

- Ruby on Rails
- PostgreSQL
- Bootstrap 5
- Simple Form

## Setup
```bash
bundle install
rails db:create db:migrate db:seed
rails server
```

Visit `http://localhost:3000`

## Database Schema

- `restaurants` - name, address, phone_number, category
- `reviews` - rating, content, restaurant_id

## Validations

- Restaurant must have name, address, and category
- Review rating must be between 0-5
- Review must be linked to a restaurant

## Challenge

[Le Wagon Yelp MVP Challenge](https://github.com/lewagon/fullstack-challenges)
