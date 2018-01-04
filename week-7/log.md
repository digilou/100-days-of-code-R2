# Week 7 Log

## [47] Day 48: 2017-01-04

### Today's Progress

1. Coded alongside examples in ch10 of Hartl's rails tutorial which limited users to editing only their own profile.
2. Scanned ahead to see determine what additional features I'll use in my app that coincide with his.

### Time Spent

1 hr

### Ideas/Techniques Learned

- Don't stop to criticize. Focus on the object at hand. Progress is made by making small steps forward. (see thoughts below)

### Thoughts, Ideas, Questions

- Focus on getting through the tutorial with as much gleaning as I can, but don't criticize yourself for not mastering it immediately. Baby steps. The intention is exposure, a degree of accomplishment (Rails app creation), and some experience. Current experience shows that I will get better if I keep tackling a variety of projects with the same frameworks, languages, and features.
- Reminder: Nothing is too hard to code, if given enough time, commitment, and determination. Some days just go smoother than others.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl

## [46] Day 47: 2018-01-03

### Today's Progress

1. Coded alongside SVG examples in ch1 & ch2.
2. Updated animated stoplight with JS, replacing the CSS keyframes.

### Time Spent

1 hr 10 min

### Ideas/Techniques Learned

- `<text>` tag for text.
- SVG is XML and CSS. The two should not be separated. Though it's graphical, it is still a language in and of itself.
- `<!CDATA[]]>` parses code as plain text. Used in standalone SVG file to wrap JS scripting.

### Thoughts, Ideas, Questions

- I knew a perk of SVG is accessibility. But I never thought about how accessible it could make maps, if created in SVG. Something to explore further.
- Not only is SVG suited for icons and images, but it's strength lies in compatability with other languages to make a more interactive experience (widgets, maps, charts, and more).
- I so so so <3 front-end work and coding. Learning it takes me away to another place where time doesn't exist. This is really the work I would prefer, though I want to understand what programming languages like JS and Ruby/Rails can do in concert.

### Project I worked on

- SVG experiments from scratch: [SVG stoplight](https://codepen.io/digilou/full/eyRamX/)

### Resources I found helpful

- [Using SVG with CSS3 & HTML5](https://github.com/oreillymedia/Using_SVG)

## [45] Day 46: 2018-01-02

### Today's Progress

1. Coded alongside SVG examples in ch1.
2. Created animated (CSS keyframes) stoplight.

### Time Spent

1 hr 50 min

### Ideas/Techniques Learned

- SVG is XML.
- `<g>` is for grouping.
- `<defs>` is defined styles that can be reused in `<use>`.
- `cy` changes to `y` when `<circle>` is replaced by `<use`.

### Thoughts, Ideas, Questions

- New coding book for Xmas!! Perfect time to try out something fun when I'm sick.
- Coding alongside reading is the best way to learn. Typing it out slows me down to assimilate it into my knowledge, and challenges me to see if I get the same results on my local environment.

### Project I worked on

- SVG experiments from scratch: [SVG stoplight](https://codepen.io/digilou/full/eyRamX/)

### Resources I found helpful

- [Using SVG with CSS3 & HTML5](https://github.com/oreillymedia/Using_SVG)

## [44] Day 45: 2018-01-01

### Today's Progress

1. Wrote integration tests for edit/update profile page.
2. Refactored form to user#new and user#edit to be shared by a partial.
3. Set up `before_action` to create authorization of editing/updating profiles.

### Time Spent

1 hr

### Ideas/Techniques Learned

- `before_action` can be used to limit access to users. It's a built-in feature of rails.

### Thoughts, Ideas, Questions

- In the midst of holidays and sickness, I could start over in a week or so, but I figure some progress is better than no progress. However, this may be my last 100 Days of Code commitment so I can be more flexible with family this year.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl

## [43] Day 44: 2017-12-31

### Today's Progress

1. Wrote specs and spec helpers to complete advanced login with remember me token/digest with checkbox on view.
2. Started ch 10 of Hartl's Rails tutorial, which includes updating, showing, and deleting users.
3. Set up edit user page.

### Time Spent

1 hr 5 min

### Ideas/Techniques Learned

- `rel="noopener"` can be added to a link prevent a third-party phishing page from a security breach which gives the new page access to the `window.opener` object.

### Thoughts, Ideas, Questions

- I like the idea of BDD, but I still haven't got into the thinking yet. The syntax of RSpec being a stumbling block.
- Tried to breeze through ch9. My son's cold is taking a toll on me, and I'm getting tired of hanging out in login setup for so long.
- I've underestimated how many views/pages need to go into just user access like login and editing.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl
- [Open External Anchors using rel='noopener'](https://developers.google.com/web/tools/lighthouse/audits/noopener)

## [42] Day 43: 2017-12-30

### Today's Progress

1. Read through WWC code changes to add OmniAuth, so I could get ideas.
2. Coded alongside ch 9 of Rails Tutorial to add remember_me token.

### Time Spent

1 hr 45 min

### Ideas/Techniques Learned

- `attr_accessor`: creates “getter” and “setter” methods that allow us to retrieve (get) and assign (set) instance variables.
- Rails time helpers
- There's a difference between token and digest when creating a remember_me token. My brain finally caught on near the end of my hour of coding.

### Thoughts, Ideas, Questions

- The more you know... Thought of the day: in coding, it takes a lot of perserverance of feeling stupid for awhile before you in start feeling confident and smart.
- Gah! The last 3-4 days I have been so tired with my child not feeling/sleeping well. So, I feel lost in my coding and that time spent isn't really productive. I have to remember that this too shall pass, and that taking a couple steps forward is still moving forward, none-the-less.
- "Remember Me" token all complete except for specs.
- Practiced working through coordination of controller, helper, model, and view. Modulation is helpful, yet confusing, at times, to find all the pieces.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl
- [WWC OmniAuth branch](https://github.com/WomenWhoCode/website/pull/2622/files)
