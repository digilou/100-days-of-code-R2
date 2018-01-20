# Week 1 Log

## [6] Day 7: 2017-11-23 (Thanksgiving)

### Today's Progress

1. Read through functions to try to determine what more I needed to add.
2. Started adding data attributes to my HTML to give more focus to rows and columns for checking the board for a winning move.
3. Skimmed through Haml docs.

### Time Spent

1 hr

### Ideas/Techniques Learned

- Global data attibutes, new to HTML5, are handy in this situation. I've seen them used, but not played with them much.

### Thoughts, Ideas, Questions

- Still feeling a bit adverse about adding AI and completing the game, in general. But I made it my first goal of this challenge for that very reason.
- Adding more rendundant attributes to my HTML makes me wonder if I should have pursued Pug or Haml. Maybe I'll convert to it before submission. I would like to add Haml to my knowledge base to better help me assist with the Women Who Code project.

### Project I worked on

- [FCC: Tic Tac Toe](https://codepen.io/digilou/pen/POOypV)

### Resources I found helpful

- [Gunnar Bittersmann's PE Tic Tac Toe](https://codepen.io/gunnarbittersmann/pen/aVWmMR)
- [HTML5 data-* attribute](https://www.w3schools.com/tags/att_global_data.asp)
- [Haml docs](http://haml.info/docs/yardoc/file.REFERENCE.html)

## [5] Day 6: 2017-11-22

### Today's Progress

1. Organized and broke down pseudo-code for JS interactions even more.
2. Started coding a couple of functions (startGame, computerPlay, checkBoard, endGame) to give Tic Tac Toe  enhanced interaction.
3. Bought the Wes Bos "React for Beginners" course to do later in this 100-day journey.

### Time Spent

1 hr 2 min

### Ideas/Techniques Learned

- Avoided `innerHTML` because I read this wasn't best practice. Went for `textContent`, but then decided `innerText` may be the best way to go for updating `output`.

### Thoughts, Ideas, Questions

- Night time is a bad time for me to really concentrate and dig deep. Avoid, if at all possible.
- Amazingly, breaking down more pseudo-code helped me zone in more on what I needed to do, which led to the beginnings of my functional programming.
- Not yet confident how I'm going to write in AI. That requirment will be the most challenging and time-consuming for me.

### Project I worked on

- [FCC: Tic Tac Toe](https://codepen.io/digilou/pen/POOypV)

### Resources I found helpful

- [Gunnar Bittersmann's PE Tic Tac Toe](https://codepen.io/gunnarbittersmann/pen/aVWmMR)
- [Node.innerText](https://developer.mozilla.org/en-US/docs/Web/API/Node/innerText)

## [4] Day 5: 2017-11-21

### Today's Progress

1. Moved `checked` state to CSS (using :after) rather than targeting with JS.
2. Started defining variables for pieces on the board.

### Time Spent

1 hr 6 min

### Ideas/Techniques Learned

- I forgot about `output` new to HTML5! Good use for announcing who the winner is.
- Thanks to Code School, I recently learned that adding variables separated by commas can improve performance. Testing to see if const and let work that way, too.

### Thoughts, Ideas, Questions

- I felt short on time today, since my son work up later and I had only an hour between then a getting ready for work.
- With Gunnar's code as a starting point, I feel like the fog isn't quite as thick, even though my functionality will vary slightly.
- There is not shame learning from someone else's code. Especially when time is spent trying to understand how it works and if it can be customized for your needs.

### Project I worked on

- [FCC: Tic Tac Toe](https://codepen.io/digilou/pen/POOypV)

### Resources I found helpful

- [Gunnar Bittersmann's PE Tic Tac Toe](https://codepen.io/gunnarbittersmann/pen/aVWmMR)
- [Output tag](https://www.w3schools.com/tags/tag_output.asp)

## [3] Day 4: 2017-11-20

### Today's Progress

1. Back to CSS for 'x' and 'o' styling, instead of using JS to make them show up as selected.
2. Mostly search-read-find since I haven't gotten my JS to work yet.

### Time Spent

1 hr

### Ideas/Techniques Learned

- `getElementsByTag` vs. `querySelectorAll` vs. `querySelector`

### Thoughts, Ideas, Questions

- Frustrated with limitations on tweaking look of pre-built form elements, like input and label. Maybe I'll have to hide the 'x' and 'o' and use `:after` instead?
- Frustrated that, apparently, I don't quite fully understand how to traverse the DOM.

### Project I worked on

- [FCC: Tic Tac Toe](https://codepen.io/digilou/pen/POOypV)

### Resources I found helpful

- none today

## [2] Day 3: 2017-11-19

### Today's Progress

1. Worked through JavaScript portion of Tic Tac Toe by writing out pseudo-code steps.
2. Started writing out JS, starting with user choices.
3. Some labels disappear when clicked.

### Time Spent

1 hr 14 min

### Ideas/Techniques Learned

- Practiced targeting DOM elements, trying to discover the difference between `getElementsByTagName`, `querySelector`, and `querySelectorAll`.
- Practiced using `addEventListener`.

### Thoughts, Ideas, Questions

- Right away, I acknowledged that I can't code this in an hour. I have to take small steps.
- Writing out pseudo-code (this time around) helped me focus on what I wanted to accomplish, and small steps I needed to take to get there.
- I'm still a little unclear when to use which DOM targetting method. I see `querySelector` but is that the best choice? What about `getElementsByTagName`?
- And why can't I seem to grab all the `label` tags? What am I doing wrong?
- Eat the elephant, one bite at a time. This really isn't my favorite project.

### Project I worked on

- [FCC: Tic Tac Toe](https://codepen.io/digilou/pen/POOypV)

### Resources I found helpful

- [JavaScript Event Listeners](https://www.w3schools.com/js/js_htmldom_eventlistener.asp);
- [JavaScript DOM Elements](https://www.w3schools.com/js/js_htmldom_elements.asp)

## [1] Day 2: 2017-11-18

### Today's Progress

1. Completed markup for FCC Tic Tac Toe board.
2. Started styling it. About halfway through my CSS from scratch.

### Time Spent

1 hr 33 min

### Ideas/Techniques Learned

- `button type="reset"` must be **inside** the form to work.
- Sass may have made some of the styling go quicker, but some less practiced aspects, like `@extend`, I just didn't want to get to far away from my goal.
- Not new, rather a reminder: design takes time, so take the time.

### Thoughts, Ideas, Questions

- I'm still determined to complete this in a timely manner, as to not waste too many days on this round for FCC projects. However, it's still tempting to avoid and and drag my feet. I'll feel pretty good about it once it's done, though!
- Re-read FCC's user stories for Tic Tac Toe and realized that keeping score is not required. I'm more than happy to do the bare minimum this go-around just to reach my goal. It's something I can practice another time. Game development is just not my interest.j
- Tried unicode for repeat symbol on "Play Again?" button, but it looks ugly. Making my own SVG sounds like the best way to go.

### Project I worked on

- [FCC: Tic Tac Toe](https://codepen.io/digilou/pen/POOypV)

### Resources I found helpful

- [Using RegEx in CSS](http://thegeekyway.com/css-regex-selector-using-regular-expression-css/)
- [Unicode Repeat Character](http://www.fileformat.info/info/unicode/char/1f501/index.htm)

## [0] Day 1: 2017-11-17

### Today's Progress

1. Init Round 2. Set up my Github repo to mimic my other 100 Days of Code repo, but with improvements and personailzed tweaks to suit my needs.
2. Watched Gunnar Bittersmann's [An inclusive tic-tac-toe, progressively enhanced video](https://youtu.be/36i2o26JE2M) from #ID24. That was timely!
3. Started a new pen for my Tic Tac Toe project (Free Code Camp). It's been too long since I've touched it and just need to start over. I'm starting with Gunnar's approach because accessibility was nagging at me anyhow, so this gives me a course to accomplish that goal!
4. Coded most of HTML base for the game. I'm liking the new approach. It's making me think about the basic experience.
5. In the end, I spent most of my time just getting myself organized and set up. But I suppose I expected that, even though I wanted to dive into code a little sooner. The video was important to watch. And documentation is something I'm striving to maintain better this time around. Besides, new projects always promise dev environment setup, orientation, and extra learning.

### Time Spent

1 hr 33 min

### Ideas/Techniques Learned

- a radio button is an ingenious way to show the choice the user has and the states of tic tac toe
- Emmet can be a quick way to help type HTML quicker without going down the rabbit hole of HTML pre-processors (Pug, Haml)
- Pug does have benefits and value, but I'll tackle that another day

### Thoughts, Ideas, Questions

- Let's do this! I know what I'm in for, which makes me wonder how I'll do this time. Can I stay committed? Accountability helps. Can I stay focused? I have strong intentions.

- Gunnar's approach to making TicTacToe accessible/usable through progressive enhancement was MIND-BLOWING. This is how I want to approach things more naturally. With my strengths lying in HTML and CSS, this shouldn't be too difficult.

- How should I handle the markup of "score" in my game? What semantics make the most sense?

### Project I worked on

- [FCC: Tic Tac Toe](https://codepen.io/digilou/pen/POOypV)

### Resources I found helpful

- Gunnar Bittersmann's [An inclusive tic-tac-toe, progressively enhanced video](https://youtu.be/36i2o26JE2M) from #ID24
