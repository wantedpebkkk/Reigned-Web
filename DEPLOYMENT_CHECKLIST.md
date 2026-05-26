# Deployment Checklist

Use this checklist to fully put the site online with GitHub Pages and a custom domain.

## 1) Push repository to GitHub

- [ ] Ensure this repository is pushed to GitHub.
- [ ] Confirm your default branch is correct (`main` or `master`).

## 2) Configure GitHub Pages

- [ ] Open repository **Settings → Pages**.
- [ ] Under source, deploy from the default branch.
- [ ] Select folder: **`/ (root)`**.

## 3) Configure DNS records at your domain provider

For apex/root (`@`):

- [ ] `A @ → 185.199.108.153`
- [ ] `A @ → 185.199.109.153`
- [ ] `A @ → 185.199.110.153`
- [ ] `A @ → 185.199.111.153`

For `www`:

- [ ] `CNAME www → wantedpebkkk.github.io`

## 4) Configure custom domain in GitHub Pages

- [ ] In GitHub Pages custom domain, set: **`reignedweb.com`**
- [ ] Confirm the repository `CNAME` file contains `reignedweb.com` (already set).

## 5) Enable HTTPS

- [ ] Wait for DNS propagation.
- [ ] Enable **Enforce HTTPS** in GitHub Pages once available.

## 6) Verify URLs

- [ ] Temporary URL works: `https://wantedpebkkk.github.io/Reigned-Web/`
- [ ] Apex domain works: `https://reignedweb.com`
- [ ] WWW domain works: `https://www.reignedweb.com`
