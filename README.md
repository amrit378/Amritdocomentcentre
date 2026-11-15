# AMRIT DOCUMENT CENTRE

A personal-use, mobile-friendly document print portal starter project.

## Features
- Dashboard with job count, today's jobs and service-charge total
- RC, DL, Motor ID, mobile-link assistance, PDF print and download job categories
- Customer/job history with search, delete and CSV export
- Customer-provided PDF/image preview and browser print
- Responsive layout for phones and computers
- GitHub Pages deployment workflow

## Important limitations
This is a static starter website. It does **not** provide secure server-side authentication, cross-device cloud sync, government database access, or automatic RC/DL retrieval. Job history is saved in the browser's local storage on the device/browser where it was entered. It is not automatically shared between your phone and computer.

Do not store OTPs, passwords, Aadhaar numbers, or other sensitive credentials in this site. OTP entry must remain on the relevant official service. Use only official/authorized sources and authentic customer documents.

## Publish using your GitHub account
1. Sign in to GitHub and create a new repository, for example `amrit-document-centre`.
2. Upload **all files and folders** from this project ZIP. Make sure `index.html` is in the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, select **GitHub Actions** as the source.
5. The included workflow `.github/workflows/deploy.yml` will publish the site. Open the **Actions** tab and wait for the Pages workflow to finish.
6. Your website address will look like `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Updating
Edit `index.html` on GitHub and commit the change. GitHub Actions will publish the update.

## Recommended next upgrade
For secure admin login and synchronized history across phone/computer, add a real backend and database (for example, Supabase or Firebase) with access rules. Do not put private API keys or passwords in this static repository.
