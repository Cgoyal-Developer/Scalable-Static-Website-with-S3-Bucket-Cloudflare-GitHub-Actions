# Scalable-Static-Website-with-S3-Bucket-Cloudflare-GitHub-Actions
A scalable static website hosted on AWS S3, delivered globally via Cloudflare CDN + HTTPS, and automatically deployed using GitHub Actions CI/CD.
# 🌐 Scalable Static Website with AWS S3 + Cloudflare + GitHub Actions

This project demonstrates how to deploy a static website using **AWS S3 (Free Tier)** for storage, **Cloudflare** for HTTPS and CDN, and **GitHub Actions** for automatic deployments. It ensures fast, secure, and globally available website delivery with every code push.

---

## 🧰 Tools & Services Used

- **AWS S3** – Static website hosting
- **Cloudflare** – DNS, CDN, and SSL/HTTPS
- **GitHub** – Version control and source hosting
- **GitHub Actions** – CI/CD automation
- **HTML/CSS** – Static website content
- **Bash** – Used inside GitHub Actions for S3 syncing

---

## 🚀 Deployment Steps

### 1. Static Site Setup
Create a basic HTML/CSS static site and organize it in a GitHub repository.

### 2. GitHub Repository
Push the static site code to a new or existing GitHub repository.

### 3. GitHub Actions Deployment
Set up GitHub Actions to deploy the site automatically to an S3 bucket when changes are pushed to the main branch.

### 4. AWS S3 Configuration
Create an S3 bucket and enable static website hosting. Set your index document and ensure the bucket is publicly readable via permissions.

### 5. Cloudflare Integration
Connect your domain to Cloudflare, point it to the S3 static hosting endpoint, enable HTTPS, caching, and performance options.

---

## 🌐 Cloudflare + S3 Integration

- Add your domain to Cloudflare and update nameservers at your registrar.
- Create a CNAME or A record pointing to the S3 static site endpoint.
- Enable SSL in Cloudflare for secure HTTPS delivery.
- Configure page rules or caching options for optimized performance.

---

## 🧪 Optional: Versioning & Caching

- Enable S3 versioning to keep historical copies of deployed files.
- Set cache control policies in S3 or configure them in Cloudflare’s dashboard.

---

## ✅ Deliverables

- ✔️ GitHub Actions CI/CD Workflow
- ✔️ AWS S3 + Cloudflare Setup Guide
- ✔️ HTTPS Enabled with Cloudflare
- ✔️ Live Website with CDN Delivery
- ✔️ Deployment Report & Screenshots

---

## 🖼️ Screenshots

| Step                        | Screenshot File Name              |
|----------------------------|------------------------------------|
| Static Website Live        | `live-site-screenshot.png`        |
| GitHub Actions Workflow    | `github-actions-screenshot.png`   |
| AWS S3 Bucket Configuration| `s3-config-screenshot.png`        |
| Cloudflare DNS Settings    | `cloudflare-dns-screenshot.png`   |
| SSL/HTTPS Verification     | `https-padlock-screenshot.png`    |

All screenshots are stored in the `/screenshots/` folder in this repository.

---

## 🌍 Live Demo

Website: [https://your-domain.com](https://your-domain.com)  
> Replace with your real domain after deployment.

---

## 📊 Deployment Report

- GitHub code pushed to `main` branch
- GitHub Actions triggered and synced site to S3
- Cloudflare connected successfully
- SSL is enabled and verified
- Site is globally distributed and cached via CDN

---

## 🔐 Notes

- All secrets (like AWS keys) are securely stored in GitHub repository secrets.
- Do not hardcode credentials in your repository.
- Use `.gitignore` to exclude any build artifacts or sensitive data.

---

## 📄 License

MIT License

---

> Author: [Your Name]  
> GitHub: [github.com/yourusername](https://github.com/yourusername)
