# Image to PDF Converter

A clean one-page web tool to convert a JPG or PNG image into a downloadable PDF in seconds.

## Features

- Drag and drop or click-to-upload image input
- Image preview before conversion
- PDF generation with portrait A4 layout
- Proportional image scaling and centered placement
- Loading indicator and user-friendly status messages
- Responsive design for desktop and mobile

## Tech Stack

- HTML
- CSS
- JavaScript
- [jsPDF](https://cdnjs.com/libraries/jspdf) via CDN

## Run Locally

1. Clone this repository.
2. Open `index.html` in your browser.

No build step or dependencies required.

## Deploy to GitHub Pages

This repo includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml` that deploys the site automatically.

1. Push to the `main` branch.
2. In GitHub, go to `Settings` -> `Pages`.
3. Under **Build and deployment**, choose **Source: GitHub Actions**.
4. The workflow will publish your site after each push to `main`.

## Project Structure

```text
.
├── .github/workflows/deploy-pages.yml
├── .gitignore
├── index.html
├── LICENSE
└── README.md
```

## License

Released under the MIT License. See [LICENSE](LICENSE).

