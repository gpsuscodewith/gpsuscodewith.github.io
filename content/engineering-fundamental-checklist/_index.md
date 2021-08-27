---
title: "Engineering Fundamental Checklist"
linkTitle: "Engineering Fundamental Checklist"
weight: 1
hide_summary: true
description: >
  This checklist helps to ensure that our engagements meet what we call our Engineering Fundamentals.
---

## Overview
This checklist is intented to help our partners understand the fundamental practices we expect your development team(s) are adhering to. There are other types of checklists out there, and we've chosen the minimum set of practices that 

### What if we aren't practicing these fundaments?
The first step is to use the checklist and mark off what you are practicing! Evaluate your level of maturity and have a conversation with one of our Technical Strategists where you share a plan to implement the practices. Once complete, a Code-with will be able to engage with you.

## Source Control

- [ ] The default target branch is locked.
- [ ] Merges are done through PRs.
- [ ] PRs reference related work items.
- [ ] Clear documentation of repository structure.
- [ ] Secrets are not part of the commit history or made public.

More details on [source control](https://docs.microsoft.com/en-us/devops/develop/git/what-is-version-control)

## Work Item Tracking

- [ ] A platform is used for backlogs, planning, etc.
- [ ] The board is organized and work items are prioritized

## CI/CD

- [ ] CI (Continuous Integration) with automated builds from the default branch
- [ ] CD (Continuous Deployment) to manage deployments to a replica environment before PRs are merged.
- [ ] Main branch should be shippable.

More details on [automated testing](https://www.thoughtworks.com/en-us/insights/blog/guidelines-structuring-automated-tests)
More details on [continuous integration](https://docs.microsoft.com/en-us/devops/develop/what-is-continuous-integration) and [continuous delivery](https://docs.microsoft.com/en-us/devops/deliver/what-is-continuous-delivery)

## Security

- [ ] Access is able to be granted on an as needed bases
- [ ] Secrets are stored in secured storage 
- [ ] Secrets are not checked in to source control

More details on [security](https://www.microsoft.com/en-us/securityengineering/devsecops)

## Observability

- [ ] Capable of implementing logging of business and functional events and collect metrics.
- [ ] Application faults and errors are logged.
- [ ] Health of the system can be monitored.
- [ ] GDPR compliance is ensured regarding PII (Personally Identifiable Information).

More details on [observability](https://martinfowler.com/articles/domain-oriented-observability.html)

## Software Development Methodology

- [ ] The process is clearly defined within team (a specific agile practice for example).
- [ ] The Dev Lead (+ PO/Others) are responsible for backlog management and refinement.

## Design Reviews

- [ ] Design reviews for each major component of the solution are carried out and documented, including alternatives.
- [ ] Stories and/or PRs link to a design document when one exists.
- [ ] Clear non-functional requirements captured

## Code Reviews

- [ ] There is a clear agreement in the team as to function of code reviews.
- [ ] The team has a code review checklist or established process.
- [ ] A minimum number of reviewers (usually 2) for a PR merge is able to be enforced.
- [ ] Capable of setting up any Linters/Code Analyzers, unit tests and successful builds for PR merges.
- [ ] There is a process for a quick review turnaround.

## Engineering Feedback

- [ ] The team submits feedback on business and technical blockers that prevent project success
- [ ] Suggestions for improvements are incorporated in the solution
- [ ] Feedback is detailed and repeatable

## Developer Experience (DevEx)

Developers on the team can:

- [ ] Build/Compile source to verify it is free of syntax errors and compiles.
- [ ] Execute all automated tests (unit, e2e, etc).
- [ ] Start/Launch end-to-end to simulate execution in a deployed environment.
- [ ] Attach a debugger to started solution or running automated tests, set breakpoints, step through code, and inspect variables.
- [ ] Automatically install dependencies
- [ ] Use local dev configuration values (i.e. .env, *.properties, appsettings.development.json).