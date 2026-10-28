Print N Stick app (installable web app)

1. Put ALL files in this folder on any free static host (HTTPS needed):
   Netlify Drop (app.netlify.com/drop), Cloudflare Pages, or GitHub Pages.
2. Open the website link on your phone.
   Android Chrome: menu > Install app / Add to Home screen.
   iPhone Safari: Share > Add to Home Screen.
3. Real Android APK (optional): paste your website link into pwabuilder.com and download the Android package.

Changing prices, sizes, materials, sheets, text or the admin password:
- Open the app, press the small "Admin" link at the bottom, log in (first password: admin123).
- Edit, then press "Download config.json".
- Upload that file to your host and replace the old config.json. All customers get the new prices.
- Do this once now: change the password in the Security tab and set the WhatsApp number in Pricing.

New admin tabs (Admin link at the bottom of the page):
- Brand: business name and logo (photo is shrunk automatically).
- Products: add shop items with name, category (dropdown), size, price, old price, stock, description and up to 3 photos.
- Categories: add, rename or remove categories. They appear as shop filter buttons and in the product dropdown. Customers add to cart and order on WhatsApp.
- Promotions: banner offers at the top. Add a code and discount % so customers can use it in the cart. Optional end date.
- Features: the highlighted boxes in the "What you get" section.
Photos (product photos and logo) are saved as separate files in the "images" folder, and config.json only holds their file names. This keeps config.json small even with many products.
To publish changes: in Admin press "Download package (zip)", unzip it, and upload config.json plus the images folder to your host (the images folder goes next to index.html). "config.json only" is for text/price changes without new photos.
Old photos that were embedded in config.json are moved to the images folder automatically the next time you press Download package.
Old unused image files stay on your host until you delete them.
The installed app's home-screen icon comes from icon-192.png and icon-512.png (not from the logo you upload in Admin).

