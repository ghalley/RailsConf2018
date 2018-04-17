# RailsConf 2018

## DHH Keynote

Conceptual Compression:

- Like putting the SQL behind an ORM such that you don't need to know as much of it to use it.
- Why build yourself when you get it for free from something else?
- The list of things to know gets so long people get intimidated to even get started in it.
- allows for people with no programming understanding to get started quickly
  - gets around a lot of gatekeeping in programming

"Leaky Abstractions"

## Who Destroyed 3 Mile Island?

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

## Acces Denied

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

