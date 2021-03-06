# Week 9

## [62] Day 63: 2018-01-19

### Today's Progress

1. Worked through failed specs (unsuccessfully).

### Time Spent

1 hr 15 min

### Ideas/Techniques Learned

- Refresher: `git branch --D <branch-name>` for local delete. `git push origin --delete <branch-name>` for remote delete.

### Thoughts, Ideas, Questions

- Now I'm up to 53 failures. This is not going well.
- After spending a lot of time trying to follow breadcrumbs to the spec failures, I dropped the issue for someone else to resolve. I want to help, but spending half my week doing it takes away from what I'm trying to achieve, overall.
- Know when to push through, ask for help, or let it go.

### Project I worked on

- Women Who Code

### Resources I found helpful

- n/a

## [61] Day 62: 2018-01-18

### Today's Progress

1. Set up micropost view and integration tests.
2. Documented code for application to my image, comment, and like features.
3. Started CSS grid tutorial

### Time Spent

2 hr

### Ideas/Techniques Learned

- `User.find_each(&:destroy)` cleared my Users table data so I could start fresh with newly seeded test data.
- `time_ago_in_words` method

### Thoughts, Ideas, Questions

- Making progress! It seemed like an 1.5 hr work on my app flew by with so much more still to be done.

### Project I worked on

- Rails photo-sharing app
- CSS Grid tutorial

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl
- [Delete all in Rails console](https://stackoverflow.com/questions/17744008/delete-all-in-rails-console)
- [CSS Grid](https://cssgrid.io) by Wes Bos

## [60] Day 61: 2018-01-17

### Today's Progress

1. Worked through Codeship failures to update specs after removing column yesterday.

### Time Spent

1 hr

### Ideas/Techniques Learned

- n/a

### Thoughts, Ideas, Questions

- Broke a bunch of spec tests (51 failures!). Trying to get a handle on the association of profile and network_id.

### Project I worked on

- Women Who Code website

### Resources I found helpful

- n/a

## [59] Day 60: 2018-01-16

### Today's Progress

1. Removed a column from a table.
2. Removed specs that applied to that column.
3. Evaluated models that may have been associated with that column.

### Time Spent

1 hr 30 min

### Ideas/Techniques Learned

- `rails g migration RemoveColumnFromTables col1:integer` requests removal of a column from a table, specifically "col1" from Tables table.
- `rspec spec/profiles_spec.rb` targets this specific file for running tests.

### Thoughts, Ideas, Questions

- Taking a leap into backend that I don't normally do, but the Rails tutorial has given me a little confidence on basics such as database migration, spec modification, and models.
- The specs are tripping me up, but I think that's because I'm trying to follow the thread of someone else's code.

### Project I worked on

- Women Who Code website

### Resources I found helpful

- [How to remove a column from a database?](https://stackoverflow.com/questions/38820188/rails-5-how-to-remove-a-column-from-a-database)
- [Run RSpec tests from specific folder](https://stackoverflow.com/questions/21531774/run-rspec-tests-from-specific-folder-using-rake)

## [58] Day 59: 2018-01-15

### Today's Progress

1. Added more specs to micropost model and associated microposts with users.
2. Wrote down image gallery ideas alongside micropost work, so I could capture the same ideas.

### Time Spent

2 hr

### Ideas/Techniques Learned

- `.errors.full_messages` to see full error message in console.
- `has_many :microposts` model associations

### Thoughts, Ideas, Questions

- Running through the micropost tutorial (ch13) to glean the code I need for likes, comments, and image gallery features for my app.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl
- [RSpec: Built in matchers](https://relishapp.com/rspec/rspec-expectations/docs/built-in-matchers)

## [57] Day 58: 2018-01-14

### Today's Progress

1. Wrote and submitted first C program "hello, world" to CS50 (week 1).
2. Started ch13 of Rails Tutorial by generating microposts model and writing specs.

### Time Spent

1 hr 35 min

### Ideas/Techniques Learned

- `text` data type allows more than 255 characters.
- `reference` type associates (references) models.
- RSpec: `assert @microposts.valid?` == `expect(@microposts.valid).to be true`. (I think??)

### Thoughts, Ideas, Questions

- I probably shouldn't have wasted half of my hour with CS50, instead of working on my Rails app, but late afternoon programming session had me worn out and I was more inclined to ease into my hour with tutorials and a tiny C program than thinking harder about my app (and screwing it up).
- CS50 is a distraction, but I'll try to take it slow. It is nice to see that I understand some C already, thanks to JavaScript and Python! I may not always count it as part of my 100 days, if I'm doing more videos than coding.
- Still feeling my way blindly through converting Rails Test syntax to RSpec syntax.

### Project I worked on

- CS50 Week 1
- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl
- [RSpec: Built in matchers](https://relishapp.com/rspec/rspec-expectations/docs/built-in-matchers)
- [edX CS50 course by Harvard](https://www.edx.org/course/introduction-computer-science-harvardx-cs50x)


## [56] Day 57: 2018-01-13

### Today's Progress

1. Password reset functionality complete and pushed to production.

### Time Spent

2 hr

### Ideas/Techniques Learned

- No "ah-ha!" moments today.

### Thoughts, Ideas, Questions

- I've come a long way on this app. So glad I'm getting somewhere. The hard part is still ahead, as I walk off the ledge of tutorials and take that leap of faith that I can construct the image sharing pieces with the help of my own logic/reasoning and StackOverflow.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl
