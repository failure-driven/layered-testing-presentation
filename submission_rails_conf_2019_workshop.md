# Submission

[CFP closes Jan 2019](https://cfp.rubycentral.org/events/railsconf2019/proposals)

### Title

Multi layer BDD for modern rails web apps

### Abstract

  Learn how to drive out functionality in a modern rails based web app with
  multi layered, outside in Behaviour Driven Development, BDD. To scale tests
  for a production scale app we will run you through the layers of testing that
  matter, from "system flow" integration specs through "page mechanics" specs
  that take a component through it's paces down through frontend component
  tests, API specs through to specs to integrate to outside services and
  everything in between. All the while building a fun app with Rails and
  ReactJS.

### Format

  Workshop

### Track

  Fundementals

### For Review Committee

Similar to the topic of the talk "Failing for the right reason - a fresh look
at TDD" but with step by step code examples. The aim is to build a web app game
using layered testing.

1. setup Rails and ReactJS to be deployable to Heroku or similar with fallback
   to vagrant setup
1. setup testing frameworks with tweaks to work with multi layer testing:
   RSpec, Capybara, Jest, Selenium webdriver, rubocop, ESLint
1. Run through 1 cycle of the full gamut of tests
  1. **“Lifecycle Flow”** is the outer most layer of this BDD approach and
     follows along a flow of activity between 1 or more actors, usually driving
     a browser along many screens of a web style applications leading to one of
     a number of possible flow on effects. These flows usually represent a
     business process.
  1. **“Page/Component Mechanics”** are tests still run from a browser but
     focusing on a particular page or component on a number of places within
     the app and exercise specific behaviours that may come about from various
     states the application may find itself in.
  1. **“Frontend Component Tests”** are used to test the usually javascript
     frontend framework implementation of the web page implementation. They
     allow for faster unit level testing of the various states the frontend can
     be in.
  1. **“External Integration Tests”** are a boundary that is fulfilled with a
     mock at most other layers of testing. This layer is performed separately
     to better control the effect of third party services.
  1. **“API Acceptance Tests”** define a boundary of the backend system and are
     an integration test of the backend unit as a whole.
  1. **“Controller Unit Tests”** are written as unit tests as opposed to more
     standard RSpec integration tests. This is due to the API acceptance being
     a better place to drive out the integration and means tests at this layer
     would only change with API changes.
  1. **“Domain Concept Tests”** often a number of model classes in rails
     represent a join domain concept and it is worth testing their interaction.
  1. **“Domain Unit Tests”** are mostly done against the grain of RSpec and are
     unit tests and not integrated with the DB.
1. Run through 2 more iterations to watch the tests evolve
1. Retrospect with an example of the code base that has been taken through a
   few more iterations

### Pitch

The style of Behaviour Driven Development (BDD) used at the workplace of the
presenters has been refined by the CTO and core testing practice lead at the
company over the last 15+ years across his time at Thoughtworks and later in
numerous companies. The presenters have diverse experience of BDD with 1
presenter 10 years and 20 years in software while the other presenter has less
then 3 years in software development and recently learning BDD. This gives them
a unique opportunity to address both experienced developers and up and comers
just learning by bringing a perspective of someone who has just freshly learned
the concepts.

Together they present in accessible way from beginner through intermediate to
experienced. Also basing the workshop on an open source demo of the style of
testing gives participants of the talk a valuable resource to find out in more
depth about this style of writing software.

Both of us are avid teachers of coders taking part in various locally organised
Rails Camps, coding Dojos, Rails Girls - Create Day.

### Speaker Information

**Selena Small and Michael Milewski**

An unlikely yet dynamic duo of fist wielding professional Muay Thai fighter
Selena Small from New Zealand and long time developer Michael Milewski.
Selena's relatively recent career switch to software engineering contrasted
with Michael's career being influenced by his developer father from a young age
allows for a very broad range of learning and experience that connects with a
wide range of audiences.

**Michael Milewski**

Developer keen on the people side of things. I love pairing, I love coding with
people new to writing software and especially driving out software with tests.
I am about scaling development through the team and their practices. I love new
technology and the challenge of assimilating to how my pair wants to write code
and together we should be greater then just the sum of the parts.

