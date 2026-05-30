# CONTRIBUTING
This is a personal homelab repository. While external contributions are not sought after, feedback and issue reports are welcome.

*Format follows [Conventional Commits](conventionalcommits.org).*


## I. BRANCHES
All work is done on `dev` and merged to `main` when complete. Direct commits to `main` are never made. `main` represents finished work only.


## II. COMMIT FORMAT
```
    <type>(<scope>): <subject>

    [optional body]
```

## III. TYPES
- `feat`: new folder or file (unpopulated), new VM, lab implementations, etc.
- `fix`: correction to existing content (when errors exist) or lab bug
- `docs`: documentation addition (populated) or update with no functional lab change
- `refactor`: restructuring without adding, removing, or fixing content


## IV. SCOPE
Scope identifies the location of the repository where the change occurred. For example...

- `feat(phase-01/directory-services): add bulk user import script`
- `fix(docs/adr): correct ADR-001 status from Proposed to Accepted`
- `chore(root): fix three broken internal links in README`


## V. SUBJECT & BODY
- Subject line is lowercase with no period at the end
- Subject line is under 80 characters
- Body explains why, not what
- Never use vague subjects
- Do not specify file extension for Markdown files


## VI. FEEDBACK & ISSUES
If you have feedback on structure, documentation quality, or notice an error/inconsistency, please open a GitHub Issue. Issues are triaged on a best-effort basis.
