# Week 10

## [69] Day 70: 2018-01-26

### Today's Progress

1. Completed ch14 of Rails tutorial.
2. Add a couple updates to my documentation toward my photo-sharing app.
3. Started planning out serious commitment to complete mobile web class (Google Udacity Scholarship class).

### Time Spent

1 hr 20 min

### Ideas/Techniques Learned

- SQL code can go inside a variable
  `following_ids = "SELECT followed_id FROM relationships
                     WHERE  follower_id = :user_id"`

### Thoughts, Ideas, Questions

- It felt good to finish the entire tutorial!! (I rushed a bit at the end, but mostly because I know I won't be adding some of this into my photo-sharing app).

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl

## [68] Day 69: 2018-01-25

### Today's Progress

1. Coded alongside ch14 of Rails tutorial (follow/unfollow buttons).
2. Documented steps with customization for my app intentions.

### Time Spent

1 hr 10 min

### Ideas/Techniques Learned

- There's a `js.erb` file type!

### Thoughts, Ideas, Questions

- Almost done with his book!
- A bit nervous about stepping off the tutorial cliff with my own ideas and customizations.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl

## [67] Day 68: 2018-01-24

### Today's Progress

1. Coded alongside ch14 of Rails tutorial (relationships/following users).
2. Documented steps with customization for my app intentions.

### Time Spent

1 hr

### Ideas/Techniques Learned

- `through`
- `<%= @user.following.count %>` to bring in the count of other users following you.

### Thoughts, Ideas, Questions

- Slow going this morning. Being woken up at 4 does little for my productivity. Picked up the pace by the time I had to go to work. Boooooo.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl

## [66] Day 67: 2018-01-23

### Today's Progress

1. Coded alongside ch14 of Rails tutorial (relationships/following users).
2. Documented steps with customization for my app intentions.

### Time Spent

1 hr 15 min

### Ideas/Techniques Learned

- `:active_relationships`

### Thoughts, Ideas, Questions

- There's still a lot to take in, but I am trying to take it slow and document alongside it, as I continue to plan an image gallery for my app.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl

## [65] Day 66: 2018-01-22

### Today's Progress

1. Set up AWS account.
2. Explored Amazon S3 photo bucket options.

### Time Spent

1 hr

### Ideas/Techniques Learned

- n/a

### Thoughts, Ideas, Questions

- Blah! I really don't like the DevOps part of this work. Setting up a site (in this case, a cloud photo bucket) is not exciting to me at all.
- Would love to set up my own "photo bucket" on my own RPi server.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl

## [64] Day 65: 2018-01-21

### Today's Progress

1. Set up carrierwave gem.
2. Added image uploading capability to microposts.
3. Added to documentation for future image upload prospects.

### Time Spent

1 hr 15 min

### Ideas/Techniques Learned

- Learned how to use carrierwave for image uploading.

### Thoughts, Ideas, Questions

- This was an exciting part of my learning! Uploading images to the web is a huge detail to learn in Rails and web dev!
- Tomorrow I'll configure an AWS S3 bucket.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl

## [63] Day 64: 2018-01-20

### Today's Progress

1. Created form for submitting microposts.
2. Refactored some page code into partials.
3. Added 'delete micropost' functionality.

### Time Spent

1 hr 50 min

### Ideas/Techniques Learned

- `"aria-label": "Compose microposts."` is how to insert aria attributes into ERB.
- `redirect_back(fallback_location: root_url)` for redirecting user back to page they were on, after an event (like delete post) happens.

### Thoughts, Ideas, Questions

- So tired today that I didn't want to code. BUT, little progress is better than no progress at all. Now I'm a little further along on microposts.
- Did some extra time in the afternoon. Mind was a lot clearer then after coffee, time with family, and a brief Doctor Who break.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl
