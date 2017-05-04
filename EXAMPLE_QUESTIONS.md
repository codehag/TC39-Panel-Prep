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

- Jan Krutisch has an interesting talk ( or talk proposal) about the aesthetics of code.
  Aesthetics are important, they have a lot to do with the human experience of coding. How\
  much aesthetics goes into the consideration of building the api? what are some new
  directions that these aesthetics are going?

- The language has come a really long way since it was first released. However there is
  a certain amount of responsibility that comes with developing something as widely used
  as javascript.For some, this has resulted in too much baggage. Some people would go as far
  as to say "just throw everything out. How do you manage the history of javascript, and new
  feature implementation?

- There are a lot of features that get worked on but do not necessarily make it to the
  language, and it would be interesting to discuss these as not failures, but learning
  points. Is there an example of an interesting feature that didn't make it into the
  language, or was depricated. In my experience, one such example is object.observe. some other examples are listed online [in the github page](https://github.com/tc39/proposals/blob/master/inactive-proposals.md)
  Why it is a benefit (or a detriment) that it didnt make it in to the language specification?
  What is the process of deciding that "gee it doesnt work the way we wanted it to" and what
  can we take away from those moments?

### Technical questions: (not too sure about this)

- An exciting new feature that is upcoming is Shared array buffer, also discussed by
  Nidin Vinayakin.This is a particularly interesting development because it allows
  javascript to perform much better and also potentially rival native applications.
  However concurrency is hard, how do you see this feature start to get picked up?
  (was thinking about this
  https://hacks.mozilla.org/2016/05/a-taste-of-javascripts-new-parallel-primitives/)

- Many features can be polyfilled or transpiled. However some features cannot. One
  such example (at least in my experience) is WeakMap. It was introduced in es2015,
  and was one of the only features that could not be polyfilled by something like
  babel. I find it interesting because its in the spec, but it doesnt get much use.
  What do you think some of the reasons for this are? How does the
  "transpile-ability" of a feature affect its use and is this an issue?

- follow up question regarding WeakMap -- It is supported by Firefox, Chrome, and
  Edge, where is a good common place to use it?

- what is the feature you are most excited for? What would you like to see implemented?

### Community involvement:

- Ideally, where would you see the work by the TC39 going? How do you see the community developing?

- It can be overwhelming to start looking at contributing to a project like this.

- We talked at the beginning how the community is an important part of getting
  features approved. What about further ways people can get involved? Are there
  any forms of mentorship within the community? Any places where discussions
  take place where one could join?
