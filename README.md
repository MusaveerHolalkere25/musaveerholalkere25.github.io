# Musaveer Holalkere | Cloud & DevOps Engineer

Personal portfolio site: **https://musaveerholalkere25.github.io**

A fast, single-page site built with plain HTML and CSS. It has no framework, no build step and no JavaScript dependencies, just one `index.html` and a few assets.

## What's on the site

- **Selected work:** three project highlights from my professional experience (EKS landing zone, cloud cost-control automation, GitLab CI/CD delivery), summarized at a high level.
- **Public work:** [eks-fargate-lz](https://github.com/MusaveerHolalkere25/eks-fargate-lz), an open-source Terraform reference for a multi-environment EKS on Fargate platform, built from scratch.
- **About, expertise and experience:** skills, career history, certifications and education.
- **Contact:** email, LinkedIn and GitHub.

## Design notes

- Responsive layout: project cards go from three columns on desktop to stacked cards on mobile.
- Inline SVG icons, so there's no icon library.
- Dark theme with keyboard-visible focus states and reduced-motion support.
- Basic SEO: page metadata, Open Graph tags and `Person` structured data (JSON-LD).
- The only external request is Google Fonts.

## Repository structure

```
.
├── index.html                          # the whole site (HTML + CSS)
├── README.md
└── assets/
    ├── musaveer-professional.jpg       # profile photo
    ├── Musaveer-Holalkere-Resume.docx  # downloadable resume
    └── eks-fargate-architecture.svg    # diagram for the Open source section
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

The site is served by GitHub Pages from the `main` branch (root). Pushing to `main` redeploys it within a minute or two.

## A note on content

Client work is summarized at a high level and no client source code or implementation details are published here. The public repository linked above is an independent reference project.

## Contact

- Email: musaveer.a.h@gmail.com
- LinkedIn: https://www.linkedin.com/in/musaveerah
- GitHub: https://github.com/MusaveerHolalkere25
