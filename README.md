Website Upload Manual
======================

This manual explains how to upload or update content for the EEE Department website.

1. Open the website folder
---------------------------
- Navigate to the local workspace folder:
  c:\Users\asg29\Documents\GitHub\EEE DEPARTMENT WEBSITE DEV

2. Update page content
-----------------------
- The website content is stored in HTML files such as:
  - index.html
  - about.html (if present)
  - announcements.html
  - activities.html
  - events.html
  - gallery.html
  - notes.html
  - placements.html
  - projects.html
  - syllabus.html

- Open the appropriate HTML file in a text editor and edit the text inside the relevant section tags.
- Save the file after making changes.

3. Replace or add images
------------------------
- Store image files in the `images` folder.
- Update the image reference inside the HTML file, for example:
  <img src="images/your-image.jpg" alt="Description">
- If the site uses JavaScript to set image URLs, make sure to update the path in `script.js` under the `siteConfig.images` section.

4. Update navigation links
---------------------------
- Edit the navigation links in `index.html` inside the `<nav class="top-nav">` section.
- For mobile menu links, update the links inside the `.mobile-menu-links` block.
- Use anchor IDs if the target is a section on the same page, or page filenames for separate pages.

5. Save and preview locally
----------------------------
- Save all changed files.
- Open `index.html` (or the updated page) in a browser to verify the content and layout.
- If the site is still local, use your browser’s refresh button after saving.

6. Publish changes to the live website
--------------------------------------
- If the website is hosted using GitHub Pages or another hosting service, commit your changes to the repository and push them to the remote branch.
- Example with Git:
  git add .
  git commit -m "Update website content"
  git push origin main

7. Notes and best practices
---------------------------
- Keep backups of original files before making large changes.
- Use descriptive `alt` text for images.
- Keep HTML structure tidy and avoid breaking existing section IDs or navigation markup.
- Verify section IDs match navbar anchor links (for example `href="#about_us"` and `id="about_us"`).

If you need a second manual for image uploads or file-specific instructions, I can create that too.
