# Portfolio (Software Engineer version): Emmanuel Seun Shittu

A static site (`index.html` plus an `assets` folder), no build step, so Vercel serves it as-is.

## Deploy on Vercel
1. Push this folder to a new GitHub repo.
2. At https://vercel.com/new, import the repo.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty. Click Deploy.

Or from a terminal: `npm i -g vercel`, then `cd portfolio && vercel --prod`.

## Customize
- Text and links: `index.html`. Colors: the `:root` variables at the top of the CSS.
- Photo: replace `assets/emmanuel.jpg` (keep a portrait shape, about 4:5).
- CV: replace `assets/Emmanuel_Shittu_CV.pdf` (keep the same file name) whenever you update your CV.
- WhatsApp number: edit the `wa.me/234...` links (country code first, no leading 0).
