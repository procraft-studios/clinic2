# Dr. Shaikh's Clinic — Website

A clean, static rebuild of the clinic website (originally built on Base44), ready to host on GitHub Pages.

## Files
- `index.html` — the whole site (one page)
- `style.css` — all styling
- `images/logo.jpg` — clinic logo
- `images/doctor.jpg` — hero photo
- `images/favicon.png` — browser tab icon

## Deploy on GitHub Pages (step by step)

1. Go to [github.com/new](https://github.com/new) and create a new repository (e.g. `shaikh-clinic`). Keep it **Public**.
2. On the new repo's page, click **"uploading an existing file"** (or use "Add file" → "Upload files").
3. Drag in **all the files and the `images` folder** from this project, keeping the same names and folder structure.
4. Commit the changes.
5. Go to the repo's **Settings** tab → **Pages** (in the left sidebar).
6. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Click **Save**.
7. Wait about a minute, then refresh — GitHub will show you a live URL like:
   `https://your-username.github.io/shaikh-clinic/`

That's it — no build step, no server needed. It's a plain HTML/CSS site.

## Notes
- The "Book Appointment" buttons currently call the clinic phone number (`0240 247 9013`). Swap the `href="tel:..."` for a booking link/form if you get one later.
- The WhatsApp footer button links to `https://wa.me/912402479013` — double check this number can actually receive WhatsApp messages (it looked like a landline in the original site).
- The original site also had a "Health Journal" (blog) section that wasn't visible in the page I could recover — let me know if you want that added back and what should go in it.
