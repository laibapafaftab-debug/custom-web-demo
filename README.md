# AuraNova Digital

Modern one-page website for **AuraNova Digital**, a studio offering custom website development and AI workflow automation.

🔗 **Live site:** https://laibapafaftab-debug.github.io/auranova-digital/

## Features

- Responsive, dark-themed design (mobile, tablet, desktop)
- Sections: Hero, About, Services, Process, Work, Reviews, Pricing, Contact
- Contact form powered by [FormSubmit](https://formsubmit.co/) (no backend needed)
- Redirects back to the site with a success message after submitting
- Honeypot field for basic spam protection

## Tech Stack

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) (CDN)
- [Font Awesome](https://fontawesome.com/) icons
- Google Fonts (Plus Jakarta Sans)
- Vanilla JavaScript
- Hosted on GitHub Pages

## Project Structure

```
auranova-digital/
├── index.html      # Main website file
├── hero-logo.jpg   # Hero image (add your logo here)
├── favicon.svg     # Site icon (optional)
└── README.md
```

## Contact Form Setup

The form in `index.html` uses FormSubmit:

```html
<form action="https://formsubmit.co/auranova597@gmail.com" method="POST">
  <input type="hidden" name="_next" value="https://laibapafaftab-debug.github.io/auranova-digital/?sent=true#contact">
  ...
</form>
```

1. Set your email in the form `action`.
2. Submit the form once. FormSubmit sends an **activation email** to that address.
3. Click **Activate Form** in that email (check Spam too).
4. After this, all inquiries arrive in your inbox.

`_next` sends visitors back to the site after submitting, where a success message is shown.

## Run Locally

Just open `index.html` in your browser. No build step is needed.

## Deploy on GitHub Pages

1. Push the files to your repository.
2. Go to **Settings → Pages**.
3. Under **Source**, choose the `main` branch and `/ (root)`.
4. Save. The site goes live in 1 to 2 minutes.

## Customization

- **Reviews:** replace the sample reviews with real client feedback before launch.
- **Pricing and services:** edit the text directly in `index.html`.
- **Portfolio:** update the project cards in the `#portfolio` section.

## Contact

- Email: auranova597@gmail.com

© 2026 AuraNova Digital. All rights reserved.
