# Software Chatter, 2021-02-19 Leads: Sam Abbott and Naomi Waterlow

## Group discussion notes

### Group 1 (Emily Nightingale, Pablo Ruiz, Orlagh Carroll, Chathika Weerasuriya, Stefan Flashce)

- Difficult to let go of your coding style, different “styles” might not mix
well together
- No professional practices that prof soft eng use, academics
shoulds take these on board, eg GitHub. Enforcing code style could be very
helpful, benefits of everyone being able to read code. Linting (?)
- Working in a field where we need to learn a number of v different things, different angles,
diverse group within CMMID, computer scientist have a big advantage on coding
and should be utilised more. Benefit of tidy code for one self is minimal.
Incentive to write better code should be set as an agenda. Learn, take a step
back.
- Minimal experience in pair coding, more for interest. Could improve
reliability of code, but again little incentive of doing it. Huge gain in
getting things out quickly, but no penalty in getting things wrong. Strategy
that needs big amount of upfront planning. Might not work well for exploratory
analysis, but if there is a structured approach then could work very well.
Collaborative design of code should be an aim of the project. Can help expand
your vocabulary and how you code, can add to each other’s way of doing it. Could
be more beneficial to projects with no strict deadline. Need to have people with
similar skill levels. Need to speak the same “language”.
- Organise resources into
a group of core competencies? How to use tools available. (this is in progress,
TED courses).
- Software Sustainability Institute (https://software.ac.uk/)
- Learning and teaching Git, courses typically only run once a year. Deliver
basics, bare minimum


### Group 2: (Sam C. (notes), Sophie Meakin, Alicia Showering, Ellie Rees, Kath Sherratt)

- What’s the best way to set up a project from the start? Good Enough Practice in
Scientific Computing
- Constantly needing to revise code as though it’s a paper -
making it clear with commenting, making the code easier to read so that it’s
easier to share
- Breaking code up into more digestible chunks. If a
script/function’s purpose can’t be summarised in a sentence it may need to be
split up
- Splitting long scripts into a series of self-contained scripts that do
things (e.g. all data loading, all analysis, all plotting), as well as code
you’re tempted to copy and paste to reuse into functions collected together in
scripts. This can make it easier for others to read, and treating your code as
though you may want to package it up can help keep things clean from the start
(Wickham book https://r-pkgs.org/)
- Adapting style based on when you join a
project and who else is going to be looking at it. Is everyone using the same
approach to coding, e.g. tidyverse with long chains, optimised dplyr, or relying
as little as possible on external packages with base?

### Group 3 (Emilie, Sam A, Elena, Nikos, Ciara)

- Software Chatter sessions with peer review
- What feedback would be most helpful? - More stylistic rather than just
mistakes e.g. could this be set up in a better way?
- Issue = time/people’s bandwidth to review each other’s
- More structure in the parts of your code that you would like to get a review of
- code
- Authorships as an incentive
- Stylistic consistency = makes it much easier for other people to understand
  therefore easier to give valuable feedback
- Ideal situation: software engineer who can review your code

### Group 4 (Akira, Yang, Carl, Calum):
- Who does pair coding/ why pair coding may be challenging?
  - Can’t have too different a skill level, but some difference is needed..
  helps to avoid writing for a too specific (advanced) audience
  - Especially ‘live’ pair coding, with one driving and another watching
  - Pair coding and code review may feel similar but could be different sometimes.
  - Weird that we review papers so many times but not the code…
  - CD: worked on code with others, often checking every few weeks
  - YL: not much experience of getting people to look at code, some conventions
  to coding styles needed
  AE: sometimes done PC. Works best when in the same room and working directly
  on separate parts of the code. Not sure if it would work as well remote; also
  matters if the project is complex and needs to be restructured
  - Are we confusing PC with code review?
  - CP: PC is two people looking at the same screen at the same time; can be
  easier when done remotely; beneficial to be doing things at the same time,
  even if it seems like too much of a time investment; but can see off the
  problem of code being too hard to review later
  - CD: have done a little of this while in the review meetings… works really
  well when it happens, usually overcomes some key problems
  - CP: ‘Never enough time to do it right’ -- but realise that save a lot of time
  not having to do things over anymore..
  - YL: what if we lack the infrastructure to make this happen? What about when
  it is not organic and are working alone? Would mean allocating more than one
  modeller per project, of similar level and coding style
  - AE: If the project has two co-first authors it would be easy…(snap)

### Group 5 (David Hodgson, David Simons, Julia, Naomi, Tim):
- Are any of us currently doing code review? Not really. 
  - This is really atypical! Tools like Gitlab exist, but…
  - Tricky if working on your own and culture of individual freedom in academia > 
  - Lack of documentation and collaboration tools primarily becomes an issue with handoffs and turnover of staff. 


- How do we do more code collaboration and shared learning for everyone?
  - Honesty helps to take down the intimidation factor for people just starting out - lessons learned and “make new/more interesting mistakes than I did” from senior people on “here is my 500+ line vFinal_final.txt mess than I used for first R project” (cf Fail Fast)
  - Working side-by-side physically can work really well - similar to having a biological lab - peers working together. PIs often don’t want to see the code - has to move with ‘younger’ generation/ECRs in our institution who are doing the most coding in modern languages (R, Python, etc) 
  - Can do more of a peer buddy system (e.g. RD students and postdocs with each other) with code, similar to manuscripts.
  - Leads of the groups need to sign off on staff doing this at a minimum and sometimes set it up (would very much encourage time investment if so). 
- Need to figure out incentives - How do we sell to PIs and management? 
  -Cf research engineering group at Imperial - e.g. analysts writing differential equations in R but then others would port this elegantly into C
  - Worth thinking about standardised workflow guidance or template data repos (cf. Thibaut passed this along within CMMID, but doesn’t exist routinely)
  - Lots of cross-language principles exist for engineering and workflows
  - Nb some of the best documented/cleanest code tends to be from when you are forced to teach it, cf R Users Group presentations
  - Would such teaching or resource development count toward people’s teaching requirements rather than thrown in as another voluntary commitment? Think the answer to this from Faculties is yes (cf MSc Health Data Science)
  - This is an ongoing academic issue for all sorts of collaboration, not just code
-How has this worked this year given everyone is virtual?
  - CMMID has no code reviews routinely, but people post their code pretty openly (Github etc)
  - And collaborate very actively on Slack > Analysis pathways > rapid manuscript review (nominate 8 people for each paper)
