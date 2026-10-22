⚔️ SOLO SYSTEM

Your Life. Your Quests. Your Evolution.

SOLO SYSTEM is a Solo Leveling-inspired personal habit tracker designed to turn everyday routines into quests, consistency into progress, and personal growth into a rank progression journey.

Build better habits, maintain your streaks, complete your daily objectives, and rise through the ranks from F to S++.

«Your system is waiting. Your next evolution starts now.»

---

✨ Highlights

Feature| Description
🎯 Habit Tracker| Organize and track the habits you want to build into your daily life.
⚔️ Quest System| Approach your goals as quests and make everyday progress feel rewarding.
📈 Rank Progression| Progress through nine ranks, from F to the ultimate S++ rank.
🔥 Streak Tracking| Build consistency by maintaining your routines over time.
👤 Personalized Experience| Customize your system to better match your preferences.
🐉 Assistant Studio| Assign a unique PNG image to each rank and personalize your mythical guardians.
💾 Local Customization| Keep your custom assistant artwork in your browser and back it up when needed.
📱 Web App Experience| Access the app through a supported browser, with installation availability depending on your device and hosting setup.

---

🏆 The Rank System

Your journey spans nine ranks. Each rank has its own identity and colour theme.

Rank| Rank Theme
F| Light Blue + White
E| Dark Blue
D| Black + Purple
C| Golden Yellow
B| Crimson Red
A| Emerald Green
S| Angel White
S+| Ash Black
S++| Heavy Purple + Black

Every rank represents another step in your journey. Work toward your goals, build consistency, and make your system your own.

---

🐲 Assistant Studio — Make It Yours

Your system, your guardian.

Assistant Studio lets you personalize the assistant artwork for all nine ranks. You can use mythical creatures, original characters, fantasy artwork, or any PNG images you prefer.

What You Can Do

- Customize each rank: Assign a different image to F, E, D, C, B, A, S, S+, and S++.
- Preview your artwork: Check an image before applying it.
- Change it anytime: Replace your selected image whenever you want.
- Reset individual ranks: Return a selected rank to its default state.
- Reset all ranks: Clear your customizations and restore the default state.
- Back up your setup: Export and import the Assistant Studio JSON configuration.

How to Customize Your Guardian

1. Open SOLO SYSTEM.
2. Navigate to Others → Assistant Studio.
3. Select the rank you want to customize.
4. Choose a PNG image from your device.
5. Preview the image and apply it.
6. Repeat for any other ranks you want to personalize.

Tip: Choose artwork with a clearly visible subject, good contrast, and a composition that remains recognizable on a mobile screen.

Where Are Custom Images Saved?

Custom assistant images are stored locally in your browser using IndexedDB.

- Your uploaded images are not automatically uploaded to GitHub.
- Customizations do not automatically synchronize between devices or browsers.
- Clearing browser site data may erase locally stored customizations.
- Export your Assistant Studio backup and keep your original PNG files somewhere safe.

«Important: The blank-assistant GitHub package intentionally contains no default rank assistant artwork. The assistant area will remain blank until you add images through Assistant Studio.»

---

🚀 Getting Started

Option 1 — Use the Published Website

If you have a published SOLO SYSTEM website, open its HTTPS URL in a supported browser and start using the app.

Option 2 — Deploy Your Own Copy with GitHub Pages

You can host your own copy of SOLO SYSTEM using GitHub Pages.

1. Download and extract the SOLO SYSTEM GitHub package.
2. Upload the package contents to the root of your GitHub repository.
3. Make sure "index.html" and "manifest.webmanifest" are present in the repository root.
4. Open your repository's Settings → Pages.
5. Under the build and deployment settings, select Deploy from a branch.
6. Choose the "main" branch and the "/(root)" folder, then save.
7. Wait for deployment to complete and open the published HTTPS URL.

GitHub's interface may vary slightly. If your repository uses a different branch, select the branch containing your application files.

Option 3 — Run Locally

Download or clone the repository and open "index.html" in a browser.

Some features, particularly installable web-app functionality, may behave differently when the HTML file is opened directly. If you encounter issues, try running the app through a local web server or GitHub Pages.

---

💾 Data, Storage & Privacy

SOLO SYSTEM uses browser storage for application data and custom assistant images.

What You Should Know

- Browser-specific storage: Data saved in one browser may not be available in another.
- Local versus hosted copies: Opening a local HTML file and visiting a GitHub Pages deployment are different origins; their stored data is not automatically shared.
- Custom artwork: Assistant Studio images are stored locally and are not automatically committed to your repository.
- Backups matter: Export available application data and Assistant Studio configurations before clearing browser data or moving to another device.
- Protect your backups: Personal JSON backups may contain information you do not want to publish. Keep them out of public repositories.

Remember: GitHub Pages source files in a public repository are publicly accessible. Never commit passwords, private information, or personal backups to a public repository.

---

🛠️ Troubleshooting

<details>
<summary><strong>My assistant image is not appearing</strong></summary>- Open Others → Assistant Studio.
- Confirm that you selected the intended rank.
- Select the PNG again, preview it, and apply it.
- Check that you are using the same browser and device where you saved the image.

</details><details>
<summary><strong>My custom assistant images disappeared</strong></summary>Custom images may be unavailable if browser site data was cleared or you switched browsers or devices.

Restore your Assistant Studio configuration from a previously exported backup if available. Keep your original PNG files as well.

</details><details>
<summary><strong>My progress is missing after changing browsers or deployments</strong></summary>Local browser storage is not automatically shared between a local HTML file, another browser, and a hosted website.

If your previous version supports exporting and importing tracker data, export a backup from the old version before moving and import it into the new version.

</details><details>
<summary><strong>I cannot install the web app</strong></summary>Installability depends on the browser, device, and hosting configuration. Try opening the published HTTPS website in a supported browser and look for its available installation option.

</details>---

📦 Repository Contents

File or Folder| Purpose
"index.html"| Main SOLO SYSTEM application, including Assistant Studio.
"assets/"| Reserved for future application assets and rank artwork. It may be empty in the blank-assistant package.
"manifest.webmanifest"| Web app manifest used for supported PWA installation and metadata.
"app-icon.svg"| Application icon in SVG format.
"app-icon-192.png"| Application icon asset.
"app-icon-512.png"| Application icon asset.

The application icons are separate from rank assistant artwork and remain included even when the default assistant images are removed.

---

💡 Tips for Your Journey

- Start with a manageable set of habits and build from there.
- Focus on consistency rather than perfection.
- Review your progress regularly.
- Choose goals that matter to you.
- Personalize your guardians to make the experience feel like your own.
- Back up your data and customizations when needed.

Progress is built through repeated actions. Keep showing up, completing your quests, and working toward your next rank.

---

🤝 Feedback & Improvements

Found a bug or have an idea to improve SOLO SYSTEM?

When reporting an issue, include:

- What you were trying to do.
- The steps you followed.
- What you expected to happen.
- What actually happened.
- Your browser and device, if relevant.

Clear details make issues easier to understand and resolve.

---

<div align="center">⚔️ YOUR JOURNEY. YOUR RULES. YOUR EVOLUTION.

Build your habits. Complete your quests. Earn your rank.

Welcome to SOLO SYSTEM.

</div>
