# Bhuvaneswari Kolluru — Portfolio

A responsive, editorial-style portfolio website built with HTML5, CSS3, and vanilla JavaScript. The layout uses a light paper background, numbered sections, generous spacing, and typography-led presentation.

## Run locally in VS Code

1. Open this folder in VS Code.
2. Add the **Live Server** extension, or open `index.html` directly in a browser.
3. Live Server is recommended for the best local file experience.

No build step, package installation, or API key is required.

## Personal assets

The portfolio uses the real files already stored in the `assets` folders.

### Profile photograph

Current profile photograph:

`assets/profile/my-photo.jpg`

### Resume

`assets/documents/resume.pdf`

The **View resume**, **Download resume**, and hero download buttons point to this path.

### Certificates

Certificate images are shown in fixed, proportional thumbnail containers. PDF files use clearly labeled decorative certificate-themed cover artwork and open the complete original PDF in a new browser tab through the **View Certificate** link. The artwork is only a visual cover and is not presented as the credential itself.

- `assets/certificates/AIskills-passport.jpeg`
- `assets/certificates/Frontend developer internship.jpeg`
- `assets/certificates/core python.jpeg`
- `assets/certificates/KR4ALL_Internship_Certificate_Kolluru_Bhuvaneswari.pdf`
- `assets/certificates/K. BHUVANESWARI - 23BJ1A0570.pdf`
- `assets/certificates/NOC26CS70S25080225304612222 (1).pdf`
- `assets/certificates/Wadhwani Foundation Certificate - 6902f714340b394e18f0853d.pdf`
- `assets/certificates/Bhuvaneswari Kolluru_Certificate.pdf`

## Customize

- Update colors and typography in the `:root` section of `style.css`.
- Update verified content and links in `index.html`.
- Update certificate filenames through the matching certificate card links.
- JavaScript interactions in `script.js` provide mobile navigation, active-section navigation, and reveal-on-scroll behavior.
- The contact section includes a `mailto:` Email Me link for `kollurubhuavana@gmail.com`.

## Publish with GitHub Pages

1. Create a GitHub repository, for example `portfolio-website`.
2. Upload `index.html`, `style.css`, `script.js`, `README.md`, and the complete `assets` folder.
3. Open the repository’s **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the branch containing the website and the `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the provided URL.

Keep the asset paths and filename capitalization unchanged when publishing, because GitHub Pages uses case-sensitive paths.
