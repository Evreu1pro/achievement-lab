# Pair Extraordinaire without an alt account

You need a **different real person** (or their GitHub identity) on a merged PR:

```
Co-authored-by: Name <ID+login@users.noreply.github.com>
```

## Legal options
1. Friend/colleague with GitHub — one shared docs PR
2. Open-source pair session — dual co-author on a real fix
3. Hackathon / study group teammate
4. Maintainer adds you as co-author on a collaborative commit (rare; ask politely)

## Not recommended
- Second account you control only for badges
- Random Co-authored-by of strangers without consent

Get email form: profile → green contribution square → commit → copy noreply email, or use `gh api users/LOGIN --jq .id` then `ID+LOGIN@users.noreply.github.com`.