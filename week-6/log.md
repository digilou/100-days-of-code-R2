# Week 6 Log

## [40] Day 41: 2017-12-27

### Today's Progress

1. Wrote more integration tests for basic login.
2. Completed ch 7 of Hartl's tutorial.

### Time Spent

30 min

### Ideas/Techniques Learned

- Fixtures reside under specs. They're tangible examples to test. Watch out for tabs vs spaces in these files.

### Thoughts, Ideas, Questions

- Prioritized sleep and family today, so did just enough coding time to get through login integration tests so I'd be rewarded with advanced login tomorrow.
- I was definitely rushing through tests/specs. Coding at night is not good for me.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl

## [39] Day 40: 2017-12-26

### Today's Progress

1. Updated documentation/cheatsheet, which worked as review of sign-up/sign-in portions.
2. Wrote specs and integration tests for login.
3. Added error flash message.
4. Completed basic login function.

### Time Spent

2 hr 15 min

### Ideas/Techniques Learned

- I think I'm finally understanding how classes work in this environment/language.
- I'm still never too good to drop typos in my code often.

### Thoughts, Ideas, Questions

- Even on projects I want to work on (especially when not happening as fast as I want), I still find it hard to get myself rolling at the beginning.
- I'm still very confused about rspec conversion. Maybe I should have stuck with the built in testing so I was less confused. Than jumped to rspec-rails when I'm ready.
- Google and StackOverflow are amazing.
- So much learned about basic user and session management! Adding `if/else` to ERB template is a wonderful thing I love about programming for the web!

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl
- [Project: RSpec Rails 3.7 documentation](https://relishapp.com/rspec/rspec-rails/v/3-7/docs)
- [Rails Uninitialized constant ApplicationController::SessionHelper](https://stackoverflow.com/questions/34420570/rails-uninitialized-constant-applicationcontrollersessionhelper)

## [38] Day 39: 2017-12-25

### Today's Progress

1. Completed sign-up functionality and spec, and deployed to Heroku.
2. Enabled SSL (TLS) for my site.
3. Started login page.

### Time Spent

1 hr 20 min

### Ideas/Techniques Learned

- First deploying to Heroku, my user model wasn't working. Found `heroku run rails db:migrate` helped. I skipped that step somewhere.
- SSL is actually TLS (Transport Layer Security) now.

### Thoughts, Ideas, Questions

- Didn't think I'd code today. Tired. Hungry. And it's Christmas. Needed a break though, so coding made sense.
- WOW. It's a good feeling to have deployed REAL signup functionality. AND SSL (TLS) is actually easy to enable in this situation. Next is login.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl

## [37] Day 38: 2017-12-24

### Today's Progress

1. Wrote specs for users_signups.
2. Finished ch 7 of Hartl's book.
3. Updated signup routing to resolve `user` versus `signup` in url.
4. Completed sign-up process!!
5. Added flash welcome message.

### Time Spent

1 hr 20 min

### Ideas/Techniques Learned

- Happy that I have more "technical sophistication" than I give myself credit for.
- More RSpec equivelants to test, using `expect().to`, etc. See cheatsheet resource below.
- Adding a flash welcome message.

### Thoughts, Ideas, Questions

- Specs are still taking me awhile as I'm learning equivelants to tests in Hartl's book. Feels like wasted time toward my goal, yet valuable for the long run.
- WOOHOO! Basic sign-up functionality is complete!

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl
- [RSpec-rails cheatsheet](https://devhints.io/rspec-rails)

## [36] Day 37: 2017-12-23

### Today's Progress

1. Added password and password confirmation to user table.
2. Wrote specs and validations for password and confirmation.
3. Started routing user information to user#show web page.
4. Constructed ERB show page.

### Time Spent

3 hrs

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
