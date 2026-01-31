# Beyond the Numbers - Book Landing Page

A professional landing page for the book "Beyond the Numbers: Three Buckets of Money"

## About the Book

This is a book about finance that introduces the revolutionary Three Buckets approach to managing your money:
- 🪣 **Bucket 1: Safety & Security** - Your foundation for financial peace of mind
- 🪣 **Bucket 2: Growth & Investment** - Building wealth for your future
- 🪣 **Bucket 3: Dreams & Lifestyle** - Living your best life today

## Features

- ✅ Professional landing page design
- ✅ Forest green book cover image
- ✅ Email signup form for building a mailing list
- ✅ Responsive design (mobile-friendly)
- ✅ GitHub Pages compatible

## Setup

1. **Deploy to GitHub Pages:**
   - Go to your repository Settings → Pages
   - Set Source to "Deploy from a branch"
   - Select the branch you want to deploy (usually `main` or `copilot/add-landing-page-for-book`)
   - Click Save
   - Your site will be available at: `https://[username].github.io/demolandingpageformybook/`

2. **Configure Email Form:**
   - See [SETUP.md](SETUP.md) for detailed instructions on setting up the Formspree email form
   - You'll need to replace `YOUR_FORM_ID` in `index.html` with your actual Formspree form ID

## Files

- `index.html` - Main landing page
- `book-cover.svg` - Forest green book cover image
- `SETUP.md` - Email form setup instructions

## Local Development

To preview the site locally:

```bash
python3 -m http.server 8080
```

Then open your browser to `http://localhost:8080`

## Customization

Feel free to customize:
- Book description and content in `index.html`
- Color scheme in the CSS section
- Book cover design in `book-cover.svg`
- Form fields for the email signup
