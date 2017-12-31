# Week 7 Log

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
