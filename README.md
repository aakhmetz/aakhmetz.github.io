# aakhmetz.github.io

Personal academic website of **Andrei R. Akhmetzhanov (吳亞克)**, Associate Professor at the [Global Health Program](https://globalhealth.cph.ntu.edu.tw/) and the [Institute of Epidemiology and Preventive Medicine](https://www.ieph.ntu.edu.tw/), College of Public Health, National Taiwan University, Taipei, Taiwan.

🌐 **Live site:** https://aakhmetz.github.io

## About

This site is built with [Academic Pages](https://github.com/academicpages/academicpages.github.io), a Jekyll-based GitHub Pages template. It features:

- Publications and research outputs
- Talks and presentations
- Teaching activities
- CV
- Research group information

## Running locally

1. Install Ruby dependencies:
   ```bash
   bundle install
   ```
2. Serve the site:
   ```bash
   bundle exec jekyll serve -l -H localhost
   ```
3. Open http://localhost:4000 in your browser.

## Using Docker

```bash
chmod -R 777 .
docker compose up
```

Then open http://localhost:4000.
