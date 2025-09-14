# App Documentation - GitHub Pages

This repository hosts the GitHub Pages website for various mobile apps, providing support documentation, privacy policies, and marketing information.

## Files

- `index.html` - Main marketing landing page
- `support.html` - Support page with FAQ and troubleshooting
- `privacy.html` - Privacy policy page
- `_config.yml` - Jekyll configuration for GitHub Pages

## Setup Instructions for app_docs Repository

### 1. Initialize and Push to GitHub

```bash
# Navigate to app_docs directory
cd ../app_docs

# Initialize git repository
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit: App documentation site"

# Connect to remote repository
git remote add origin https://github.com/shenshutao/app_docs.git

# Push to GitHub
git push -u origin main
```

### 2. Enable GitHub Pages

1. Go to https://github.com/shenshutao/app_docs
2. Click **Settings** tab
3. Scroll to **Pages** section
4. Set Source to **Deploy from a branch**
5. Select branch: **main** and folder: **/ (root)**
6. Click **Save**

### 3. App Store Connect URLs

After GitHub Pages is enabled, use these URLs:

- **Marketing URL:** `https://shenshutao.github.io/app_docs/`
- **Support URL:** `https://shenshutao.github.io/app_docs/support.html`
- **Privacy Policy URL:** `https://shenshutao.github.io/app_docs/privacy.html`

### 4. Customization

Update the following in your files:

- Replace `support@example.com` with your actual support email in:
  - `support.html`
  - `privacy.html`
- Replace `privacy@example.com` with your privacy contact email in `privacy.html`
- Update contact information in `index.html`

## Repository Structure

```
app_docs/
├── index.html          # Marketing landing page
├── support.html        # Support and FAQ page
├── privacy.html        # Privacy policy page
├── _config.yml         # Jekyll configuration
└── README.md          # This file
```

## Apps Supported

- **QR Scanner** - Fast QR & barcode scanner with EMVCo payment support

## Local Development

To test locally:

```bash
# Install Jekyll (if not installed)
gem install bundler jekyll

# Serve the site
jekyll serve

# Visit http://localhost:4000/app_docs/
```

## Adding New Apps

To add support for additional apps:

1. Create new HTML files for each app (e.g., `app2-support.html`)
2. Update navigation in existing files
3. Add new app information to `_config.yml`
4. Create app-specific directories if needed

## Features Included

- ✅ Responsive design for mobile and desktop
- ✅ Professional marketing page
- ✅ Comprehensive FAQ and support
- ✅ GDPR-compliant privacy policy
- ✅ App Store Connect ready
- ✅ SEO optimized
- ✅ Fast loading with minimal dependencies