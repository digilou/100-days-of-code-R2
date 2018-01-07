# Week 8 Log

## [50] Day 51: 2017-01-07

### Today's Progress

1. Pinpointed that email wasn't being accepted into database.
2. Erased db data and seeded with new fake users.
3. Left answer on StackOverflow to help someone else experiencing the same problem I had: https://stackoverflow.com/questions/47367673/gravatar-for-no-method-error-hartl-rails-chapter-7/48140914#48140914
4. Everything is working again!

### Time Spent

2 hr 35 min

### Ideas/Techniques Learned

- `downcase!` seemed to be preventing email of new/updated user from entering the database.
- `User.destroy_all` erases all data in database.

### Thoughts, Ideas, Questions

- So, why was a new user even created without throwing an error??
- Cleared data, but id#s continued on up from 190 instead of resetting to 1.
- Tomorrow I'll test to see that I can't edit someone else's profile from mine.

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
