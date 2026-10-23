# Cheshire & North Wales Hawking Club Website 🦅

This repository contains the source code for the official website of the **Cheshire & North Wales Hawking Club (CNWHC)**, a vibrant falconry club made up of passionate enthusiasts from Cheshire, North Wales, and the wider North West of England.

🔗 **Live Website:** [https://canwhc.co.uk](https://canwhc.co.uk)

## 📌 Project Overview

The website serves as a digital hub for existing club members and a welcoming portal for prospective falconry enthusiasts. It provides essential information regarding monthly meetings, field events, membership requirements, and contact details for the club's committee.

### Key Content Tracked on the Site:
*   **Monthly Meetings:** Held on the first Tuesday of every month at 8 PM at the Railway Inn, Helsby.
*   **Field Meetings:** Information on heavily subsidised field meets for both longwings and shortwings throughout the season.
*   **Membership Management:** Details on annual fees (£30/year), benefits (insurance, private groups, Hawk Board representation), and how to apply.
*   **Media Gallery:** Visual showcases of members' birds (Peregrine Falcons, Harris Hawks, Goshawks) and field meets.

## 🛠️ Built With

*   **[Hugo](https://gohugo.io)** - Fast static site framework
*   **Markdown** - Content format
*   **HTML5 / CSS3 / JS** - Front-end templates and styling

## 🚀 Getting Started

To get a local copy of this project up and running for development or content updates, follow these steps.

### Prerequisites
Make sure you have **Hugo** installed on your local machine.

*   **macOS (via Homebrew):**
    ```bash
    brew install hugo
    ```
*   **Windows (via Chocolatey):**
    ```powershell
    choco install hugo-extended
    ```
*   **Linux (Debian/Ubuntu):**
    ```bash
    sudo apt-get install hugo
    ```

### Installation & Local Development

1. Clone the repository (including submodules if your theme uses them):
   ```bash
   git clone --recurse-submodules https://github.com
   ```
2. Navigate into the project directory:
   ```bash
   cd canwhc-website
   ```
3. Start the local Hugo development server:
   ```bash
   hugo server
   ```
4. Open your browser and navigate to `http://localhost:1313/` to view the site.

## 📝 Making Content Updates

To update or add content (such as meeting schedules, announcements, or gallery images):
1. Locate or create Markdown files inside the `content/` directory.
2. Ensure front matter variables (like `title`, `date`, and `draft`) are configured properly.
3. Save your changes and preview them on the local dev server before pushing to production.

## 🌐 Deployment

This project is configured for automated deployment via **Render**. 

Every time changes are pushed to the `main` or `master` branch, Render triggers a new build automatically using the following settings:
*   **Environment:** `Static Site`
*   **Build Command:** `hugo --gc --minify`
*   **Publish Directory:** `public`

## 👥 Contributing

We welcome contributions to improve the website's performance, design, or accessibility although the club's committee have overall control of content. 

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---
*Website codebase maintained on behalf of CNWHC. Imagery and copy assets are property of their respective club members.*
