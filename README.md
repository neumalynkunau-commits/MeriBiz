# MeriBiz PNG — starter prototype

A mobile-friendly, website-first prototype for women entrepreneurs in Papua New Guinea.

## Included in this MVP prototype
- Responsive mobile-friendly interface
- Add and remove products/services
- Record sales and expenses in Kina (K)
- Dashboard totals and simple sales-minus-expenses balance
- Business profile and store preview
- Optional WhatsApp order link for products
- Export sales/expense records to CSV

## Run it locally
Open `index.html` in a modern browser. No build step is needed.

## Publish with GitHub Pages
1. Sign in to GitHub and create a repository, e.g. `meribiz-png`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then Save.
6. Wait for GitHub Pages to publish the site; use the URL shown in Settings → Pages.

Tip: If using a phone, GitHub Pages settings and uploads are usually easier in Chrome than inside the GitHub app. If uploading a ZIP, extract it first and upload the files, not just the ZIP.

## Important prototype limitations
- Data is stored in this browser's local storage on this device only.
- There are no user accounts, shared/cloud database, image uploads, multi-device sync, or secure backups.
- This is a prototype, not ready for storing sensitive customer or financial information.
- WhatsApp order links open WhatsApp; they do not process payments or confirm inventory.
- The balance is sales minus recorded expenses; it is not necessarily accounting profit.

## Suggested next development stage
Before public business use, add:
1. Authentication and per-user access controls.
2. A managed database and server-side authorization.
3. Cloud image storage with file limits.
4. Validation, backups, privacy notice, and a way to export/delete account data.
5. Clear marketplace rules, reporting tools, and a process for handling complaints.
6. User testing with women entrepreneurs in multiple PNG provinces, including users with low data connectivity.

## Suggested technology when moving beyond prototype
- Front end: HTML/CSS/JavaScript initially; React + Vite when the interface grows.
- Hosting: GitHub Pages for the static prototype.
- Database/authentication later: Supabase or Firebase, after reviewing privacy, pricing, connectivity, and security needs.
- Images: compressed uploads to a managed storage service.
- Orders: begin with WhatsApp/manual confirmation before adding payment integrations.
