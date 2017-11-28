# Week 2 Log

## [11] Day 12: 2017-11-28

### Today's Progress

1. Started over, this time with Gunnar's code, so I can understand why my bugs (originating in `startGame`, I think) persist.
2. Began intermittent structure and design tweaks to discover what problem I created in v1.

### Time Spent

1 hr 5 min

### Ideas/Techniques Learned

- Practice with `console.log()` to find global variables.

### Thoughts, Ideas, Questions

- I still haven't discovered why `output` in `startGame()` was throwing a `TypeError`, so starting over seemed liked the next best step, though it feels VERY tedious doing so. The only perk, I'm getting to know my code in and out, which gives me improvement ideas as I go.

### Project I worked on

- [FCC: Tic Tac Toe](https://codepen.io/digilou/pen/POOypV)

### Resources I found helpful

- [Gunnar Bittersmann's PE Tic Tac Toe](https://codepen.io/gunnarbittersmann/pen/aVWmMR)
- JavaScript: Novice to Ninja, 1st ed.

## [10] Day 11: 2017-11-27

### Today's Progress

1. Became more familiar with the why's of Gunnar's code, like why he used specific `Math` methods.
2. Refactored a couple of arrow functions.
3. Found that `const output = table.getElementsByTagName("output")` was not doing the trick, so I reverted back to `table.querySelector("output")` (but now that gives me a `TypeError` at `startGame()`).

### Time Spent

1 hr 7 min

### Ideas/Techniques Learned

- `Math.abs()` method returns the absolute number (-1 === 1).
- `Math.sigh()` method returns the sign of a number (negative, positive, zero).
- `parseInt()` function taps into a string and returns an integer with a specified radix; good practice is to always include the base (radix) since not all browsers support the default of `10`.
- Thanks to Wes Bos's ES6 course, I'm more comfortable with understanding how and when to use arrow functions.

### Thoughts, Ideas, Questions

- Output isn't doing anything? 
- Bottom right square `board[2][2]` disappears when bottom left square `board[2][0]` is clicked or even when a bottom row win occurs? Sometimes vice versa.

### Project I worked on

- [FCC: Tic Tac Toe](https://codepen.io/digilou/pen/POOypV)

### Resources I found helpful

- [Gunnar Bittersmann's PE Tic Tac Toe](https://codepen.io/gunnarbittersmann/pen/aVWmMR)
- [Math.abs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/abs)
- [Math.sign](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/sign)
- [parseInt](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseInt)
- [ES6 for Everyone](https://es6.io)

## [9] Day 10: 2017-11-26

### Today's Progress

1. Used Firefox web inspector to work through JS errors in the console. Resolved JS typos allowed me to move forward a little more, so that 'x' and 'o' are appearing and disappearing, as expected.

### Time Spent

1 hr 3 min

### Ideas/Techniques Learned

- Use `DOMContentLoaded`(versus `load`) to fire event / run function immediately after HTML is parsed, not waiting on CSS, images, and subframes. It's an HTML5 spec.
- Once again, fixed typos resolve issues. Found with the help of the JS console/inspector.

### Thoughts, Ideas, Questions

- Thought I understood `const` better, but still unsure why `querySelectorAll` works inside this.
- Hmm... upon game reset, the opposite letter appears. Something that may resolve when I update my code to include AI? And nothing appears to be happening in `output` though no errors show up.

### Project I worked on

- [FCC: Tic Tac Toe](https://codepen.io/digilou/pen/POOypV)

### Resources I found helpful

- [Gunnar Bittersmann's PE Tic Tac Toe](https://codepen.io/gunnarbittersmann/pen/aVWmMR)
- [DOMContentLoaded](https://developer.mozilla.org/en-US/docs/Web/Events/DOMContentLoaded)

## [8] Day 9: 2017-11-25

### Today's Progress

1. Experimented with syntax I was less familiar with: `let`, `const`, `calc()`, `vmin`.
2. Updated some design aspects of my Tic Tac Toe board.
3. Solved X and O overlap issue caused by conflict of .js styling while JS functions are not working yet.

### Time Spent

1 hr 12 min

### Ideas/Techniques Learned

- `vmin` is a newer relative unit. I experimented with it to make my table cells stretch across the viewport.
- `const` isn't immutable, but it's set to not be overwritten.
- `let` is more like `var`, but is scoped for a block rather than just a function.
- First time playing with calc CSS function. Whitespace must be between `+` and `-`, but not `/` or `*`.

### Thoughts, Ideas, Questions

- So glad I bought the Wes Bos "ES6 for Everyone"! It's already helped me better understand things I was learning, but wasn't quite sure how to use at the appropriate time.

### Project I worked on

- [FCC: Tic Tac Toe](https://codepen.io/digilou/pen/POOypV)

### Resources I found helpful

- [Fun with Viewport Units](https://css-tricks.com/fun-viewport-units/)
- [ES6 for Everyone](https://es6.io)
- [calc() CSS function](https://developer.mozilla.org/en-US/docs/Web/CSS/calc)

## [7] Day 8: 2017-11-24

### Today's Progress

1. Combed through my Tic Tac Toe code to try and figure out why player's choice is not working.
2. After 45 minutes, resolved typos, which fixed my player selection problem.

### Time Spent

1 hr 6 min

### Ideas/Techniques Learned

- `::after` is CSS3 and `:after` is CSS2
- CodePen has an Analyze CSS feature, which I should have used much sooner. Typos happen.

### Thoughts, Ideas, Questions

- Always, always, always read letter by letter. I resolved my `fieldset` and `label::after` problems all because of types "fieldet" and "positon" were misspelled.

### Project I worked on

- [FCC: Tic Tac Toe](https://codepen.io/digilou/pen/POOypV)

### Resources I found helpful

- [Gunnar Bittersmann's PE Tic Tac Toe](https://codepen.io/gunnarbittersmann/pen/aVWmMR)
- [::after pseudo class](https://developer.mozilla.org/en-US/docs/Web/CSS/::after)
