# Week 5 Log

## [30] Day 31: 2017-12-17

### Today's Progress

1. Worked through some of Hartl's examples for setting up controllers and models for users and posts.
2. Add more ideas/revisions to app planning.
3. Started documenting setup of a Rails app for my own reference.

### Time Spent

1 hr 10 min

### Ideas/Techniques Learned

- Refresh: connecting controllers and models with `resource`, `has_many`, `belongs_to`, `validates :resource, presence: true`.
- Controllers are generated as plural: `Users`.
- Models are generated as singular: `User`.
- `Text` type allows more characters than `string`.
- My IOS Notes has turned out to be a good spot for "jotting" down concept/code ideas when I'm away from my source code and notebook. It saves to iCloud, so I can get to it on my MPB. One caveat, I have to upgrade macOS to see tables I create.

### Thoughts, Ideas, Questions

- Second go-around of Rails Tutorial is being absorbed faster, include creating controllers and models. I know it's because of my exposure to rails in p/t and volunteer work. Chicken-and-the-egg problem: which do I do first... read books and watch videos or makes something? Both help each other, so a healthy mix is needed. I guess each journey is different.
- To move forward, I'll roll my own authentication, but create a separate branch to experiment with Devise and OmniAuth.
- Thinking about starting up my ARIA tutorial app as I work through this one. That way the fresh ideas, like authentication and table generation are fresh. It could be a secondary project, if the burden of research isn't too much (since I've been out of a11y learning mode for several months).

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl

## [29] Day 30: 2017-12-16

### Today's Progress

1. Walked through some RailsCast tutorial about creating authentication from scratch.
2. Wrote down more plans for user and administrative features I want now and in the future.

### Time Spent

1 hr 40 min

### Ideas/Techniques Learned

- Learning authentication and authorization basics for Rails
- Repeat: planning before development is still so important!

### Thoughts, Ideas, Questions

- Confirmed: understanding Ruby DOES help. Lately I've been spending more time learning Ruby, and working through methods. BIG help when suddenly I have to define methods for users and sessions. I get it! I was able to easily work alongside the RailsCast because I understood the code.
- Still not quite sure what authentication route I'll go (scratch vs. gems), but I'll probably start out small from scratch, and add Facebook login as a feature later.
- Still deciding how to roll out featuers, which is P1 (priority one) or less priority (nice to have).
- I have to remind myself to keep it in check. Just because I can, doesn't mean I should. Evaluating the base functionality will help me reign in too many things.
- Tomorrow I will walk [Rails Tutorial](https://www.railstutorial.org/book/) by Michael Hartl to work through his authentication from scratch. RailsCast was helpful to watch, but it's outdated (not Rails 5).

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- [RailsCast: Authentication from Scratch](http://railscasts.com/episodes/250-authentication-from-scratch)
- [OmniAuth gem](https://github.com/omniauth/omniauth)

## [28] Day 29: 2017-12-15

### Today's Progress

1. Played with RSpec more. Added spec directory and moved test files to it.
2. Reviewed gems (Devise, Pundit) for help with authentication and authorization.
3. Walked through some Rails tutorials about creating authentication and authorization from scratch.

### Time Spent

1 hr 15 min

### Ideas/Techniques Learned

- Installing the RSpec gem doesn't automatically create a spec directory. I had to run `rails generate rspec:install`.
- Learning authentication and authorization basics for Rails
- I'd like to use Pundit and Devise later on down the road, without overwhelming myself too much.

### Thoughts, Ideas, Questions

- As a beginning, I feel like I'm wasting time on BDD (behavior driven development), but since this is all new to me, it takes extra time. I think it'll be more intuitive later on. Having wireframes and a list of user tasks in front of me helps a lot!
- As I feel my way through RSpec, I need to continue learning about development of the features I want.

### Project I worked on

- Rails photo-sharing app

### Resources I found helpful

- other people's source code
- [RSpec Rails](https://github.com/rspec/rspec-rails)
- [Pundit](https://github.com/elabs/pundit)
- [Devise](https://github.com/plataformatec/devise)
