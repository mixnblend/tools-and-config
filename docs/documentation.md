# Project Documentation

## Goals

An engineer, when they come onto a team, should be able to have all dependencies and tools installed and the application running within a morning.

## Context

The faster a new team member can become productive on a project, the faster the point at which they will feel that they’re an actual member of that team.

Documentation that captures succinctly everything there is needed to get a project up and running reduces the bus factor on that project.

If succinct but comprehensive documentation is automatically browseable and searchable across the organisation it helps promote knowledge sharing and allows other teams to quickly see what is in use.

How we as a function approach things such as documentation acts as a good motivator and indicator for how we approach larger concerns.

## Structure

The documentation should provide the following resources:

- README with the following sections:
- A paragraph describing what the project does
- Table of Contents
- Quickstart (a short, sharp guide on how to get started)
- Contributing (a short description or link to a document on how to contribute to the project - branching strategies, commit message formats, merge request rules etc)
- Testing (what testing frameworks and tools are used and why/how)

Additional Documents (links to additional documents in a /docs folder including, but not limited to):

- Pre-requisites (list of prerequisites to get the project set up)
- Contributing (any detailed notes on contributing to the project)
- Gotchas (any common project pitfalls and gotchas experienced in setting up the project)
- Any additional tooling in use on the project and the reasons why (use of git hooks, config generation etc).
- Architectural diagrams
- Notes on available environments
- Notes on dependency management tools in use (asdf, jenv, etc).
- Release process outline
