---
name: Update ft-package
about: "[More an internal] issue template to update one of our packages"
title: "[UPDATE]"
labels: ''
assignees: ''

---

```[tasklist]
### branch  `develop` 
- [ ] Document, add & commit all changes to the repo
- [ ] `git pull` all PRs
- [ ] review and merge pulled PRs
- [ ] update dependencies with `composer update --no-install -vv`
- [ ] commit all changes to the repo
- [ ] bump version
- [ ] open PR on `main` branch
```

```[tasklist]
### branch  `main` 
- [ ] merge `development` PR
- [ ] tag commit with new version
- [ ] `git push && git push --tags`
```
