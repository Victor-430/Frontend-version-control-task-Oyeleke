# Frontend-version-control-task-Oyeleke

- Flexisaf internship week 4 task. Create a collaborative version control project using Git and Github.

## Purpose

- To access my understanding of:
- Version control workflows
- Collaboration practices such as creating and reviewing pull requests, creating branches etc..
- Git commands e.g git pull, git commit --amend etc..

## Branch Structure

### Main Branch

Purpose: Stable branch with all features

### Feature Branches

#### 1. feature-header (merged)

- **Purpose**: Implement header component
- **Commits**:
  - Initial HTML structure
  - Basic styling
  - Navigation menu

#### 2. feature-footer (merged)

- **Purpose**: Implement footer component
- **Commits**:
  - Copyright text
  - Social media links
  - Footer styling

#### 3. feature-header-new (renamed)

- **Purpose**: Renamed from feature-header for clarity
- **Status**: Demonstrates branch renaming workflow

## Pull Request Screenshots

### Header Component PR

[Header PR](<./Screenshot (Header).png>)
_Pull request showing code review and approval process_

### Footer Component PR

[Footer PR](<./Screenshot (Footer).png>)
_Pull request showing code review and approval process_

## Git Commands used

# Branch Management

- git checkout -b <branch-name> # Create and switch to new branch
- git branch # List all branches
- git branch -m <old> <new> # Rename branch

# Committing Changes

- git add . # Stage all changes
- git commit -m "message" # Commit with message
- git status # Check working directory status

# Synchronization

- git push origin <branch> # Push branch to remote
- git pull origin main # Pull latest changes
- git fetch origin # Fetch remote changes

# History & Inspection

- git log --oneline # View commit history

# Reversion

- git revert HEAD # Revert last commit
- git reset --hard HEAD~1 # Remove last commit (local only)

# Collaboration

- git checkout main # Switch to main branch
- git merge <branch> # Merge branch (local)

# Naming convention used for collaboration

- feat: new feature
- fix: bug fix
- style: formatting, styling
- docs: documentation changes

**Examples used in this Project:**

✅ feat: add basic header HTML structure
✅ style: add footer styling and layout
✅ feat: create footer with copyright text

# Lessons Learned

1. Branch Strategy

Creating feature branches keeps main branch stable

helps keep each feature isolated for independent development and review

2. Commit Granularity

Small, focused commits make history readable and reversions easier

Each commit addresses one specific change

3. Pull Request Reviews

Code review process catches issues early

4. Revert vs Reset

git revert is safer for shared branches, git reset for local-only changes

Used revert for pushed commits to maintain history integrity

5. Branch Naming

Descriptive branch names improve team collaboration

Used feature-\* prefix for clarity e.g feature-header

6. Commit Messages

Conventional commits improve project maintainability

Used standardized prefixes for all commits e.g feat

# Challenges Overcome

- Merge Conflicts: Learned to resolve conflicts when branches diverge
- Remote Sync: Understood push/pull workflow with remote repository
- Branch Management: Practiced creating, switching, and deleting branches
- History Navigation: Used git log to understand project timeline
