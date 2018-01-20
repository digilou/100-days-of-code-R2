# Week 4 Log

## [27] Day 28: 2017-12-14

### Today's Progress

1. Wireframmed main pages (login/signup, image board with modals, user profile)
2. Pseudo-coded login/signup tests
3. Wrote out list of tasks user wants to do on image board.
4. Started adding issues to Bitbucket, and considering priority of functions and features.

### Time Spent

1 hr

### Ideas/Techniques Learned

- Refresh: wireframing.

### Thoughts, Ideas, Questions

- Wow, planning is underrated! Coding makes things happen, but lack of direction and clarity gets your nothing but a mess. Glad I sat down to wireframe, write out tasks/tests, and bullet out user stories!

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- n/a

## [26] Day 27: 2017-12-13

### Today's Progress

1. PR for Women Who Code issue: added smart pluralize to automated email subject line (within config file).
2. 5 lessons on Ruby from Learn.co free tutorials.

### Time Spent

2 hr

### Ideas/Techniques Learned

- Refresh: smart pluralize method `#{pluralize(job_credits.count,"Post")`.
- Using the rails console.

### Thoughts, Ideas, Questions

- Took a break from app planning to get my hands practicing more Ruby and Rails. Will work on app wireframes and user stories separate from coding hour.
- Manual testing with rails console: adding a user, checking the table, sending a notification. SO LOST. Feel like I wasted time I can't get back. Hoping I learn this at another time.

### Project I worked on

- Women Who Code
- Learn.co Ruby tutorials

### Resources I found helpful

- [Ruby Development](https://learn.co)
- [Women Who Code](https://womenwhocode.com)

## [25] Day 26: 2017-12-12

### Today's Progress

1. Installed RSpec for testing.
2. Searched and skimmed through RSpec resources.
3. Intent to write specs for login page.

### Time Spent

1 hr

### Ideas/Techniques Learned

- I was surprised that RSpec is not bundled in the skeleton Rails framework, although there is testing pre-built. RSpec makes it a little easier to understand.

### Thoughts, Ideas, Questions

- I should probably sit down and make wireframes/mockups. Also, write out some user stories, so this doesn't get too convoluted. It would help with my BDD (behavior driven design) testing.

### Project I worked on

- [Photo-sharing app](https://ancient-reef-60958.herokuapp.com/)

### Resources I found helpful

- [Rails Tutorial eBook](https://www.railstutorial.org/book) by Michael Hartl
- [Testing with Rails](http://guides.rubyonrails.org/testing.html)
- [RSpec gem](https://github.com/rspec/rspec)

## [24] Day 25: 2017-12-11

### Today's Progress

1. Refactored HTML into ERB on login page.
2. Read about writing tests and added tests to login spec.
3. Added more structure to login page to allow for signup.

### Time Spent

1 hr

### Ideas/Techniques Learned

- Many tests need to be written in the beginning.

### Thoughts, Ideas, Questions

- I'm definitely not comfortable with TDD (test driven development) yet. This project (a perk of Rails, actually) pushes me to write tests in the beginnning, which would benefit other projects I work on.
- In the beginning of dev, I have so many ideas and much learning to do as I set up this application. How do I best get organized to make the most of my time??
- As ideas pop up, I can see how a project can get complicated and messy real fast.

### Project I worked on

- [Photo-sharing app](https://ancient-reef-60958.herokuapp.com/)

### Resources I found helpful

- [Rails Tutorial eBook](https://www.railstutorial.org/book) by Michael Hartl

## [23] Day 24: 2017-12-10

### Today's Progress

1. Setup postgres in Rails app.
2. Generated static home page (login screen).
3. Coded HTML for login page.
4. Updated controller to point to render home page `respond_to :html`.
5. Updated route to make home page as root `root 'static_pages#home'`.

### Time Spent

1 hr 47 min

### Ideas/Techniques Learned

- Postgres local installation and configuration in Rails app.
- Refresh: generating controllers with views, routes, and spec.

### Thoughts, Ideas, Questions

- I "think" my database is all set up. The truth will come out when I start setting up users for login.
- Don't know why I'm still shocked that initial setup (database) took an hour. I really just want to code/design stuff.
- Feels good to be setting up a web app from back to front all by myself! Such grand hopes for my personal project (right now).
- Don't forget to start writing tests/spec tomorrow for home. Do it early and often.

### Project I worked on

- [Photo-sharing app](https://ancient-reef-60958.herokuapp.com/)

### Resources I found helpful

- [Rails Tutorial eBook](https://www.railstutorial.org/book) by Michael Hartl
- [Postgres Local Setup](https://devcenter.heroku.com/articles/heroku-postgresql#local-setup)
- [Database not found](https://stackoverflow.com/questions/17633422/psql-fatal-database-user-does-not-exist)
- Women Who Code database.yml file
- [How to Setup Postgres on Mac OS](https://launchschool.com/blog/how-to-install-postgresql-on-a-mac)

## [22] Day 23: 2017-12-09

### Today's Progress

1. Edited Gemfile. Installed more gems.
2. Continued local environment setup with Heroku.
3. Created Procfile.
4. Deployed app to Heroku.
5. Finished Ch.1 of Rails Tutorial.

### Time Spent

1 hr 13 min

### Ideas/Techniques Learned

- Heroku setup.
- Introduced to Procfiles.

### Thoughts, Ideas, Questions

- Still need to set up Postgres locally. Did I not do this before?

### Project I worked on

- [Photo-sharing app](https://ancient-reef-60958.herokuapp.com/)

### Resources I found helpful

- [Heroku docs](https://devcenter.heroku.com/)
- [Rails Tutorial eBook](https://www.railstutorial.org/book) by Michael Hartl

## [21] Day 22: 2017-12-08

### Today's Progress

1. Logged back into Heroku, started reading docs to figure out how to set up and deploy my photo-sharing Rails app with them. More time on DevOps than software engineering today.
2. Initiated new Rails app.
3. Installed carrierwave gem for photo uploading to AWS rather than Heroku.
4. Set up Git and pushed repo to Bitbucket.

### Time Spent

1 hr 47 min

### Ideas/Techniques Learned

- Refresh: using/pushing to Bitbucket.
- Refresh: initializing a Rails app.
- Refresh: initializing a local Git repo.

### Thoughts, Ideas, Questions

- Reminder: new projects always take a few days of environment setup. It's the way of things.

### Project I worked on

- Son's photo-sharing app (not public yet)

### Resources I found helpful

- [Heroku docs](https://devcenter.heroku.com/articles/how-heroku-works)
- [Rails Tutorial eBook](https://www.railstutorial.org/book) by Michael Hartl
- [Carrierwave Uploader](https://github.com/carrierwaveuploader/carrierwave)
- [Bitbucket: Push updates to a repo](https://confluence.atlassian.com/bitbucket/push-updates-to-a-repo-221449525.html)
