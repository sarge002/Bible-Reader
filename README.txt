BIBLE READER — FIRST WORKING VERSION

Files
- index.html: the app
- ERV-hu_combined.json: your Bible text and commentary data (keep the exact filename)
- edits.json: starter file for personal edits

RUN LOCALLY
For the most reliable result, upload the files to a GitHub repository and enable GitHub Pages. The app loads ERV-hu_combined.json and edits.json from the same folder. Browsers often block automatic JSON loading if index.html is opened directly as a file.

GITHUB PAGES
1. Create/open your repository.
2. Upload index.html, ERV-hu_combined.json, and edits.json into the repository root (the same folder).
3. In the repository, open Settings → Pages and enable deployment from your main branch and root folder.
4. Open the published Pages URL.

YOUR EDITS
- Edits are saved automatically in this browser, separately from the original Bible JSON.
- Open Settings → Export edits.json to download a portable backup.
- To use that backup on another browser/device, open Settings → Import edits.json.
- To make the exported version the starter edits.json for a newly deployed copy, upload the exported file to GitHub and replace the existing edits.json.
- GitHub Pages is read-only from the app: it cannot silently write your edits back to the repository.

CURRENT BUILD NOTES
- The app is a first working foundation, not yet the final polished version of every requested feature.
- Verse popup includes highlighting, editing verse text/footnotes, layout controls, and adding headings.
- Custom headings can be edited, collapsed/expanded, or deleted.
- Search covers verse text, footnotes, and custom headings.
- Highlights are listed in Bible order and can be filtered by color.
- The renderer supports the common markup found in the supplied JSON while refusing to execute arbitrary HTML.
- Future translation files can be configured in the TRANSLATIONS list near the top of the app script. The version selector is intentionally not shown yet while only one translation is configured.
