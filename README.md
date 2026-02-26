# BabyBite Legal Documents

This directory contains the public-facing legal documents for BabyBite. These pages are designed to be hosted as a static site (e.g., via GitHub Pages).

## 📂 Structure

- `index.html`: The main landing page/directory for legal documents.
- `terms/index.html`: Terms of Service (multi-language support).
- `privacy/index.html`: Privacy Policy (multi-language support).

## 🛠 Features

- **Multi-language Support**: All pages include built-in language switching (EN, FR, ES, DE, AR, ZH).
- **Responsive Design**: Mobile-first CSS tailored for a premium brand feel.
- **Privacy-Focused**: Documents explicitly state that no baby data is stored on our servers.

## 🚀 Hosting on GitHub Pages

This folder is 100% compatible with GitHub Pages.

### Quick Start
1. Push this folder to your GitHub repository.
2. Go to **Settings > Pages**.
3. Select the branch and folder (e.g., `/legal`).
4. Click **Save**.

### Recommendations
- **.nojekyll**: Add an empty `.nojekyll` file to the root of your deployment branch to bypass Jekyll processing.
- **Pathing**: All internal links are relative (`./` or `../`), so the site will work whether it's hosted at `babybite.app/legal/` or a custom subdomain.

## 📝 Maintenance

When updating terms or privacy policies:
1. Update the **"Last updated"** date in the specific HTML file.
2. Ensure you update all language sections (EN, FR, ES, etc.) to maintain consistency.
3. Verify links after editing.

---
&copy; 2026 BabyBite. All rights reserved.
