# Software Chatter, 2021-03-05
Lead: Tim Taylor

## Group discussion notes 

**Group discussion questions:**

- How could you incorporate testing within your work?
- What are the pros and cons?
- When is it appropriate to test more or less?
- What obstacles would you face?
- What approach would you take (including code changes) to testing the following
  script?
  - https://gist.github.com/tjtnew/4ce98ff40b9cee29056896e17db99754


### Group 1 (Akira, Sophie, Ciara, Ellie, Carl)

- Official way of testing is not necessarily clear in different languages
- Level of standards (is the code for product?) and practices are different in
  academia

### Group 2 (Tim, Emily, Katherine, Ruwan, Pablo)

- Struggle to separate testing between “data getting” (different data sources
  from many different places, messy data, use a package to create data in nicer
  format) and “data cleaning”.
- Good example, tricky. Ideal should separate data getting from data cleaning,
  view them as separate things, two different functions. If not possible, can
  do “mocking” where you pretend a function is returning something that it
  isn’t, mock data. Check that your cleaning process works on snapshot data, 
  which has been cleaned already.
- Testing experience is downloading data from internet. Used to manually testing,
  can be hard to get into if you haven’t done it previously. 
- Experience of doing tests expecting something to go wrong, but not done
  systematically.
- Need an abstraction of analytical workflow that lends itself to testing. R
  package environment help with these workflow. Can run tests using a keyboard
  shortcut.
- Usually testing more “organically” - manually checking/summarising output - 
  rather than writing explicit tests.

### Group 3 (Sam, Naomi, Yalda Yang)

- Sometimes we are doing testing anyways - learning the concept of “testing”
  helps us formalise the procedure, and incentivise us to think about what are
  the things that we need to keep an eye on.
- “Unit” testing is like starting from the bottom and towards the top so we can
  easily locate the issues if there are any. 
- `covr` can help locate the
  dimension that’s not covered. The idea behind it is “code coverage”.
- There are testing frameworks - `testthat` in R.
- Testing should be done as one works and moves along the development process.
  - Cons: time consuming, sometimes vulnerable to structural changes of the program;
  - Pros: very helpful to debugging, relevant for mechanistic modelling
  (probably less the case for mechanistic).
- Novel/ complicated processes should almost always incorporate testing. If we
  are just using routine/ standardized/ mature models maybe it’s okay. Sometimes
  time available is also the constraint.

### Group 4 (Joe, Thibaut, Chathika, Pally)

- Minimal experience in some of the group
- Some error handling and logging but nothing formalised - can be tested itself
- (package called testthat) - software developer soft skills not always trained
  in as an analyst
- Appropriate to test when collaboration
- Time-consuming -but ‘not a waste of time’!
- Stochastic complex models - where there are a lot ways it can differ when
  re-run - definitely worth doing.
- Need to learn principles of design at least of learning to design in a modular
  way- making code reproducible
- Culture change in academia required
- Cannot test everything - but foolproof against the most common - if using
  modular code - to inbuild code into each module to catch any issues - checks
  inside the functions might be computationally intensive 
