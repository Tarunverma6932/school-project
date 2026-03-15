# School Project (ABC Public School Noida)

This repository contains a static HTML/CSS/JS website designed for a school portal (ABC Public School Noida). It includes public-facing pages and a simple ERP-style login/signup workflow.

## 🗂️ Project Structure

- `zenith_public_school_home/` – Home page with hero section, slider, and site navigation
- `zenith_public_school_houses/` – House system page
- `zenith_public_school_clubs/` – Clubs page
- `zenith_public_school_downloads/` – Resources/Downloads page
- `zenith_public_school_erp_portal/` – Core ERP portal layout
- `zenith_erp_login_*` – Three login variants (login forms + links)
- `zenith_erp_sign_up_*` – Sign-up flow pages
- `zenith_erp_set_new_password/` – Reset password page
- `zenith_erp_sign_up_success/` – Signup success confirmation page

> Note: The folder names pre-date the branding change; the site is now branded as **ABC Public School Noida**.

## 🚀 Running Locally

To run the site locally, start a simple HTTP server from the repository root:

```bash
cd /Users/tarunverma/Downloads/stitch
python3 -m http.server 8000
```

Then open your browser at:

```
http://localhost:8000/zenith_public_school_home/code.html
```

## 🛠️ Customizing the Site

### Change the homepage slider images
Update the `background-image` URL values inside the slider `<div class="slide">` elements in:

- `zenith_public_school_home/code.html`

### Change text/site name
Update the content in the HTML files where the school name appears.

## ✅ GitHub
This repo is ready for GitHub. Just add a remote and push:

```bash
git remote add origin https://github.com/<your-username>/school-project.git
git push -u origin main
```

---

If you want, I can also add a small CSS file and move shared styles out of the HTML (cleaner structure).