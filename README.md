# CBSE Class 10 Study Hub (2026–27)

## What's included
- Responsive, mobile-friendly study portal.
- Official CBSE question-paper archive, current sample-paper/marking-scheme page, curriculum portal and NCERT links.
- Original starter Maths quiz questions with scoring, hints and answer review.
- Student profile and quiz history stored locally in the browser.
- Weak-chapter finder based on saved quiz averages.
- Revision bookmarks / mistake book to save questions from quiz results.
- Personal study-task checklist saved on the device.
- Export progress as JSON, clear history, formula cards, first-20-elements chart, text-based mind-map starters, puzzle and general career guidance.
- PWA manifest and service-worker caching starter.

## Run locally
Open `index.html` in a browser. Quiz history, profile, bookmarks and study tasks use localStorage. PWA installation/service-worker features require HTTPS or localhost.

## Publish on GitHub Pages
1. Create a repository (for example, `cbse-class10-hub`).
2. Upload all files in this folder to the repository root.
3. Open **Settings → Pages**, choose the main branch and root folder, then save.
4. Wait for the published HTTPS URL.

## Important limitations
- This is a front-end starter, not a complete production account system. Profile, scores, bookmarks and tasks stay in the same browser/device; there is no cloud sync or authentication. Export progress before changing devices or clearing browser data.
- The quiz bank, formula sheets and mind maps are starter content, not complete coverage of every 2026–27 chapter. Verify content against the official current syllabus and NCERT before relying on it for exam preparation.
- Previous-year papers are linked to CBSE's archive rather than bundled. A separate official answer key may not exist for every paper; do not label unofficial solutions as CBSE-approved.
- Career guidance is general information. Confirm eligibility, fees and deadlines from the relevant official institution.
- The site is an independent study companion and is not affiliated with CBSE or NCERT.

## Official links used
- CBSE 2026–27 Class X sample papers and marking schemes: https://cbseacademic.nic.in/SQP_CLASSX_2026-27.html
- CBSE previous-year question-paper archive: https://www.cbse.gov.in/cbsenew/question-paper.html
- CBSE curriculum portal: https://cbseacademic.nic.in/curriculum_2027.html
- NCERT: https://ncert.nic.in/

## APK
PWA installation does not create an APK. To make an APK, wrap/build the web app using a toolchain such as Capacitor with Android Studio, test on real devices, and sign the Android package. Add secure authentication and a backend before offering cross-device student accounts.


## Combined offline edition
This package includes the starter website, administrator details, offline paper catalogue, the uploaded Maths and Science paper PDFs, and the starter formula/quiz/planner PDF. Open `index.html` in a browser for the site. Use the **Offline PYQs** link to browse the included PDF library. Some external official resource links still require internet.

**Administrator:** Himanshu Kumar Singh — PM Shri School, Jawahar Navodaya Vidyalaya.

Note: The included papers are the PDFs supplied in the uploaded archives; this does not guarantee a complete CBSE archive for every year or set. Quiz/profile data is stored locally in the browser and does not sync between devices.
