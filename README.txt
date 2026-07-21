DECK GIANT WEBSITE — PRODUCTION BUILD (for GitHub + Cloudflare)
===================================================================

WHAT CHANGED FROM THE PREVIOUS DOWNLOADS
-------------------------------------------
Earlier bundles had every photo embedded directly inside each HTML
file (as base64 text) — great for easy previewing in chat, but it
made every page several megabytes.

This version separates images back into real files. Result:

    Before (embedded):   2,000-4,000 KB per page
    Now (linked):           24-32 KB per page

Same look, same content — just dramatically lighter and faster.

WHAT'S IN THIS FOLDER
-----------------------
All 11 HTML pages and all 55 photos sit together in ONE flat folder
(no subfolders). This is intentional — it's the simplest, lowest-risk
structure to drag-and-drop straight into GitHub with zero risk of
broken image paths.

  index.html          Home
  pergolas.html        Pergolas
  decks.html            Decks
  carports.html         Carports
  pavilions.html        Pavilions
  about.html            About
  upgrades.html         Upgrades
  faq.html              FAQ
  pricing.html          Pricing
  our-process.html      Our Process
  gallery.html          Gallery

  + 55 .webp/.png image files

NEXT STEPS
------------
1. Create a free GitHub account at github.com (if you haven't yet).
2. Create a new PUBLIC repository (e.g. "deckgiant-website").
3. Click "Add file > Upload files" and drag in EVERYTHING from this
   folder — all 11 HTML files and all the images, all at once, into
   the root of the repo (don't create a subfolder for them).
4. Commit the upload.
5. Go to pages.cloudflare.com, sign up free, "Create a project >
   Connect to Git," authorize GitHub, pick this repo, deploy.
6. You'll get a free live preview link like:
       deckgiant.pages.dev
   Review everything there before connecting your real domain.

STILL MISSING
---------------
- Contact page (needed before any "Request a Quote" button will
  actually go anywhere)
- The contact FORM itself won't send email until it's wired up to
  a form service like Formspree — a quick one-time setup once the
  Contact page exists

Come back to this same Project any time to keep working — just
re-upload this folder (or the next one I give you) so I have the
current files again.
