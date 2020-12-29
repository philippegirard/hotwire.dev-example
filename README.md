# Hotwire code example

I copied the code from DHH's screencast on the [hotwire.dev](https://hotwire.dev/#screencast) homepage.

# How to run the example
You will need rails 6.1, docker and docker-compose

### Start redis
```
docker-compose up -d
```
this should start redis on port 6379

### Start rails
```
bundle install
rails db:create
rails s
```

# Try the app
Go to `http://localhost:3000/rooms`