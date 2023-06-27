---
name: Quality Standards
about: "[More an internal] issue template to keep track of all quality best-practices."
title: Establish quality standards
labels: 'automation'
assignees: ''

---

```[tasklist]
### Repository Standards
- [ ] Has nice [README.md](https://github.com/figuren-theater/new-ft-module/blob/main/README.md)
- [ ] Add [`.github/workflows/ft-issue-gardening.yml`](https://github.com/figuren-theater/new-ft-module/blob/main/.github/workflows/ft-issue-gardening.yml) file (if not exists)
- [ ] Add [`.github/workflows/release-drafter.yml`](https://github.com/figuren-theater/new-ft-module/blob/main/.github/workflows/release-drafter.yml) file
- [ ] Add [`.github/workflows/update-changelog.yml`](https://github.com/figuren-theater/new-ft-module/blob/main/.github/workflows/update-changelog.yml) file
- [ ] Add [`.editorconfig`](https://github.com/figuren-theater/new-ft-module/blob/main/.editorconfig) file
- [ ] Add [`.phpcs.xml`](https://github.com/figuren-theater/new-ft-module/blob/main/.phpcs.xml) file
- [ ] Check that `.phpcs.xml` file is not present in `.gitignore`
- [ ] Add [`CHANGELOG.md`](https://github.com/figuren-theater/new-ft-module/blob/main/CHANGELOG.md) file
- [ ] Add [`phpstan.neon`](https://github.com/figuren-theater/new-ft-module/blob/main/phpstan.neon) file
- [ ] Run `composer require --dev figuren-theater/code-quality`
- [ ] Run `composer normalize`
- [ ] Run `vendor/bin/phpstan analyze .`
- [ ] Run `vendor/bin/phpcs .`
- [ ] Fix all errors ;)
- [ ] commit, PR & merge all (additional) changes
- [ ] Has branch protection enabled
- [ ] Enable repo for required **Build, test & measure** status check via [Org >> Settings](https://github.com/organizations/figuren-theater/settings/actions)
- [ ] Add **Build, test & measure** badge to the [code-quality](https://github.com/figuren-theater/code-quality) README
- [ ] Submit repo to [packagist.org](https://packagist.org/packages/figuren-theater/)
- [ ] Remove explicit `repositories` entry from [ft-platform](https://github.com/figuren-theater/ft-platform)s `composer.json`
```

```[tasklist]
### Plugin Standards
- [ ] Has `DE_**` translation(s) available (if present in the UI)
```

```[tasklist]
### Theme Standards
- [ ] Is labeled as **Block Theme**
- [ ] Is labeled as **accessibility-ready**
```


