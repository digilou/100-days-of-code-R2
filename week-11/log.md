# Week 11

## [71] Day 72: 2018-01-28

### Today's Progress

1. Worked through more of week 3 (focus on caching) of the Google Udacity Scholaship Mobile Web course.

### Time Spent

1 hr 20 min

### Ideas/Techniques Learned

- `event.waitUntil` to signal progress of cache box install
- `caches.match(request)` to find a cache that exists
- `caches.open("a-cache")` to open a cache
- `cache.addAll([])` creates an array of items (fonts, pictures, etc) to add to the cache box

### Thoughts, Ideas, Questions

- Promises should NOT end with a semicolon. That's a hard lesson for me to grasp.
- Week 3 is slow going, and I sometimes feel like I'm in the wrong class. But I've come so far in coding that I KNOW I can do this when the time is put in.
- Note taking is halping me out a ton!

### Project I worked on

- Google Udacity Scholarship: Mobile Web

### Resources I found helpful

- Udacity course

## [70] Day 71: 2018-01-27

### Today's Progress

1. Worked through part of week 3 (Service Workers) of the Google Udacity Scholaship Mobile Web course.

### Time Spent

1 hr 20 min

### Ideas/Techniques Learned

- `respondWith()`
- `event.response`
- `new Response('string of some sort', headers: {'Content-Type': 'text/html'})` (no `;` on the end)
- `event.request.url.endsWith('.jpg')` to hijack just jpg files with a response (file).

### Thoughts, Ideas, Questions

- The Dr. Evil gif hijacking trick was great!
- I think I'm going to need to understand better what promises are.
- Week 3 is already giving me ideas to apply to side jobs and projects I'm working on.

### Project I worked on

- Google Udacity Scholarship: Mobile Web

### Resources I found helpful

- Udacity course
- [Response object](https://developer.mozilla.org/en-US/docs/Web/API/Response)