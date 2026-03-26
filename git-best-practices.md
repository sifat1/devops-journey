# Git Best Practices for DevOps

## Daily Commands
- `git status` - Always check before doing anything
- `git log --oneline --graph` - Visualize history
- `git fetch` - Get latest from remote without merging

## Branch Naming Convention (Recommended)
- `feature/<short-description>`
- `bugfix/<issue>`
- `chore/<task>`
- `docs/<topic>`

## Commit Message Best Practices
- Use present tense ("Add README" not "Added README")
- Keep first line under 50 characters
- Add body if needed for explanation

## .gitignore
- Never commit sensitive files, logs, or build artifacts
