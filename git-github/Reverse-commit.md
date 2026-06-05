# Git Commands (Undo / Reset)

## Show Commit History

```bash
git log --oneline
```

**Use:** Show commit history

---

## View Old Code (Temporary)

```bash
git checkout <commit-id>
```

**Use:** View old code temporarily

---

## Reset to Previous Version

```bash
git reset --hard <commit-id>
```

**Use:** Delete wrong commits and go back to that version

---

## Push Changes to GitHub (Force)

```bash
git push origin main --force
```

**Use:** Update GitHub after reset

---

## Create Backup Branch

```bash
git branch backup
```

**Use:** Create backup before making changes

---

## Revert Commit (Safe Undo)

```bash
git revert <commit-id>
```

**Use:** Undo commit without deleting history

---

## Go Back N Commits

```bash
git reset --hard HEAD~n
```

**Use:** Go back n commits (e.g., HEAD~2 = 2 commits back)
