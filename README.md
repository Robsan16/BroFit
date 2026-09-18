# BRO FIT Men's Wear Website

Premium static e-commerce website built with HTML5, CSS3, JavaScript, jQuery and Foundation 6 Sites.

## Open the site

Open `index.html` in a browser. All framework, script and image assets are stored inside this project; the Poppins typeface is loaded from Google Fonts.

## Update store details

Edit the clearly marked `BROFIT_CONFIG` block near the top of `assets/js/app.js`:

- `whatsappNumber` - country code and number without `+` or spaces
- `phone`
- `instagramUrl` and `instagramHandle`
- `address`
- `businessHours`
- `shippingNote`
- `exchangeWindow`

Products are managed once in `assets/js/products.js`. Product cards, search, filters, wishlist and product pages all read from that file.

## Before production launch

- Replace placeholder store details in `BROFIT_CONFIG`.
- Replace placeholder product photography with final BRO FIT product images.
- Review shipping, exchange, privacy and terms copy with the business owner.
- Replace relative canonical and Open Graph URLs with the final public domain.
- Connect the contact form, accounts, checkout and order tracking only through a secure backend.

## Placeholder photography

The local product images are temporary Unsplash photography downloaded from `images.unsplash.com`. Confirm final production usage and attribution requirements, or replace them with owned BRO FIT photography before launch. The supplied `RObi.png` brand artwork is stored as `assets/images/banners/bro-fit-coming-soon.png` and used across the site.
