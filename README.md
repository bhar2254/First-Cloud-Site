# 🌐 Cloudflare Pages + GitHub Deployment Guide

This project is a simple, responsive Bootstrap 5 static site using a Viridis color scheme. It serves as a tutorial for deploying static sites on **Cloudflare Pages** with **automatic GitHub deployments**.

## 📦 What's Inside?

- Bootstrap 5 layout
- Viridis color palette for a vibrant, scientific aesthetic
- Step-by-step deployment instructions
- GitHub → Cloudflare Pages integration walkthrough

---

## 🚀 Quick Start

### 1. Fork This Repository

Click the **"Fork"** button at the top right of this page to copy this repository into your GitHub account.

### 2. Customize (Optional)

Modify any HTML/CSS in your fork if you want to personalize the guide or design.

---

## 🛠 Deploy to Cloudflare Pages

1. **Log in to [Cloudflare Pages](https://pages.cloudflare.com)** with your Cloudflare account.
2. Click **"Create a Project"**.
3. Connect your GitHub account and authorize access.
4. Select your forked repository from the list.
5. Configure the build:
    - **Framework preset**: `None` (or your choice)
    - **Build command**: Leave empty for static HTML
    - **Output directory**: Leave empty or set to `/` (or your build folder if applicable)
6. Click **"Save and Deploy"**.

After deployment, your site will be live at a `your-project.pages.dev` URL. 🎉

---

## 🔄 Automatic Deployments

Every time you push changes to your GitHub repository (on the branch you configured), Cloudflare Pages will automatically rebuild and redeploy your site.

---

## 📄 Live Demo

> You can see the example live at:  
> 🔗 [first-cloud-site.blaineharper.com](https://first-cloud-site.blaineharper.com) *(replace with your real URL)*

---

## 📚 Resources

- [Cloudflare Pages Documentation](https://developers.cloudflare.com/pages)
- [Bootstrap 5 Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- [Viridis Color Maps](https://bids.github.io/colormap/)

---

## 📝 License

This project is licensed under the GPL-3.0 license.
