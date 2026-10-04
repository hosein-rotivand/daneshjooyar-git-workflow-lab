# Project Workflow

## Branches
- main: stable history
- develop: integration
- feature/*: new functionality
- release/*: release preparation
- hotfix/*: urgent fixes

## Typical feature workflow
1. Create a feature branch from develop.
2. Implement and test the change.
3. Review with git diff.
4. Commit with a descriptive message.
5. Merge into develop.
6. Open a Pull Request for review when collaborating.

## Versioning
Use MAJOR.MINOR.PATCH:
- MAJOR: incompatible changes
- MINOR: new backward-compatible features
- PATCH: backward-compatible fixes

## Safe recovery
Inspect git status and git log before recovery operations.
Prefer git revert for published commits.
Do not force-push shared branches without a clear reason.
