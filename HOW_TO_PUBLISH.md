# How to Publish Your Website on GitHub Pages

Since **Git** is not currently installed on this computer, the easiest ways to publish your site are using the **GitHub Website** directly or **GitHub Desktop**.

## Method 1: The "Drag & Drop" Way (Easiest)

1.  **Create an Account**: Go to [github.com](https://github.com) and sign up/login.
2.  **New Repository**:
    *   Click the **+** icon in the top-right corner -> **New repository**.
    *   Repository name: `milanpathak.github.io` (Recommended! This makes your URL clean: `https://milanpathak.github.io`).
    *   Make sure it is **Public**.
    *   Click **Create repository**.
3.  **Upload Files**:
    *   On the next screen, click the link that says **"uploading an existing file"**.
    *   Open your folder `z:\Personal_Website` in Windows Explorer.
    *   Select **ALL** files (Ctrl+A).
    *   Drag and drop them into the GitHub page.
    *   Wait for them to upload.
    *   In the "Commit changes" box at the bottom, type "Initial release" and click **Commit changes**.
4.  **Activate Pages**:
    *   Go to **Settings** (tab at the top of your repo).
    *   On the left sidebar, click **Pages**.
    *   Under **Build and deployment** > **Branch**, select `main` (or `master`) and folder `/(root)`.
    *   Click **Save**.
5.  **Done!**: Wait 1-2 minutes. Your site will be live at `https://milanpathak.github.io` (or `https://yourusername.github.io/reponame`).

---

## Method 2: GitHub Desktop (Recommended for Updates)

If you plan to make changes often, this is better.

1.  Download and install **[GitHub Desktop](https://desktop.github.com/)**.
2.  Login with your GitHub account.
3.  Go to **File** > **New Repository**.
    *   Name: `milanpathak.github.io`
    *   Local Path: Choose a folder on your computer (e.g., `Documents`).
4.  **Copy Files**:
    *   Copy all files from your current workspace `z:\Personal_Website` into that new folder you just created.
5.  **Publish**:
    *   GitHub Desktop will see the new files.
    *   Type a summary (e.g., "Initial site") and click **Commit to main**.
    *   Click **Publish repository** in the top bar.
6.  **Enable Pages**:
    *   Go to the repository on GitHub.com -> **Settings** -> **Pages** -> Enable from `main`.

---

## Checklist for Success
- [ ] Ensure `index.html` is in the root (not in a subfolder).
- [ ] Ensure your image filenames match your specific code (e.g., `Photo_Thesis.png` vs `photo_thesis.png`). Case sensitivity matters on GitHub (Linux) but not on Windows!
- [ ] **Important**: Verify your image extensions. If your code says `.jpg` but the file is `.JPG`, fix it in the code.
