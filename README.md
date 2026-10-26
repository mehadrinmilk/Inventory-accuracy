# Inventory Accuracy

Tracks which warehouse products have been confirmed accurate.

- Website: plain HTML hosted on GitHub Pages (`index.html`, `config.js`)
- Login and data: Supabase (database rules in `setup.sql`, which is kept outside this repo)
- Only the owner can mark products, upload files and approve people. Approved people can view.
- Product data is not stored in this repository. It lives in Supabase and is loaded through the app's Upload tab.
