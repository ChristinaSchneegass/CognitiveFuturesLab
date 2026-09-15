Cognitive Futures Lab — website

A lightweight, responsive multi-page website designed for GitHub Pages. It uses plain HTML, CSS, and JavaScript, so there is no build process or package installation.

Publish on GitHub Pages

Copy all .html files and the assets folder into the root of your GitHub Pages repository.

Replace your current index.html when you are ready.

Commit and push the changes.

In the repository, open Settings → Pages and make sure the site is deployed from the correct branch and root folder.

Before publishing

Search the project for YOUR. and replace the placeholder email address in index.html.

Review these pieces of provisional copy:

Partner naming and order

Research direction descriptions

Collaboration description

Contact text

Copyright/lab ownership

The newsletter is intentionally shown as “coming soon”; there is no fake or inactive signup form. It can later be connected to Buttondown, Mailchimp, Brevo, or another GDPR-compatible mailing service.

Structure

index.html
research.html
people.html
notes.html
about.html
connect.html
privacy.html
assets/
  css/styles.css
  icons/favicon.svg
  js/main.js

Customization

The main identity colors are at the top of assets/css/styles.css:

--white: #ffffff;
--ink: #111a2c;
--signal: #18b8c4;
--pulse: #d9f45b;

The page loads Source Serif 4, IBM Plex Sans, and IBM Plex Mono from Google Fonts. If institutional privacy policy prevents externally hosted fonts, download and self-host them or replace the font variables with approved typefaces.
