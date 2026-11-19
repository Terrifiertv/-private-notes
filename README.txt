PRIVATE NOTES — IPHONE PWA

This is a free, local-only notes app. Notes are encrypted with AES-GCM in your browser's IndexedDB. A key is derived from your password using PBKDF2-SHA-256.

IMPORTANT:
- Your notes stay in this browser on this iPhone. They do not sync to other devices.
- If you forget your password, there is no password reset and the notes cannot be decrypted.
- Clearing Safari website data can erase your vault. Keep a separate secure backup if the notes matter.
- This is a starter project, not a professionally audited security product.
- It needs to be hosted on HTTPS for encryption and offline installation to work.

FREE PUBLISHING OPTION:
1. On a computer, create/sign in to a GitHub account and create a new PUBLIC repository named private-notes.
2. Upload all files from this folder to the repository's main/root folder.
3. In the repository, open Settings -> Pages.
4. Under Build and deployment, choose Deploy from a branch, branch main, folder /(root), then Save.
5. Wait for GitHub Pages to publish the site. Open the published HTTPS address on your iPhone in Safari.
6. Tap Share -> Add to Home Screen -> Add.

If you only have your iPhone, you can still create the GitHub repository and upload the files using GitHub's website, but uploading multiple files is easier from a computer.
