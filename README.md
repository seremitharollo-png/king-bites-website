# King Bites Grill (demo site)

## Files
index.html, menu.html, about.html, gallery.html, contact.html  – the 5 pages
css/style.css  – all styling (colours are variables at the top)
js/config.js   – EDIT THIS: WhatsApp number, phone, email, address, hours, socials, menu, prices, reviews, gallery
js/main.js     – builds header/footer/menu/etc. from config.js (no need to edit)

## Run locally
Double-click index.html, or from this folder run: python3 -m http.server 8000  then open http://localhost:8000

## Reuse for a client
1. Edit js/config.js (whatsapp = digits only, e.g. 27821234567).
2. Update <title>/description in each page and the JSON-LD block in index.html.
3. Add real photos via the image fields in config.js.
