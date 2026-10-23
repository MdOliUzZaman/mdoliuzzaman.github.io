# Md Oli Uz Zaman — personal website

Live at: https://YOUR-USERNAME.github.io

## How to update the site (no software needed)

1. Go to your repository on github.com and click **index.html**.
2. Click the **pencil icon** (Edit this file).
3. Near the top you'll see a block that starts with `const SITE = {`. All your
   content lives there: about text, publications, experience, talks, awards,
   reviewer list, links.
4. Copy an existing entry, paste it at the top of its list, and change the text.
   Keep the quotes "..." and the comma after each entry.
5. Change `updated: "October 2026"` to the current month.
6. Click **Commit changes**. The site updates in about a minute.

### Common edits
- **New paper:** copy one block inside `publications: [` and edit title, authors, venue, year, url.
- **New talk / award / review:** add a line to `talks`, `awards` or `service`.
  The talk count and peer-review count update automatically.
- **Years at Intel:** counts automatically from January 2023.
- **New resume PDF:** on the repository page click **Add file → Upload files**,
  upload your PDF named exactly `cv.pdf`, and commit (it replaces the old one).
  The web version of the resume is the block between `RESUME PAGE` comments in
  index.html; edit it the same way.
- **New photo:** upload a square image as `images/photo.jpg`.

If something breaks, open the **History** of index.html and restore the previous version.
