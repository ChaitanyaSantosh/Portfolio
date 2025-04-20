# Chaitanya Santosh Portfolio

This repository hosts a GitHub Pages website showcasing Chaitanya Santosh Madadala's portfolio in a hacker-themed terminal interface. The site features a large greeting, interactive terminal, clickable menu, and Matrix-style background animation.

## Features

- **Greeting**: A bold "Hi, Welcome to Chaitanya Santosh Portfolio" displayed above the terminal.
- **Terminal Interface**: Interactive terminal with green-on-black aesthetic, supporting commands like `summary`, `experience`, `education`, `skills`, `projects`, `certifications`, `contact`, `help`, and `clear`.
- **Clickable Menu**: Navigate sections by clicking menu items.
- **Matrix Rain Effect**: Animated background with falling green characters.
- **Responsive Design**: Adapts to mobile and desktop screens.

## Setup and Deployment

### Prerequisites

- A GitHub account.
- Git installed locally (optional for manual upload).
- A modern web browser (Chrome, Firefox, Edge, etc.).

### Steps to Deploy

1. **Clone or Download the Repository**:

   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```

   Or download the repository as a ZIP and extract it.

2. **Ensure Files**:

   - The repository should contain:
     - `index.html`: The main webpage.
     - `README.md`: This file.

3. **Test Locally** (Recommended):

   - Open `index.html` in a web browser (e.g., double-click the file or drag it into Chrome).
   - Verify that the design (greeting, terminal, Matrix rain) appears correctly.
   - If you see only plain text, check the browser console (F12 &gt; Console) for errors.

4. **Push to GitHub**:

   - Initialize a Git repository locally:

     ```bash
     git init
     git add index.html README.md
     git commit -m "Initial commit with portfolio website"
     ```

   - Link to a remote GitHub repository:

     ```bash
     git remote add origin https://github.com/<your-username>/<your-repo-name>.git
     git branch -M main
     git push -u origin main
     ```

   - Alternatively, upload files manually:

     - Go to your repository on GitHub.
     - Click **Add file** &gt; **Upload files**.
     - Drag and drop `index.html` and `README.md`, then commit to the `main` branch.

5. **Enable GitHub Pages**:

   - Go to your repository on GitHub.
   - Navigate to **Settings** &gt; **Pages**.
   - Under **Branch**, select the `main` branch and `/ (root)` folder.
   - Click **Save**.
   - Wait 1-5 minutes for deployment. Check the **Pages** section for the URL (e.g., `https://<your-username>.github.io/<your-repo-name>/`).

6. **Access the Site**:

   - Visit the provided GitHub Pages URL.
   - If the design doesn't appear, see the **Troubleshooting** section below.

## Usage

- **Menu Navigation**: Click menu items (Summary, Experience, etc.) to view sections.
- **Terminal Commands**: Type commands like `help`, `summary`, or `clear` in the terminal input.
- **Responsive**: Test on mobile devices to ensure the layout adjusts correctly.

## Troubleshooting

If you see only plain text instead of the designed webpage:

1. **Check GitHub Pages URL**:

   - Ensure you're visiting the correct URL (e.g., `https://<your-username>.github.io/<your-repo-name>/`).
   - Verify that GitHub Pages is enabled for the `main` branch and `/ (root)` folder in **Settings** &gt; **Pages**.

2. **Test Locally**:

   - Download `index.html` from your repository.
   - Open it in a browser (e.g., Chrome).
   - If the design appears locally but not on GitHub Pages, the issue is likely with the deployment.

3. **Inspect Browser Console**:

   - Open the GitHub Pages site in a browser.
   - Press F12 and go to the **Console** tab.
   - Look for errors (e.g., "Failed to load resource" or JavaScript errors).
   - Common issues:
     - **MIME Type Error**: GitHub Pages may serve `index.html` as `text/plain`. Ensure the file is uploaded correctly and has no extra extensions (e.g., `index.html.txt`).
     - **JavaScript Errors**: Ensure the browser supports `<canvas>` (all modern browsers do).

4. **Verify File Integrity**:

   - Download `index.html` from your repository.
   - Check that it matches the provided file (e.g., contains `<style>` and `<script>` sections).
   - Ensure the file is saved with UTF-8 encoding and no extra characters.

5. **Clear Browser Cache**:

   - Clear your browser's cache or open the site in an incognito window to rule out caching issues.

6. **Re-upload Files**:

   - Delete `index.html` from the repository.
   - Re-upload the file from the provided ZIP or copy-paste the content into a new `index.html` via GitHub's web interface.
   - Commit and wait for GitHub Pages to redeploy.

7. **Check Deployment Status**:

   - Go to your repository's **Actions** tab.
   - Look for a "pages build and deployment" workflow. If it failed, check the error details.
   - Re-run the workflow if necessary.

8. **Contact Support**:

   - If the issue persists, share the repository URL and browser console errors with me or GitHub Support.

## Contributing

Feel free to fork this repository and submit pull requests for improvements.

## License

This project is unlicensed and free to use.