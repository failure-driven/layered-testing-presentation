# Submission

[CFP close 11:59 PM AEST Monday 15 October](https://www.papercall.io/cfps/1406/submissions/new)

### Title

Failing for the right reason - a fresh look on TDD

### Elevator Pitch
_300 characters as exciting and enticing as possible_

  Real code, live demo, learn to write tests to drive out code from the very
  beginning! Ever had difficulty writing tests? Don't know how to identify the
  unit under test? Find it hard to write tests BEFORE implementation? Join us
  as we take you on a journey through multilayer outside-in BDD.

### Talk Format

  20min

### Audience Level

  All

### Description

_contemporary experience, beyond single application, diversity, novel experiences or developments_

You have a great idea for a web app but you have no idea how it’s all going to fit together. Learn how to drive your design from the business level interactions that a user might make, right through to the smallest units of the domain with multi-layer outside-in behavioural driven design (BDD).

This talk is a hands on style tutorial which will enable developers to get started on their projects or improve the testing strategies within their own organisations. We’re going to run through building a simple web app written with a Rails API and React frontend, and tested using RSpec, Capybara, Selenium webdriver and Jest.

The multi layer, outside in BDD development style is based on many years and companies worth of refinement to the techniques from the perspectives of two developers who came from polar opposite backgrounds - One with over 20 years of commercial experience and a vast background in TDD, and one relatively new to software.

Participants will be taken though the various layers:

* **"Lifecycle Flow"** is the outer most layer of this BDD approach and follows along a flow of activity between 1 or more actors, usually driving a browser along many screens of a web style applications leading to one of a number of possible flow on effects. These flows usually represent a business process.

* **"Page/Component Mechanics"** are tests still run from a browser but focusing on a particular page or component on a number of places within the app and exercise specific behaviours that may come about from various states the application may find itself in.

* **"Frontend Component Tests"** are used to test the usually javascript frontend framework implementation of the web page implementation. They allow for faster unit level testing of the various states the frontend can be in.

* **"External Integration Tests"** are a boundary that is fulfilled with a mock at most other layers of testing. This layer is performed separately to better control the effect of third party services.

* **"API Acceptance Tests"** define a boundary of the backend system and are an integration test of the backend unit as a whole.

* **"Controller Unit Tests"** are written as unit tests as opposed to more standard RSpec integration tests. This is due to the API acceptance being a better place to drive out the integration and means tests at this layer would only change with API changes.

* **"Domain Concept Tests"** often a number of model classes in rails represent
  a join domain concept and it is worth testing their interaction.

* **"Domain Unit Tests"** are mostly done against the grain of RSpec and are unit tests and not integrated with the DB.

Attendees of the talk will walk away with a practical framework knowing

* What Unit is under test
* What to test at which level
* Which failures are expected to happen where
* A code repository with all these concepts

### Notes

  Technical requirements:

    The talk is aimed at beginners who may have heard about TDD, through to
    intermediate developers who just don’t know how to test all parts of their
    applications right through to advanced developers looking at how tests can
    scale in a large ruby/rails codebase.

    The talk is to be presented by 2 presenters. Both presenters would prefer
    lapel microphones to allow easy movement on stage and as there will be a
    small amount of live coding.

  Best people for this subject:

    The style of Behaviour Driven Development (BDD) used at the workplace of
    the presenters has been refined by the CTO and core testing practice lead
    at the company over the last 15+ years across his time at Thoughtworks and
    later in numerous companies. The presenters have diverse experience of BDD
    with 1 presenter 10 years BDD and 20 years in software development
    experience, while the other presenter has less then 3 years in software
    development and recently learning BDD. This gives them a unique opportunity
    to address both experienced developers and up and comers just learning, by
    bringing a perspective of someone who has just freshly learned the
    concepts.

    Together they present in an accessible way from beginner through intermediate
    to experienced. Also basing the presentation on an open source demo of the
    style of testing gives participants of the talk a valuable resource to find
    out in more depth about this style of writing software.

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
  the fresh food industry, Fresho!

_notes: could focus more on other aims in development, hackathons, rails camps,
running, put coding ahead of partying_
