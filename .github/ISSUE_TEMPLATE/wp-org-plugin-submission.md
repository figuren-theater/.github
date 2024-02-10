---
name: Submit to wp.org/plugins
about: "Keep track of all WordPress best-practices for submitting plugins to the svn repo."
title: Submit to wp.org/plugins
labels: 'automation'
assignees: ''

---

Including localised screenshots, if screenshots are showing translated UI elements.
https://developer.wordpress.org/plugins/wordpress-org/plugin-assets/#banner-filenames

```[tasklist]
### Add visuals & screenshots
- [ ] Normal Banner: `banner-772x250.(jpg|png)`
- [ ] Normal Banner (Localized): `banner-772x250-(rtl|es|es_ES).(jpg|png)`
- [ ] High-DPI (Retina): `banner-1544x500.(jpg|png)`
- [ ] High-DPI (Retina Localized): `banner-1544x500-(rtl|es|es_ES).(jpg|png)`
- [ ] Normal: `icon-128x128.(png|jpg)`
- [ ] High-DPI (Retina): `icon-256x256.(png|jpg)`
- [ ] SVG: `icon.svg`
- [ ] `screenshot-1.(png|jpg)` English image caption
- [ ] `screenshot-1-de.(png|jpg)` German image caption
```


```[tasklist]
### Prepare README & Submit
- [ ] Update readme to follow the Standards at https://wordpress.org/plugins/readme.txt
- [ ] Validate readme with https://wpreadme.com/
- [ ] Check that we followed all block guidelines at https://github.com/WordPress/wporg-plugin-guidelines/blob/block-guidelines/blocks.md
- [ ] Validate plugin using the https://wordpress.org/plugins/developers/block-plugin-validator/
- [ ] Run https://wordpress.org/plugins/plugin-check/ without failure
- [ ] Submit for Review
- [ ] Get plugin approved
```

```[tasklist]
### Automate deployment to .org
- [ ] Use …. Gh action
- [ ] Add content of CHANGELOG.md to generated readme.txt
```


```[tasklist]
### After Review
- [ ] Opt-in for the *community* plugins-taxonomy
- [ ] Opt-in for the *blocks* taxonomy, see https://developer.wordpress.org/plugins/wordpress-org/add-your-plugin-to-the-block-directory/
- [ ] > Go to https://wordpress.org/support/plugin/YOURPLUGIN and look at the sidebar on the right. Click the Subscribe to this Plugin button for email alerts.
```

