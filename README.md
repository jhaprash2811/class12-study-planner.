# Class 12 Study Hub

A mobile-friendly study planner for six Class 12 subjects. It tracks chapter status, calculates syllabus completion, allocates more time to less-complete subjects, and saves progress in the browser.

## Publish with GitHub Pages

1. Sign in to GitHub and create a **new public repository** named `class12-study-planner` (or any name you like).
2. Upload all files from this folder to the repository's root:
   - `index.html`
   - `styles.css`
   - `app.js`
   - `manifest.webmanifest`
   - `sw.js`
3. Open the repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait a minute or two. GitHub will show your website URL in the Pages section.

## How to use

- Open the website and go to **Subjects**.
- Set every chapter to **Not started**, **In progress**, or **Completed**.
- Add or remove chapters to match your current CBSE syllabus.
- **Overview** shows subject and overall completion percentages.
- **Day planner** distributes your chosen daily study hours, giving more time to subjects with lower completion.
- Since school/coaching times vary, the plan is based on session lengths, not fixed clock times. Fit sessions around your day.
- **Reminders** lets you choose a daily reminder time and request browser notifications.
- Export a JSON backup regularly. Import it if you change browser/device.

## Important notes

- The starter chapter lists are editable examples based on common Class 12 course structures. Confirm the exact 2026–27 CBSE syllabus and your school's Electronics & Hardware units, then edit the lists.
- Progress is saved in browser local storage on the device/browser where you use the site. GitHub Pages does **not** sync it across devices. Export/import a backup to move progress.
- Browser reminders are checked while the planner page is open. A normal static GitHub Pages website cannot guarantee scheduled notifications after the browser is closed.
- If you update files on GitHub, refresh the website. If an old version remains cached, clear the site's browser cache or update the cache name in `sw.js`.
