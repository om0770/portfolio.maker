# Portfolio Builder 
**Crafted by Om | PhotOm Designs**

Welcome to the official repository for the Portfolio Builder, a powerful, client-side web application designed to generate professional, responsive portfolio websites in minutes. 

---

## 🎯 What Does It Do?
The Portfolio Builder is a completely self-contained, no-code website generator. It allows you to visually assemble a personalized portfolio by selecting from tailored themes (Corporate, Minimalist, Creative, Terminal, Photography, Academic), customizing your content, and instantly exporting a production-ready, single `index.html` file. 

## ⚙️ How Does It Work?
The entire architecture is designed to be lightweight and run 100% locally in your web browser. There are no databases, no backend servers, and no installations required.

*   **Tech Stack:** Vanilla HTML5, JavaScript, and Tailwind CSS (via CDN).
*   **Live Emulator:** As you update text, tweak colors, or upload images, a flawless scaling emulator renders the exact Desktop, Tablet, and Mobile views in real-time.
*   **Media Handling:** It utilizes Cropper.js to natively resize and format images directly in the browser, converting them into Base64 strings saved to your local storage.
*   **One-Click Export:** Once the design is finalized, the app compiles the CSS, HTML, and JavaScript (including an optional AI Chatbot widget) into a single, highly optimized file.

## 🤝 Who Are the Beneficiaries?
This tool is built for anyone who needs a beautiful digital presence quickly:
*   **Freelancers & Creatives:** Photographers, artists, and designers who need a visual-heavy site to showcase their work.
*   **Developers & Tech Professionals:** Engineers who want a clean, terminal-style or minimalist site to display case studies and GitHub links.
*   **Students & Academics:** Researchers and job-seekers who need a structured format for their resumes, timelines, and publications.
*   **Small Business Owners:** Service providers looking for a fast, reliable landing page to collect client inquiries via the built-in contact form.

## 🧩 What Problems Does It Solve?
*   **The Complexity Barrier:** Building a website traditionally requires knowing HTML/CSS/JS or navigating clunky CMS dashboards. This tool removes the learning curve entirely.
*   **Expensive Subscriptions:** Standard website builders charge monthly fees. This provides a premium output that can be hosted entirely for free.
*   **Hosting Friction:** Traditional sites require managing multiple files, assets, and folders. By bundling everything into one self-sufficient file, deployment becomes as simple as a drag-and-drop.
*   **Data Privacy:** Because everything runs locally and saves to browser storage, user data never touches a third-party server during the creation process.

## 🚀 How Is It Better Than Others?
*   **Zero Dependencies:** No `npm install`, no complex build steps, and no bulky frameworks. Just open the file and start building.
*   **Flawless Device Emulation:** Unlike standard responsive views that just shrink the window, the built-in emulator scales the physical dimensions perfectly, letting you see the true mobile and tablet experience on a desktop monitor.
*   **All-in-One File Architecture:** Everything from the custom fonts and Tailwind styling to the image data and interactive chatbot is bundled into the final export. You never have to worry about broken image links or missing CSS files.

---

## 🛠️ Step-by-Step Guide: Creating Your Portfolio

Creating your website takes only a few minutes. Here is how to do it:

1.  **Open the Tool:** Download this repository, unzip it, and double-click the main `index.html` file to open it in your web browser (Chrome, Safari, Edge, etc.).
  <div align="center">
  <a href="https://github.com/user-attachments/files/29740986/index.html">
    <img src="https://img.shields.io/badge/Download-Portfolio_Builder-blue?style=for-the-badge&logo=github" alt="Download Portfolio Builder" />
  </a>
</div>



2.  **Pick a Template:** In the left sidebar, go to **Configuration > Templates**. Choose a layout that fits your profession. 
3.  **Customize Your Content:** 
    *   Go through the sidebar sections (Introduction, About Details, Skills, Projects, etc.).
    *   Type in your details, pick your custom colors under **Colors & Fonts**, and upload your images (the tool will let you crop them perfectly).
4.  **Preview Your Work:** Click the **Toggle Preview** button (or the floating eye icon on mobile) to see exactly how your site looks on Desktop, Tablet, and Mobile.
5.  **Export:** Click the **Export** button at the top right of the screen. A file named `index.html` will download to your computer.


---
### 1. Accessing the Editor Menu
By default, the main configuration sidebar is hidden on mobile devices to give you maximum space for typing and editing. To access the tools, tap the **hamburger menu icon** (three horizontal lines) in the top-left corner of the screen.

<img src="https://github.com/user-attachments/assets/091dfc58-dd1f-41bb-a36b-2c0f29fc22ff" alt="Open Editor Menu" width="210" height="100" style="max-width: 100%; height: auto;">

---

### 2. Navigating the Admin Panel
Once you open the menu, the **Admin Panel** will slide in. From here, you can scroll through all the available tools. Use this panel to switch templates, update your SEO settings, change global colors, and jump between different content sections (like Hero, About, and Projects).

<img src="https://github.com/user-attachments/assets/682d13bd-462f-4ef0-bdc1-c5b30273e324" alt="Admin Panel Sidebar" width="260" height="480" style="max-width: 100%; height: auto;">

---

### 3. Checking Your Progress
As you update text or upload images, you will want to see how the final website is shaping up. Simply tap the floating orange **PREVIEW** button located at the bottom of your screen to instantly load the live emulator. Tap it again to close it and return to the editor.

<img src="https://github.com/user-attachments/assets/01daa1b3-6cab-4fa7-a988-d89b17278bc1" alt="Floating Preview Button" width="250" height="120" style="max-width: 100%; height: auto;">

---

### 4. Using the Device Emulator
While inside the Preview screen, you are not just looking at a standard web page—you are using a flawless scaling emulator. Use the **device toggle icons** at the top of the preview screen to see exactly how your portfolio will look and feel on a mobile phone, a tablet, or a full desktop monitor.

<img src="https://github.com/user-attachments/assets/df9716b5-3a0c-46d6-ae03-f600e01fb960" alt="Device Emulator Toggles" width="260" height="480" style="max-width: 100%; height: auto;">


## 🌐 Publishing Guide: Getting Your Site Live for Free

Once you have your `index.html` file, you need to host it on the internet so people can visit it. Both GitHub Pages and Vercel offer fantastic, free hosting for this exact type of file.

### Option A: Hosting via GitHub Pages (Best for keeping everything in one place)

1.  **Create a GitHub Account:** Go to [GitHub](https://github.com/) and sign up or log in.
2.  **Create a New Repository:** 
    *   Click the green **New** button on the left sidebar.
    *   Name your repository (e.g., `my-portfolio`).
    *   Check the box that says **"Add a README file"**.
    *   Click **Create repository**.
3.  **Upload Your File:**
    *   In your new repository, click the **Add file** button near the top right, then select **Upload files**.
    *   Drag and drop your final `index.html` file onto the screen.
    *   Click the green **Commit changes** button.
4.  **Activate GitHub Pages:**
    *   Click the **Settings** tab at the top of your repository page.
    *   On the left sidebar, click **Pages**.
    *   Under the "Build and deployment" section, look for "Branch". Change the dropdown from "None" to **main**.
    *   Click **Save**.
5.  **Wait and View:** Wait about 2–3 minutes. Refresh the page, and GitHub will display the live URL to your brand-new website at the top!

### Option B: Hosting via Vercel (Best for blazing-fast loading speeds)

1.  **Upload to GitHub First:** Follow steps 1 through 3 from the Option A guide above to get your `index.html` file into a GitHub repository.
2.  **Create a Vercel Account:** Go to [Vercel](https://vercel.com/) and click **Sign Up**. Choose to sign up using your GitHub account.
3.  **Import Your Project:**
    *   Once logged into Vercel, click the **Add New...** button and select **Project**.
    *   You will see a list of your GitHub repositories. Find the one you just created and click **Import**.
4.  **Deploy:**
    *   Leave all the settings exactly as they are on the next screen.
    *   Click the blue **Deploy** button.
5.  **Celebrate:** Within 10 to 15 seconds, Vercel will finish building your site and provide you with a live, shareable URL!

---

## 📝 License

**Copyright (c) 2026 PhotOm Designs. All Rights Reserved.**

This project is proprietary and closed-source. You may view the code for educational purposes, but you may not copy, modify, distribute, or use this software (or any of its parts) for personal or commercial purposes without explicit written permission from PhotOm Designs.
