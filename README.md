# insurance-regulatory-insight

Hunny Sachdeva's professional portfolio and GitHub Pages home for the **Insurance Regulatory Insight** newsletter — IRDAI regulations, industry trends, customer protection and leadership insights.

- Live site: https://hunnysachdeva.github.io/insurance-regulatory-insight/ (or repo root, depending on Pages setup)
- LinkedIn newsletter: https://www.linkedin.com/newsletters/insurance-regulatory-insight-7504091886962266112

## Structure

```
insurance-regulatory-insight/
│
├── index.html              # Portfolio homepage (About, Experience, Skills, Insights, CV, Contact)
├── style.css                # Shared stylesheet
├── README.md
│
├── images/
│   └── issue-01-cover.svg   # Minimalist cover graphic for Issue 01
│
├── assets/
│   └── Hunny-Sachdeva-CV.pdf
│
└── issues/
    └── issue-01/
        └── index.html        # "Customer Interest Before the Sale"
```

## Adding a new issue

1. Duplicate `issues/issue-01/` as `issues/issue-02/`.
2. Replace the title, meta, standfirst and body content.
3. Generate a new cover SVG (copy `images/issue-01-cover.svg` and swap the issue number/title).
4. Add a new `.pub-card` block to the "Insights & Publications" section in `index.html`, linking to the new issue.

## Publishing

This repo is set up for GitHub Pages. In **Settings → Pages**, set the source to the `main` branch, root folder. If publishing at the repo path (`hunnysachdeva.github.io/insurance-regulatory-insight/`), all links here are already relative and will work as-is.
