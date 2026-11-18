# Tejas Patil | AWS DevOps Engineer Portfolio

Static portfolio (HTML, CSS, JavaScript). No build step.

## Sections
Home, About, Technical Skills, Professional Experience, Featured Projects, Architecture Showcase, Resume, Contact, Footer.

## Run locally
Open `index.html` in a browser, or serve the folder:
```bash
python -m http.server 8000
```

## Update content
- Text and sections: `index.html`
- Styles and theme colors: `assets/newcss.css` (`--hue-color` controls the accent)
- Behavior: `assets/ptj.js`
- Resume: replace `assets/Tejas_Patil_AWS_DevOps_Resume.pdf` (keep the file name)

## Contact form
By default the form opens the visitor's mail app (`mailto:`). To send through EmailJS, fill in
`assets/config.js` (`serviceId`, `templateId`, `publicKey`). EmailJS public keys are designed for browser
use; never add a private key. Set the recipient in your EmailJS template.

## Deploy
Upload the folder to GitHub Pages, Netlify, Vercel or S3/CloudFront.
