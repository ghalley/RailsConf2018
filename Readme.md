# RailsConf 2018

DHH Keynote
------
------

Conceptual Compression:

- Like putting the SQL behind an ORM such that you don't need to know as much of it to use it.
- Why build yourself when you get it for free from something else?
- The list of things to know gets so long people get intimidated to even get started in it.
- allows for people with no programming understanding to get started quickly
  - gets around a lot of gatekeeping in programming

"Leaky Abstractions"

------

Who Destroyed 3 Mile Island?
------
------

@nmeans

"The Field Guide for Understanding Human Error" by Sidney Dekker
First Stories:

- Hindsight Bias, exaggerating your ability to have predicted it in the first place
- Outcome Bias, you judge decisions made based on knowing their outcome

Second Stories:

- understating the context in which people made decisions that led to something

Human Error is never the cause.

- as WHAT is responsible, not WHO
- understand WHY it made sense
- Seek FORWARD accountability, not backward.

Always look for the second story!

------

Acces Denied
------
------

Vladimir Dementyev
@palkan_tula

Authentication - answers "Who's there?"
Authorization - answers "am I allowed to do that?"

1. Granting and revoking access
2. How to verify access?

### Discretionary Access Control

Becomes permission records in DB

### Mandatory Access Control

Security clearance check ( a hierarchy of access to compare to )

### Role Based Access Control

Collects permission into one role that can be applied

### Attributed Based Access Control

### How to verify Access?

[Action Policy Gem](https://github.com/palkan/action-policy)

------

Keeping Moms for the Long Term
------
------

Being a mom in tech sucks:

- parental leave isn't good
  - more like maternity leave
  - companies have a huge impact on how much time you can actually take

Flex Schedule allows for unexpected things of raising a kid to not impede your job

Think about parents' needs around company outings or team-building events

Career Growth

- going home and learning more is not an option for parents

------

Tools for failing gracefully
------
------

1. Maintenance Mode
    - the fail whale mode

2. Read-Only Mode
    - no saving of information

3. Feature Flags
    - allows for controlled experience for when certain things aren't working

4. Rate Limits
    - Protection from malicious traffic
    - drops load effectively

5. Stop non-critical work
    - prioritize what needs to be computed

6. Known Unknowns
    - features or fixes that you're unsure of
    - Scientist Gem

7. Circuit Breakers
    - responsive shut-offs
    - cutting off things at a certain capacity automatically
    - hard close

Caveats:

- visibility
- does it actually work?
- knowledge vs control

------

The Practical Guide to Building an Apprenticeship
------
------

@megantiu

- Fulfills a real need.
- Unify and engage your team.
- create more diverse/inclusive organizations

an entry level job to allow for much more learning

focuses on growth, rather than internships that may focus on a project

You need:

1. A plan
2. Cash
3. Buy-in

Decide:

1. Program length
2. number of apprentices
3. who's going to do what

You *need* a game plan

### Hiring

establish an ubiased, level playing field

1. Application
2. Code Challenge
3. Final Interview

end-to-end anonymization to prevent bias

What does your background bring to the table?
Tell us about a problem that challenged you?

Numerical review values for data-driven decisions

Code Challenge:

- decide what you want to know
- figure out what format to use
- write the code challenge

used a script to anonymize commits and everything

Use an HR platform!
Don't limit code challenge to one language.

Set Goals for the apprentices

Similar onboarding experience as full time devs

Scavenger hunt!

Include lessons in some foundational concepts like OOP

Early exposure to the product development cycle

Team rotations doing customer facing work.

Apprenticeship Patterns

regular communication, via 1:1

include them in team rotation decisions

don't be afraid to let them fail

look for early warning signs and be proactive about intervening

ensure everyone is on same page for expectations

------

Upgrading Rails at Scale
------
------

Stop the bleeding first before developing features/bug fixes, at least on upgrade branch.

Failing tests can be marked and passed anyway to allow use of Continuous Integration so that they can come back to them while still using the CI.

Having more people actively working on the upgrade helps it go faster.

https://github.com/Edouard-chin

------

Here's to the Crazy Ones
------
------

