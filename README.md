# Layered Testing Presentation/Workshop

Talk/workshop on the idea of outside in multi layered behaviour driven layered testing workshop

## Inspiration

  - [x] confirm we can pull off a good talk at a Ruby meetup
  - [ ] would be good for work
  - [ ] should be fun
  - Presentation inspirations
    * **Tell a story**
      * https://www.youtube.com/watch?v=nChKjkG2NDw
        the video does not seem to do the talk justice bring in personal experience and story to better allow for the audience to be inspired and understand
      * all story example https://www.youtube.com/watch?v=WoTemqfZiHE
      * good stories and presence https://www.youtube.com/watch?v=nAEt36XNtAE
    * **Commit by Commit** to explain working
      * react - https://github.com/anhnk/tic-tac-toe/commits/master
      * redux - https://github.com/isaacrowntree/tic-tac-toe-redux-dojo/commits/master
    * **2 presententers**
      * [50 in 50 Keynote Guy Steele and Richard Gabriel](https://vimeo.com/25958308) - seeing this live was amazing, it is layered, legends in computers are presenting
    * **Get to the point quickly**
      * redux tutorial on egghead has short concises videos about different specific concepts https://egghead.io/courses/getting-started-with-redux
    * **A level of performance art**
      * https://www.youtube.com/watch?v=_z8FQdIbpJo This example being musical goes above and beyond, leaning towards some jokes is a start but clearly would be cool to get some energy across. Left-right keyboard pairing? pushups for broken tests?

## Skills

  - [ ] come up with a convincing example, key feature flow, that everyone immedaitely can relate to and intimately know and understand
    - social network
    - ecommerce
    - other ...
  - [ ] put together a commit by commit end to end example to run through all the layers of layered testing
  - [ ] break down the various layers, the kind of errors that are expected to occur, how to judge which tests should go where, which are unit/integration tests
  - [ ] understand the current views on testing
    - https://www.mountaingoatsoftware.com/blog/the-forgotten-layer-of-the-test-automation-pyramid
    - https://martinfowler.com/bliki/TestPyramid.html
    - https://martinfowler.com/articles/practical-test-pyramid.html
    - https://github.com/senpay/layered-test-framework-example
    - https://github.com/hyprnz/layered-testing
    - https://github.com/testdouble/test-smells/tree/master/smells/unnecessary/7-layer-testing
      - need for mocking and unit testing to prevent all testings failing
      - insided out Detroit-school TDD leads to various problems
    - https://www.infoq.com/articles/layered-test-automatation
    - https://www.gartner.com/doc/2645817/produce-better-software-using-layered
    - Idea from Nick at Rails Camp North Pine around domain object modelling with adapters for testing the domain directly or via ui?
  - [ ] presentation format? slides https://revealjs.com/
  - [ ] current layers
    * Process flow
    * Mechanics of a page
    * Frontend component tests
    * API integration tests
    * controller unit tests
    * model db integration tests
    * model unit tests
    * ... and what ever I have missed
  - ...

## Credibility

  - [ ] run workshop at ruby hack night
  - [ ] run workshop at rails camp
  - ...

## Win

  - [ ] run presentation at ruby meetup
  - [ ] run presentation at a conference
  - ...

## Glory

  :)

## Conference options

**Done:**

- [Ruby meetup Melboure](https://www.meetup.com/Ruby-On-Rails-Oceania-Melbourne/)
  - plan for November 2018
  - https://github.com/rails-oceania/melbourne-ruby/issues/111
  - DONE [Ruby.org.au video Oct 31](http://youtu.be/p72EPNXbjiU)

**Waiting:**

- [Ruby Conf AU](https://www.rubyconf.org.au/2019)
  - CFP ends 15 October https://www.papercall.io/rubyconf-au-2019
  - SUBMITTED waiting ⏱

- [Craft Conf - Budapest](https://www.papercall.io/craft-conf-2019)
  - May 9 - 10 2019
  - SUBMITTED waiting ⏱

- [ReactJS meetup](https://www.meetup.com/React-Melbourne/events/255823040/)
  - Tue Nov 27
  - SUBMITTED waiting ⏱

**Next submissions:**

- [React Amsterdam](https://goo.gl/forms/WZsgwz8WGvrlPyvH2)
  - April 11 - workshops
  - April 12 - conference
  - CFP open till Jan 15th 2019

- [EuRuKo Rotterdam](https://euruko2019.org/)
  - June 21-22 Rotterdam
  - CFP open till Feb 28th 2019 - [CFP](https://www.papercall.io/euruko2019)

- [Hack in Paris](https://www.papercall.io/hack-in-paris)
  - June 16th to 20th 2019
  - CFP closes December 10, 2018

**Possible submissions but no travel budget:**

- [Rubyfuza & friends](https://www.papercall.io/rubyfuza)
  - Feb 7-9 2019 Capetown
  - CFP close 15 December

- [Ruby Conf India](https://www.rubyconfindia.org/)
  - 20-21 Jan 2019
  - [CFP](https://www.papercall.io/rci19) - Nov 30

**Other:**

  - https://eventil.com/events?q%5Bcfp_open%5D=cfp_is_open

  - Ruby Conf 2019 Nashville, Nov 18-20, 2019! - http://rubyconf.org/

  - http://railsconf.com/ 2019 April 30 - May 2 2019 Minneapolis

  - https://rubyconferences.org/

  - [Ruby Conf Malaysia](https://rubyconf.my/) 25-26 October
    - missed it?

  - [Ruby Russia](https://rubyrussia.club/en) 6 October
    - CFP 15 September

  - [Rails Conf](http://railsconf.com/) - April 17-19 2018 - 2019 dates?
    - is there a CFP - https://eventil.com/events/railsconf-2019/cfp ?
    - https://cfp.rubycentral.org/events

  - [Ruby Conf](https://rubyconf.org/) - 13-15 Nov 2018
    - CFP closed Jul 31

  - any other https://www.papercall.io/events

  - or how do you got onto https://www.codercruise.com/speakers/

## Demo Blog

1. `rails new blog_demo`

## Slides

```
git clone https://github.com/hakimel/reveal.js.git
cp index.html reveal.js/index.html
cd reveal.js
npm install
npm start
open http://localhost:8000/
```

