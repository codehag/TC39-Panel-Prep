# Final Draft
This draft contains the flow of the panel, plus potential questions that might be used to move it
along.

**Important Note on Panel Flow**

Since we only have 25 minutes, I will use a hand gesture to signal you if we need to move on or give someone a chance to speak.
Make sure to glance at me every now and then to see if I am signaling.

Gesture: **I will raise my hand while holding the pen.**

When you see this, please round off your point as best as possible with one or two sentences.

## Gentle intro:
_Purpose: Get the audience up to speed, so that no one feels left behind._
Estimated time: 10~ minutes

### Topics:
- What is TC39 and what does it do?
- Who are the members?
- what is consensus?
- what is your experience working on new features for the language (how did you get involved,
  features you feel strongly about, etc)

#### (Community) Questions:

- @chekofif
  Where does the line between library and language feature get drawn? For example, should, or not, observable be added to the standard?#tc39qs

- How do you read proposals? Lupe

## In-depth discussion:
_Purpose: Get into some interesting discussions. This will be pretty free-form. We could gently
ramp into the discussion by starting with some personal experience stuff and then move into
technical territory._
Estimated time: 10~ minutes

### Topics:
- What are the main language features that are under development?
- Classes and where they are going this year
- what is the feature you are most excited for? What would you like to see implemented?
- Proposal sepecific questions from the community

#### Community Questions

##### Class related questions
-  I saw this article http://2ality.com/2012/07/esnext-classes.html but since class and prototype work differently and prototype cannot imitate everything from classes, I wonder if it is really just syntactic sugar or since they work the same it should be considered as syntactic sugar. #tc39panel

- Sona Leeojosoeun May 30
  After reading this document(https://github.com/tc39/proposal-private-methods … …), I wanted to know why the “#” sign is used to express private. Most other language use “private” keyword to express private #tc39panel

##### General Questions (from last year)
- Any plans for a general-purpose abort/cancellation primitive in JavaScript? We now have AbortSignal on the web to abort an ongoing fetch, but there’s no equivalent in Node. @jsconfeu #tc39panel Mattias Buelens@MattiasBuelens

- Navigating the JS perf minefield is hard, and explaining it to others is harder. What can we do to improve this, Mike North @michaellnorth

- What did happen to Operator Overloading in ES? Wikipedia claims it’s on for ES8, but I can’t find a proposal? #tc39qs, & 0x0F

## This last year ...
_Purpose: Discuss some things that came up in the last year, and how the committee is handling them_
Estimated time: 5~ minutes

### Topics
- Smoosh -> flat
- Shared array buffer
- A better line of communication with developers

#### Community Questions

- none so far

## Getting people excited:
_Purpose: Round off the discussion, and get the community excited about the work that is being
done._
Estimated time: 10~ minutes

### Topics
- How is the community involved? How can it be more involved?
- where would you like to see the committee go in the future?
- What are some issues that the community faces in terms of its structural makeup, such as who is
  part of the panel and who is heard?
- Where do you see the community in the future?
- how can we help?

#### Community Questions

- Question from last year: Christian Kaestner speaking about how communities influence api's. Lets talk a bit about the roll of
  the community of developers around JS and how they influence the process for introducing features.
  With a project such as creating the spec for a language like JS, there are a lot of interested
  parties pushing for their interests to be added to the spec. How are vendors, such as browsers,
  influencing the development of new features? How do you balance the needs of JS developers and
  vendors?

# Moderator Extra Questions
These questions will be used if we are going too fast and need to fill out a block of time somehow
(or if I end up brain dead and cannot formulate a question on the fly!)

These are My questions:


### Intro:

- What is TC39? (see if there is someone willing to give a quick intro)

- ECMAScript has a release cycle that has four stages, lets talk a bit about each of
these stages and what is involved.

- (regarding stage 3) Browsers and transpilers play a pretty important roll in testing out a new
feature. Lets talk a bit about the role that community plays

### In-depth Discussion:

- Let's start from a personal perspective, how did you start workin on the ECMA / JavaScript spec?
  What is your story?

- a few of the conference speakers bring up how javascript has developed, and how the community
  has influenced that development. We have the talk by Harriet Lawrence about the
  sociolinguistics and the javascript community, any thoughts on this in relation to your work on the
  TC39?

- Christian Kaestner speaking about how communities influence api's. Lets talk a bit about the roll of
  the community of developers around JS and how they influence the process for introducing features.
  With a project such as creating the spec for a language like JS, there are a lot of interested
  parties pushing for their interests to be added to the spec. How are vendors, such as browsers,
  influencing the development of new features? How do you balance the needs of JS developers and
  vendors?

- As a follow up question to how communities and the specification interact, how is building a specification different from doing opensource work?

- There are a lot of features that get worked on but do not necessarily make it to the
  language, and it would be interesting to discuss these as not failures, but learning
  points. Is there an example of an interesting feature that didn't make it into the
  language, or was depricated. In my experience, one such example is object.observe. some other examples are listed online [in the github page](https://github.com/tc39/proposals/blob/master/inactive-proposals.md)
  Why it is a benefit (or a detriment) that it didnt make it in to the language specification?
  What is the process of deciding that "gee it doesnt work the way we wanted it to" and what
  can we take away from those moments?

### Community involvement:

- Ideally, where would you see the work by the TC39 going? How do you see the community developing?

- It can be overwhelming to start looking at contributing to a project like this. How can someone
  start?

- We talked at the beginning how the community is an important part of getting
  features approved. What about further ways people can get involved? Are there
  any forms of mentorship within the community? Any places where discussions
  take place where one could join?
