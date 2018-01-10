# Week 8 Log

## [53] Day 54: 2017-01-010

### Today's Progress

1. Added data to user model: activation, activated on, and activated digest.
2. Generated a user mailer for account activation and password reset.
3. Customized account activation mailer.

### Time Spent

1 hr 45 min

### Ideas/Techniques Learned

- Bitbucket troubleshooting not necessary. It turns out that they're having server and storage issues themselves.
- `rails generate mailer UserMailer account_activation password_reset` creates 2 mailers.
- CGI module escape method to escape out troublesome characters in URL: `CGI.escape("Don't panic!")` == "Don%27t+panic%21". Rails does this automatically.

### Thoughts, Ideas, Questions

- Question: why is `rails db:migrate:reset` not clearing my data so I can reseed new data?
- Thoughts: I now have a much clearer idea how mailers work. SO EXCITING!

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl

## [52] Day 53: 2017-01-09

### Today's Progress

1. Wrote specs to test that non-admins cannot delete other users.
2. Finished ch10 and began ch11 of Rails tutorial.
3. Pushed to Heroku.

### Time Spent

1 hr

### Ideas/Techniques Learned

- `heroku pg:reset DATABASE` clears data from database in heroku. Useful, if not a little scary.

### Thoughts, Ideas, Questions

- Trouble with Bitbucket. Apparently I'm not the only one:
    - [ssh_exchange_identification: Connection closed by remote host](https://bitbucket.org/site/master/issues/12435/ssh_exchange_identification-connection)
    - [git push remote end hung up](https://bitbucket.org/site/master/issues/7567/git-push-remote-end-hung-up)
- Looking for RSpec resources to learn syntax:
    - [RSpec](http://rspec.info)
- Next up is account activation, which is JUST what I was thinking about yesterday. So glad Hartl covers it!

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl

## [51] Day 52: 2017-01-08

### Today's Progress

1. Fixed "remember me" issue.
2. Added admin boolean column to users.
3. Deleted some users to verify that destory works.

### Time Spent

1 hr 25 min

### Ideas/Techniques Learned

- `destroy`

### Thoughts, Ideas, Questions

- "remember me" helper was missing a parameter and assignment value was `user_id` instead of the correct `user.id`. Typos abound!
- Small win in that I was right on par coding ahead of some examples. I understood this delete implementation better.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl

## [50] Day 51: 2017-01-07

### Today's Progress

1. Pinpointed that email wasn't being accepted into database.
2. Erased db data and seeded with new fake users.
3. Left answer on StackOverflow to help someone else experiencing the same problem I had: https://stackoverflow.com/questions/47367673/gravatar-for-no-method-error-hartl-rails-chapter-7/48140914#48140914
4. Everything is working again!
5. Bootstrap and Will Paginate gems added.
6. Pagination added.
7. Bootstrap styling added to most views.

### Time Spent

3 hr 35 min

### Ideas/Techniques Learned

- `downcase!` seemed to be preventing email of new/updated user from entering the database.
- `User.destroy_all` erases all data in database.

### Thoughts, Ideas, Questions

- So, why was a new user even created without throwing an error??
- Cleared data, but id#s continued on up from 190 instead of resetting to 1.
- I really wanted to experiment with pagination and want to focus more on backend, so I added Bootstrap to push the progress of my app further along faster. It was a tough call because I wanted to style from scratch, but my pride from this app is more in that I'm building the whole thing myself. I have other work that will show off my design (CSS, UX, a11y) skill set.
- Tomorrow I'll test to see that I can't edit someone else's profile from mine.
- Also, rememember_me function doesn't seem to function right.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl
- [Delete all in Rails console](https://stackoverflow.com/questions/17744008/delete-all-in-rails-console)

## [49] Day 50: 2017-01-06

### Today's Progress

1. Troubleshooting for problems with user editing and all users list.
2. Set up github.io page for this repo so I can look back on it, given I never took extra time to blog on Carney Develop It.
3. Experimented with SVG in CSS.

### Time Spent

2 hr

### Ideas/Techniques Learned

- Refresher: check user in Rails console with `User.find_by_id(50)` to find user with the id of 50. I used this to verify that Faker and seeds worked.
- Learned several ways to kill the rails server: `kill -9 {PID#}`, `ctrl+Z`, `killall -9 ruby`. All with mixed results!

### Thoughts, Ideas, Questions

- Faker is working! It's something in my code that's broken.
- Tomorrow I'll go back to the master branch and start ch10 over, begrudgingly.

### Project I worked on

- Rails photo-sharing app
- [SVG in CSS](https://codepen.io/digilou/full/WdXyzZ/)

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl
- Using SVG in CSS3 & HTML5 by Amelia Bellamy-Royds
