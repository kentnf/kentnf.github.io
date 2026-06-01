# MOILab Website

Static website for **MOILab** — Laboratory of Horticultural Omics Big Data Integration and Utilization, Beijing University of Agriculture.

**Live:** [lab.moilab.net](https://lab.moilab.net)

## Structure

```
moilab-web/
├── index.html        # Home — lab intro + research projects
├── members.html      # Lab members (current + former)
├── databases.html    # Databases & tools listing
├── news.html         # News & publications
├── style.css         # Shared stylesheet
├── images/           # All site images
└── wordpress_backup/ # Original WP backup (not deployed)
```

## How to Update

The site is pure static HTML/CSS. To make changes:

1. Edit the relevant `.html` file directly
2. Replace images in `images/` if needed
3. Push to GitHub → auto-deploys to GitHub Pages

### Common Tasks

**Add a member:** Copy a `.member-card` block in `members.html`, update name, email, and image src.

**Add a publication:** Add a `<li>` to the `.pub-list` in `news.html`.

**Add a database/tool:** Add a `.media-row` block in `databases.html`.

## Deployment

This site is deployed via **GitHub Pages**. Push to the `main` branch to trigger deployment.

For custom domain (`lab.moilab.net`), set up a CNAME record pointing to `<username>.github.io`.

## Original Site

This site was migrated from WordPress + Hestia theme. The original backup is in `wordpress_backup/`.
