# Email Form Setup Guide

This landing page uses [Formspree](https://formspree.io/) for the email signup form, which is perfect for static GitHub Pages sites.

## Steps to Configure the Email Form

### Option 1: Using Formspree (Recommended - Free for up to 50 submissions/month)

1. Go to [https://formspree.io/](https://formspree.io/)
2. Sign up for a free account
3. Create a new form
4. Copy your form's endpoint URL (it will look like `https://formspree.io/f/YOUR_FORM_ID`)
5. In `index.html`, replace `YOUR_FORM_ID` in this line:
   ```html
   <form class="signup-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
6. Commit and push the change to GitHub
7. Your form is now live! Submissions will be sent to the email associated with your Formspree account

### Option 2: Using Other Static Form Services

Alternative services that work with GitHub Pages:

- **Netlify Forms**: If you host on Netlify instead of GitHub Pages
- **Google Forms**: Embed a Google Form (requires iframe)
- **EmailJS**: Client-side email service
- **Basin**: Simple form backend service

## Testing the Form

1. After deploying to GitHub Pages, visit your landing page
2. Fill out the form with test data
3. Submit the form
4. Check your email (or Formspree dashboard) for the submission

## Customization

You can customize the form fields in `index.html`. The current setup includes:
- Name field (text input)
- Email field (email input)

To add more fields, add additional form groups in the signup form section.
