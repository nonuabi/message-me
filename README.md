# Message Me

Message Me is a Ruby on Rails application for real-time messaging.

## Prerequisites

1. Install RVM (Ruby Version Manager): [https://rvm.io/rvm/install](https://rvm.io/rvm/install)

## Setup Project

Follow these steps to set up the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/nonuabi/message-me.git
   ```
2. Navigate to the project directory:
   ```bash
   cd message-me
   ```
3. Install Ruby 2.6.8 using RVM:
   ```bash
   rvm install ruby-2.6.8
   ```
4. Install Bundler version 2.2.30:
   ```bash
   gem install bundler:2.2.30
   ```
5. Install project dependencies
   ```bash
    bundle install
   ```
6. Create the database
   ```bash
    rails db:create
   ```
7. Migrate the database tables
   ```bash
   rails db:migrate
   ```

## Seed Data in Database

To seed the database with initial data, run:

```bash
 rails db:seed
```

## Start Application

1. Start the Rails server
   ```bash
    rails s
   ```
2. Visit the application in your browser at: http://localhost:3000/
