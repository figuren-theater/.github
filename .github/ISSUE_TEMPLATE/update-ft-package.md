---
name: Update ft-package
about: "[More an internal] issue template to update one of our packages"
title: Update ft-package
labels: ''
assignees: ''

---

```[tasklist]
### branch  `develop` 
- [ ] Documented, added & commited all changes to the repo
- [ ] `git pull`ed all PRs
- [ ] reviewed and merged the pulled PRs
- [ ] updated dependencies with `composer update --no-install -vv`
- [ ] commited all changes to the repo
- [ ] bumped version
- [ ] opened PR on `main` branch
```

```[tasklist]
### branch  `main` 
- [ ] merged `development` PR
- [ ] tagged commit with new version
- [ ] `git push && git push --tags`
```
