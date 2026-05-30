# Contributing
This is a personal homelab repository. While external contributions are not sought after, feedback and issue reports are welcome.

*Format follows [Conventional Commits](conventionalcommits.org).*


## Branches
All work is done on `dev` and merged to `main` when complete. Direct commits to `main` are never made. `main` represents finished work only.


## Commit Format
```
    <type>(<scope>): <subject>

    [optional body]
```

## Types
- `feat`: new project, VM, lab implementations, etc.
- `fix`: correction to existing content or lab bug
- `docs`: pure documentation addition with no functional lab change
- `refactor`: restructuring without adding or removing content
- `chore`: maintenance such as link fixes or formatting corrections


## Scope
Scope identifies the location of the repository where the change occurred. For example...

- `feat(phase-01/directory-services): add bulk user import script`
- `fix(docs/adr): correct ADR-001 status from Proposed to Accepted`
- `chore(root): fix three broken internal links in README`


## Subject and Body
- Subject line is lowercase with no period at the end
- Subject line is under 80 characters
- Body explains why, not what
- Never use vague subjects


## Feedback and Issues
If you have feedback on structure, documentation quality, or notice an error/inconsistency, please open a GitHub Issue. Issues are triaged on a best-effort basis.
