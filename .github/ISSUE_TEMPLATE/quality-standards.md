---
name: Establish quality standards
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
- [ ] Add [`.github/workflows/prerelease-changelog.yml`](https://github.com/figuren-theater/new-ft-module/blob/main/.github/workflows/prerelease-changelog.yml) file
- [ ] Add [`.editorconfig`](https://github.com/figuren-theater/new-ft-module/blob/main/.editorconfig) file
- [ ] Add [`.phpcs.xml`](https://github.com/figuren-theater/new-ft-module/blob/main/.phpcs.xml) file
- [ ] Check that `.phpcs.xml` file is not present in `.gitignore`
- [ ] Add [`CHANGELOG.md`](https://github.com/figuren-theater/new-ft-module/blob/main/CHANGELOG.md) file with an *Unreleased-Heading*
- [ ] Add [`phpstan.neon`](https://github.com/figuren-theater/new-ft-module/blob/main/phpstan.neon) file
- [ ] Run `composer require --dev figuren-theater/code-quality`
- [ ] Run `composer normalize`
- [ ] Run `vendor/bin/phpstan analyze .` without errors
- [ ] Run `vendor/bin/phpcs .` without errors
- [ ] Fix all errors ;)
- [ ] commit, PR & merge all (additional) changes !
- [ ] Has branch protection enabled ?
- [ ] Add [`.github/workflows/build-test-measure.yml`](https://github.com/figuren-theater/new-ft-module/blob/main/.github/workflows/build-test-measure.yml) file
- [ ] Enable repo for required **Build, test & measure** status checks via [Repo Settings](/settings/actions)
- [ ] Add **Build, test & measure** badge to the [code-quality](https://github.com/figuren-theater/code-quality) README
- [ ] Submit repo to [packagist.org](https://packagist.org/packages/figuren-theater/)
- [ ] Remove explicit `repositories` entry from [ft-platform](https://github.com/figuren-theater/ft-platform)s `composer.json`
- [ ] Update `README.md` and fix **LICENSE-Link**, to see all workflows running
- [ ] Publish the new drafted Release as Prerelease to trigger auto-updating versions in CHANGELOG.md and plugin.php
```

```[tasklist]
### Plugin Standards
- [ ] Plugin is translation ready
- [ ] Has `de_DE` & `de_DE_formal` translation(s) available (if present in the UI)
- [ ] Run `npm run lint:js` without errors
- [ ] Run `npm run lint:css` without errors
- [ ] Run `npm run lint:pkg-json` without errors
```

```[tasklist]
### Theme Standards
- [ ] Is labeled as **Block Theme**
- [ ] Is labeled as **accessibility-ready**
```

```[tasklist]
### Plugins only
- [ ] Plugin is translation ready and already translated to de_DE and de_DE_formal
```

