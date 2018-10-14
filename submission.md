# Submission

[CFP close 11:59 PM AEST Monday 15 October](https://www.papercall.io/cfps/1406/submissions/new)

### Title

Failing for the right reason - a fresh look on TDD

### Elevator Pitch

- layered testing
- actual test driven
- techniques for organising your tests
- selena's secret sauce "a good time"  

_300 characters as exciting and enticing as possible_

  You'll walk out of this talk flipping all your testing practices on their
  head, find purpose in designing software through tests first and learn a
  framework of testing your complete stack that delivers value to the client
  and piece of mind in test driven working software.

### Talk Format

  20min

### Audience Level

  Intermediate

### Description

_contemporary experience, beyond single application, diversity, novel experiences or developments_

  The talk is a hands on style tutorial in a style of layered Behaviour Driven
  Design for modern web applications often with a SPA (Single Page Application)
  on the front end written in a framework like ReactJS and backed by Rails for
  the API as well as admin like functionality.

  This multi layer, outside in BDD stle is based on many years and companies
  worth of refinement to the techniques and described now as is used in
  Melbourne startup to build quality software.

  To make the code available and shareable the presnetation follows along an
  open source demo project implementation of the same style of testing
  approach.

  Participants will be taken though the various layers:

  **"Lifecycle Flow"** is the outer most layer of this BDD approach and follows
  along a flow of activity between 1 or more actors, usually driving a browser
  along many screens of a web style applications leading to one of a number of
  possible flow on effects. These flows usually represent a business process.

  **"Page/Component Mechanics"** are tests still run from a browser but
  focusing on a particular page or component on a number of places within the
  app and exercise specific behaviours that may come about from various states
  the application may find itself in.

  **"Frontend Compment Tests"** are used to test the usually javascript
  frontend framework implementation of the web page implementation. They allow
  for faster unit level teting of the various states the frontend can be in.

  **"External Integration Tests"** are a boundary that is fulfilled with a mock
  at most other layers of testing. This layer is performed separately to better
  control the effect of third party services.

  **"API Acceptance Tests"** define a boundary of the backend system and are an
  integration test of the backend unit as a whole. This allows for TODO ....

  **"Controller Unit Tests"** are written as unit tests as opposed to more
  standard RSpec integration tests. This is due to the API accpectance being a
  beter place to drive out the integration and means tests at this layer would
  only change with API changes.

  **"Domain Concpet Tests"** often a number of model classes in rails represent
  a join domain concept and it is worth testing their interaction.

  **"Domain Unit Tests"** are mostly done against the grain of RSpec and are
  unit tests and not integrated with the DB for variuos reasons TODO ...

  For each of these layers a summary will be given of:

  * how to define the unit under test and why
  * the kind of things that should and should not be tested and could break
    under this level
  * example test code

### Notes

Technical requirements:
  The talk is to be presented by 2 persenters, Selena Small and Michael
  Milewski. Both prsenters would prefer lapel microphones to allow easy
  movement on stage.

Best people for this subject:
  The style of Behaviour Driven Development (BDD) used at Fresho has been
  refined by it's core practitioner Perryn Fowler over the last 15+ years
  across his time at Thoughtworks and later in numerous companies. Michael
  Milewski picked up BDD from Perryn about 10 years ago and brings a wide
  variety of experience to the topic. Selena on the other hand is a new
  developer that specifically sought out Perryn to learn BDD and test driven
  development and brings a perspective of someone who has just freshly learnt
  the concpets.

  Together they present in accessible way from beginner through intermediate to
  experienced. Also basing the presentation on an open source demo of the style
  of testing gives participants of the talk a valuable resrouce to find out in
  more depth about this style of writing software.

2 people:
  Although either of us could present the subject we thought that it would be
  more approachable and lively if both of us were on stage. We also both
  encouraged each other to get this topic to a level at which we can present.
  That said Selena has applied to do another talk. As we understand it each
  presenter can only do 1 talk. If it happens that both her individual talk and
  this talk were to be selected to presnt, we would hope that there would be
  leniency to that ruling.

### Tags

rails, web development, testing, BDD, TDD

# Profile Details

### Name

Selena Small & Michael Milewski

### URL

### Organization or affliation

[Fresho!](https://fresho.com.au)

### Twitter Handle

@selenasmall88, @saramic

### Bio

  An unlikely yet dynamic duo of fist wielding professional Muay Thai fighter
  Selena Small from New Zealand and Polish born folk dancing Michael Milewski
  joining forces in building quality software and taking pairing, testing and
  developer practices to a new level at a small Melbourne based B2B startup in
  the fresho food industry, Fresho!

_notes: could focus more on other aims in development, hackathons, rails camps,
running, put coding ahead of partying_
