# Week 6 Log

## [36] Day 37: 2017-12-23

### Today's Progress

1. Added password and password confirmation to user table.
2. Wrote specs and validations for password and confirmation.
3. Started routing user information to user#show web page.

### Time Spent

1 hr 32 min

### Ideas/Techniques Learned

- `has_secure_password` for Rails has a lot of features packed into it! Most of the password validation work is done by using this.
- `resources :users` adds routing between model and displaying info on page.
- `<%= debug(params) if Rails.env.development? %>` to add debug console into web page.

### Thoughts, Ideas, Questions

- Still wish I was further along in this project! At least I'm finally starting to touch the view pages, which is really where I want to be.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl
- [Simple authentication in Rails using Bcrypt](https://gist.github.com/thebucknerlife/10090014)

## [35] Day 36: 2017-12-22

### Today's Progress

1. Wrote more validations and specs for user model.

### Time Spent

1 hr 25 min

### Ideas/Techniques Learned

- `expect(@user).to_not be(true)` == `assert_not @user.valid?`

### Thoughts, Ideas, Questions

- RSpec seems to be the trend among Rails devs, but the built in test feature seems just as readable to me.
- Testing and validation feels tedious (as a n00b and tired mama) when you just want to get your page views up and working. But I'm grateful the importance is stressed throughout Hartl's book.
- Tomorrow I can learn how to add a secure password!

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl
- [How to test Rails models with RSpec](https://semaphoreci.com/community/tutorials/how-to-test-rails-models-with-rspec)
