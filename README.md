# AI Product Manager - Landing Page

A clean, minimal landing page for Jatin Rajvanshi's AI Product Management mentoring services.

## Quick Start

1. Open `index.html` in your browser to preview the site
2. The page is fully responsive and works on all devices

## What's Included

- **Hero Section**: Eye-catching introduction with call-to-action
- **About Section**: Your background and journey
- **Services Section**: 6 service cards showcasing what you offer
- **Contact Form**: Collects name, email, profession, and message
- **Success State**: Shows your email after form submission

## Current State

The form currently:
- ✅ Collects all required information
- ✅ Shows success message with your email
- ✅ Logs form data to browser console
- ❌ Does NOT send emails yet (needs backend integration)

## Next Steps for Backend Integration

Choose one of these options:

### Option 1: Formspree (Easiest)
1. Go to [formspree.io](https://formspree.io) and create a free account
2. Get your form endpoint URL
3. Replace the form's `onsubmit` handler with Formspree action
4. You'll receive email notifications automatically

### Option 2: EmailJS
1. Sign up at [emailjs.com](https://www.emailjs.com/)
2. Create an email service and template
3. Add EmailJS SDK to the HTML
4. Update the submit handler to use EmailJS API

### Option 3: Custom Backend
Build a simple Node.js/Express server to handle form submissions and send emails.

## Deployment

To deploy to your domain (aiproductmanager.ca):
- Use services like Netlify, Vercel, or GitHub Pages (all free)
- Or upload to your hosting provider

## Customization

- **Colors**: Change `#00D9FF` (cyan accent) to your preferred color
- **Email**: Update `jatin@aiproductmanager.ca` in the HTML
- **Content**: Edit any text directly in the HTML file

## Files

- `index.html` - Complete landing page (HTML + CSS + JS in one file)
- `README.md` - This file

---

Built with vanilla HTML, CSS, and JavaScript. No dependencies required.
