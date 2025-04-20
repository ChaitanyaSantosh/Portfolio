# Chaitanya Santosh Portfolio

This repository hosts a GitHub Pages website showcasing Chaitanya Santosh Madadala's portfolio in a hacker-themed terminal interface. The site features a large greeting, interactive terminal, clickable menu, and Matrix-style background animation.

## Features

- **Greeting**: A bold "Hi, Welcome to Chaitanya Santosh Portfolio" displayed above the terminal.
- **Terminal Interface**: Interactive terminal with green-on-black aesthetic (or blue-on-white with theme toggle), supporting commands like `summary`, `experience`, `education`, `skills`, `projects`, `certifications`, `contact`, `help`, and `clear`.
- **Clickable Menu**: Clicking a menu item clears the terminal and displays only the respective section's content, centered vertically.
- **Matrix Rain Effect**: Animated background with falling green (or blue in light theme) characters.
- **Theme Toggle**: Switch between dark (green-on-black) and light (blue-on-white) themes via a menu item.
- **Command History**: Use up/down arrow keys to navigate previous terminal commands.
- **Smooth Scroll Animation**: Terminal output fades in for a polished visual effect.
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

3. **Test Locally** (Critical):

   - Open `index.html` in a web browser (e.g., double-click or drag into Chrome).
   - Verify that you see:
     - The large greeting ("Hi, Welcome to Chaitanya Santosh Portfolio").
     - The green-on-black terminal with a clickable menu.
     - The Matrix rain effect in the background.
     - Clicking a menu item (e.g., "Summary") clears the terminal and shows only that section's content, centered.
     - Typing commands (e.g., `summary`, `help`) appends content.
     - Toggling the theme switches to blue-on-white and back.
     - Up/down arrow keys navigate command history.
     - Output fades in smoothly.
   - If you see plain text, check the browser console (F12 > Console) for errors.

4. **Push to GitHub**:

   - Initialize a Git repository locally:

     ```bash
     git init
     git add index.html README.md
     git commit -m "Initial commit with updated portfolio website"
     ```

   - Link to a remote GitHub repository:

     ```bash
     git remote add origin https://github.com/<your-username>/<your-repo-name>.git
     git branch -M main
     git push -u origin main
     ```

   - Alternatively, upload files manually:

     - Go to your repository on GitHub.
     - Click **Add file** > **Upload files**.
     - Drag and drop `index.html` and `README.md`, then commit to the `main` branch.
     - Ensure the file is named exactly `index.html` (not `index.html.txt` or `Index.html`).

5. **Enable GitHub Pages**:

   - Go to your repository on GitHub.
   - Navigate to **Settings** > **Pages**.
   - Under **Branch**, select the `main` branch and `/ (root)` folder.
   - Click **Save**.
   - Wait 1-5 minutes for deployment. Check the **Pages** section for the URL (e.g., `https://<your-username>.github.io/<your-repo-name>/`).

6. **Access the Site**:

   - Visit the provided GitHub Pages URL.
   - If you see a 404 error or plain text, see the **Troubleshooting** section below.

## Usage

- **Menu Navigation**: Click menu items (Summary, Experience, etc.) to clear the terminal and display only the selected section's content, centered vertically.
- **Terminal Commands**: Type commands like `help`, `summary`, or `clear` to append content.
- **Theme Toggle**: Click "Toggle Theme" to switch between dark and light themes.
- **Command History**: Use up/down arrow keys to cycle through previous commands.
- **Responsive**: Test on mobile devices to ensure the layout adjusts correctly.

## Troubleshooting

### 404 Error

If you see a "404 - File or directory not found" error:

1. **Verify GitHub Pages Setup**:

   - Go to **Settings** > **Pages** in your repository.
   - Ensure the **Source** is set to `main` branch and `/ (root)` folder.
   - Check the provided URL in the **Pages** section (e.g., `https://<your-username>.github.io/<your-repo-name>/`).

2. **Check File Placement**:

   - In your repository, confirm that `index.html` is in the root directory of the `main` branch (not in a subfolder).
   - Ensure the file name is exactly `index.html` (lowercase, no extra extensions like `.txt`).

3. **Confirm Repository Name**:

   - If your repository is named `<your-repo-name>`, the URL should be `https://<your-username>.github.io/<your-repo-name>/`.
   - For a user/organization site (e.g., `<your-username>.github.io`), the repository must be named exactly `<your-username>.github.io`.

4. **Check Deployment Status**:

   - Go to the **Actions** tab in your repository.
   - Look for a "pages build and deployment" workflow. If it failed, view the error details and re-run the workflow.
   - Wait 1-5 minutes after pushing changes, as deployment can take time.

5. **Re-upload Files**:

   - Delete `index.html` from the repository.
   - Re-upload `index.html` from the provided ZIP or via Git, ensuring the correct file name and content.
   - Commit and wait for redeployment.

6. **Clear Browser Cache**:

   - Open the URL in an incognito window or clear your browser cache (Ctrl+Shift+Delete in Chrome).

### Plain Text Issue

If the site loads but displays only plain text instead of the designed webpage:

1. **Verify File Content**:

   - In your repository, click `index.html` to view its raw content.
   - Ensure it contains the full HTML, including `<style>` and `<script>` sections, matching the provided file.
   - If corrupted, delete and re-upload `index.html`.

2. **Check File Name**:

   - Ensure the file is named exactly `index.html` (not `index.html.txt` or `Index.html`).
   - In the repository, rename the file if necessary via the web interface.

3. **Test Locally**:

   - Download `index.html` from your repository.
   - Open it in a browser (e.g., Chrome).
   - If the design appears locally, the issue is with GitHub Pages serving the file.
   - If plain text appears locally, check the browser console (F12 > Console) for errors.

4. **Inspect MIME Type**:

   - Open the site in a browser and press F12 > **Network** tab.
   - Reload the page and check the response for `index.html`.
   - Ensure the `Content-Type` is `text/html`. If it’s `text/plain`, the file was uploaded incorrectly.
   - Fix by re-uploading `index.html` with the correct `.html` extension.

5. **Browser Console Errors**:

   - Press F12 > **Console** and look for JavaScript or CSS errors.
   - Ensure JavaScript is enabled and the browser supports `<canvas>` (all modern browsers do).

6. **Re-deploy**:

   - Create a new repository and repeat the deployment steps to rule out repository-specific issues.
   - Use the provided ZIP file to ensure clean files.

## Contributing

Feel free to fork this repository and submit pull requests for improvements.

## License

This project is unlicensed and free to use.