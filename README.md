# CV
Navid Komijani CV repo

This repo contains the CV's JSON file as an extension of the [Json Resume Schema](https://jsonresume.org/).
The JSON Resume is an open-source initiative to create a JSON-based standard for resumes. For developers, by developers.

## Steps to produce
Using the Google Chrome [JSON Resume Exporter](https://chromewebstore.google.com/detail/json-resume-exporter/caobgmmcpklomkcckaenhjlokpmfbdec) my [LinkedIn profile](https://www.linkedin.com/in/navid-komijani/) is exported as JSON and then edited for improvements.
```bash
# HTML
resume export docs/index.html --theme jsonresume-theme-eshaham

# PDF
resume export docs/index.pdf --theme jsonresume-theme-eshaham
```

## Theme
Themese can be founded here: https://npmjs.com/search?q=jsonresume-theme
Installed theme [jsonresume-theme-eshaham](https://www.npmjs.com/package/jsonresume-theme-eshaham)
```bash
npm install jsonresume-theme-eshaham
```

## GitHub Action
Using the [JSONResume Export GitHub Action](https://github.com/marketplace/actions/jsonresume-export), the CV output is exported to https://navidkom.github.io/cv/ after every change.
