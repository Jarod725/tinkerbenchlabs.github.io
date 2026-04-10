# TinkerBench Labs — Web

Static site for [tinkerbenchlabs.com](https://tinkerbenchlabs.com), hosted on GitHub Pages.

## Structure

```
index.html          # Company home
garagelog/          # GarageLog app landing page
privacy/            # Privacy policy
support/            # GarageLog support & FAQ
assets/css/         # Shared stylesheet
assets/images/      # Logo, app icon, screenshots
CNAME               # Custom domain for GitHub Pages
```

## Deployment

Push to `main` on the `tinkerbenchlabs.github.io` repo. GitHub Pages serves the root directly.

### NameCheap DNS

| Type  | Host | Value                        |
|-------|------|------------------------------|
| A     | @    | 185.199.108.153               |
| A     | @    | 185.199.109.153               |
| A     | @    | 185.199.110.153               |
| A     | @    | 185.199.111.153               |
| CNAME | www  | tinkerbenchlabs.github.io    |

## TODO before launch

- [ ] Add App Store link to `garagelog/index.html` (both badge locations)
- [ ] Add app icon / screenshots to `assets/images/` and wire into pages
- [ ] Fill in FAQ answers in `support/index.html`
- [ ] Confirm privacy policy effective date is current
- [ ] Enable HTTPS enforcement in GitHub Pages settings after DNS propagates
