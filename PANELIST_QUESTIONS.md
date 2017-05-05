# Panelist Questions

This page is dedicated to Panelist Questions. Are you working with the TC39 panel? Got a feature
that is proposed? Have a questions you would love to see discussed or would love to discuss? Feel free to add it!

### Questions Collected:

Would love community feedback/questions on [https://github.com/maggiepint/proposal-temporal
…](https://github.com/maggiepint/proposal-temporal) -
trying to get this one right!
- Maggie Pint (@maggiepint)

### Notes From Dan's (@littledan) Twitter thread

- What should we make sure *not* to mess up in JavaScript? What needs to stay out?

- Rationales help with avoiding repeating past mistakes and make it much simpler to figure out what’s going on.

- The standardization of Observables (streams) and better support for FP: the pipe operator, pattern matching, immutable data structures, etc.

- More fp built-in. composition, curry, pattern-matching, Maybe type.

- Someone with experience with designing standard libraries should work on extending JS’s (via modules!). Esp. processing coll.

- Deprecate and remove the creepy implicit type casting!
(pragma mode, strong mode to keep from breaking stuff)

- Keep out: observables, leave it in user land. Put in: decimal128. Fixing 0.1 + 0.2 !== 0.3 would give JS a big edge in backend


- Bash &al eventually moved off of backticks & towards a *far* more versatile recursive $() syntax.  Template strings ought to recurse fwd too!

- I want weakref very bad! Overseers that can describe the world now, while not preventing dealloc.

- Please add Array.range([start=0, ]end[, step=1]) like Python. No range generator is a glaring oversight in JS.

- a module registry for users to be able to reflect on what modules there are, see the exports & maybe their imports.

