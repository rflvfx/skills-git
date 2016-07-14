# Git Cheat Sheet

```bash
git rebase -i HEAD~3          # squash last 3 commits
git stash push -m "wip"       # stash with message
git cherry-pick <sha>         # pick a commit
git reset --soft HEAD~1       # undo commit keep changes
git reflog                    # recover lost commits
git log --oneline --graph     # visual history
git bisect start              # find buggy commit
```
