nky-portfolio | README v1.0 (October 2025)
============================================================
Author: Natalia Kong Yi
------------------------------------------------------------
Description:
This document provides a quick overview of how to edit, 
update, and publish the NKY Portfolio website.

------------------------------------------------------------
STRUCTURE
------------------------------------------------------------
/en/                 → English version (main)
/es/                 → Spanish version (mirror)
/shared/css/         → Global modular CSS (style, accent, footer, variables)
/shared/assets/      → All visual and UI assets
/shared/docs/        → Technical documentation
/favicon.ico         → Browser icon

------------------------------------------------------------
EDITING PROJECTS
------------------------------------------------------------
To add or update a project:
1. Duplicate any HTML file inside `/en/projects/` and rename it.
2. Replace the title, description, and tags.
3. Add your images in `/shared/assets/images/projects/[project-name]/`.
4. Update the grid in `work.html` (both EN and ES) with:
   - thumbnail
   - title
   - year
   - tags
   - link to the individual project page.

------------------------------------------------------------
LANGUAGE SWITCH
------------------------------------------------------------
Each page has an EN | ES toggle.
When creating new pages, make sure both versions link
to each other correctly (e.g., en/project1.html ↔ es/project1.html).

------------------------------------------------------------
PUBLISHING ON GITHUB PAGES
------------------------------------------------------------
1. Go to your repository’s Settings → Pages.
2. Choose the branch (main or master) and root directory.
3. Save and wait for the link to be generated (it usually ends with `.github.io`).
4. Test that all links and images load correctly.

------------------------------------------------------------
CUSTOMIZATION
------------------------------------------------------------
- Color scheme → edit `/shared/css/variables.css`
- Accent hover → edit `/shared/css/accent.css`
- Fonts → change `--font-main` in `/shared/css/variables.css`
- Footer → edit `/shared/css/footer.css`
- Favicon → replace `/shared/assets/images/ui/icon.png` and `/favicon.ico`

------------------------------------------------------------
MAINTENANCE TIPS
------------------------------------------------------------
- Keep image files under 300 KB for web performance.
- Test all links after renaming folders.
- Use consistent lowercase file names with hyphens.
- Validate HTML with https://validator.w3.org/
- Back up `/shared/docs/` regularly.

------------------------------------------------------------
VERSION HISTORY
------------------------------------------------------------
v1.0 — Initial release, October 2025
