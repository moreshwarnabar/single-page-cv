# Cloud Resume Challenge – HTML Resume

This repository contains the code for Moreshwar Rajan Nabar's cloud-ready résumé, built as part of the Cloud Resume Challenge. The site is a single-page static application composed of `index.html` and `index.css`, showcasing professional experience, education, and projects in a modern, responsive layout.

## Project Structure

- `index.html`: Main markup for the résumé page.
- `index.css`: Styling for the résumé layout, typography, and responsive behavior.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-account>/cloud-resume-challenge.git
   cd cloud-resume-challenge
   ```
2. Serve the site locally (pick one):
   - Double-click `index.html` to open it in your browser, **or**
   - Use a lightweight web server for a closer-to-production experience:
     ```bash
     python3 -m http.server 8080
     ```
     Then visit `http://localhost:8080` in your browser.

## Customization Tips

- Update contact information, experience, education, and skills directly in `index.html`.
- Adjust colors, fonts, and layout in `index.css`. The site currently uses Google Fonts and Font Awesome for typography and icons.
- Add analytics, serverless counter endpoints, or certification badges as you expand the Cloud Resume Challenge requirements.

## Deployment

Because the project is a plain static site, you can deploy it to any static hosting platform (e.g., AWS S3 + CloudFront, GitHub Pages, Netlify, Vercel, or Azure Static Web Apps). Most providers simply require uploading the contents of this repository and configuring the host to serve `index.html` as the root document.

## Next Steps

- Automate deployments with CI/CD (GitHub Actions, AWS CodePipeline, etc.).
- Integrate a cloud-based visitor counter backed by a serverless function and database.
- Add end-to-end tests or visual regression checks to maintain layout quality over time.

## License

This project is available under the MIT License. See the `LICENSE` file (add one if needed) for details.
