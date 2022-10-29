# Committing Changes to Git Repositories

I use [Conventional
Commits](https://www.conventionalcommits.org/en/v1.0.0/#summary) as a base
standard/system.

The basics:
```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```
## Examples:
`fix(admin): prevent race condition with requests`

## type
- fix: patches a bug
- feat: introduces new feature
- chore: cost of doing business, technical debt
- Other: build:, ci:, docs:, style:, refactor:, perf:, test:
- add a '!' if it is a BREAKING CHANGE (e.g. 'fix!:')

## scope (optional)
A scope MAY be provided after a type. A scope MUST consist of a noun describing
a section of the codebase surrounded by parenthesis, e.g., fix(parser):

