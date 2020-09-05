# Changes from upstream

Just rebase against upstream after fetching it

```
git fetch upstream

git co 2.0.x

git rebase upstream/2.0.x
```

# update branch to current tag

```
git rebase --onto newBase oldBase feature/branch
```
