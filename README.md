# TMI GLOBAL AUTOS 🚗

Official website project for **TMI GLOBAL AUTOS**, a car dealership in Lagos, Nigeria.

## Project structure

```text
.
├── index.html
├── images/
├── netlify.toml
├── robots.txt
├── sitemap.xml
└── README.md
```

## Deploy with Netlify + GitHub

This is a static HTML website. No framework or build step is required.

**Netlify settings**
- Production branch: `main`
- Build command: leave blank
- Publish directory: `.`

Connect the GitHub repository to Netlify. Future pushes to the production branch can automatically trigger deployments.

## Custom domain

The intended production domain is:

`https://tmiglobalautos.com/`

After the site is deployed, add the custom domain in Netlify under **Domain management → Production domains**, then follow Netlify's DNS instructions for the domain registrar.

## Updating cars

Vehicle images are stored separately in `images/` rather than embedded inside `index.html`. This keeps the HTML lightweight and makes GitHub uploads and website loading more manageable.

## Important

Do not commit passwords, API keys, private tokens, or other secrets to this repository.
