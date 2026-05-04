KALKI VATTHA - live-ready static website package

Files included:
- kalki-vattha-final-live-website.html
- assets/kalki-vattha-logo-tight.jpg
- assets/kalki-vattha-logo.jpg
- assets/kalki-vattha-hero-hoodie.png

How to preview:
1. Open kalki-vattha-final-live-website.html in any modern browser.
2. Test the hero SoundCloud player, 3D try-on studio, product filters, size selector, fit finder, bundle builder, add-to-cart, cart drawer, payment logo tiles, newsletter form and music links.

What has been upgraded:
- Your supplied KALKI VATTHA logo is now used in the nav, hero, origin section and footer.
- The site is positioned as Melbourne operated with worldwide shipping.
- The music story is corrected: Goa trance is described as starting from Goa beach/forest party culture, not as ancient Indian tradition.
- SoundCloud, Spotify, Bandcamp, Parvati Records booking, Instagram, Facebook and Gmail logo links are included.
- Payment logo tiles are included for Stripe, PayPal, Shopify, Afterpay, Apple Pay, Google Pay, Visa, Mastercard, Amex and Klarna.
- The supplied logo is described correctly as lotus and Krishna flute.
- Tailwind CSS is loaded through the CDN with preflight disabled, so it supports utility styling without resetting the custom premium CSS system.
- Gateway-ready checkout logic is included for Stripe, Shopify, PayPal and Afterpay.
- The page includes a homepage SoundCloud player with shopper-facing copy explaining they can play music while browsing, a 360-degree featured Night Temple hoodie image viewer with drag/touch rotation, interactive 3D try-on/customisation studio, distinct hoodie/tee/jacket model treatments, a black/brown/navy launch palette, animated background depth, a sticky buy CTA, scarcity signals and first-visit conversion sections.
- Reference-inspired refinements were added from premium interactive sites: clearer motion cues, visible payment proof, responsive grids, tactile hover depth and stronger trust blocks.

Payment setup:
This is a static HTML storefront, so it cannot securely process card payments by itself. To go live, create hosted checkout/payment links with Stripe Payment Links, Shopify, PayPal or your ecommerce platform, then replace these placeholders inside the JavaScript `checkoutLinks` object:

- REPLACE_WITH_STRIPE_PAYMENT_LINK
- REPLACE_WITH_PAYPAL_CHECKOUT_LINK
- REPLACE_WITH_SHOPIFY_CHECKOUT_LINK
- REPLACE_WITH_AFTERPAY_OR_SHOPIFY_CHECKOUT_LINK

Product setup:
Inside the JavaScript `products` array, replace sample product names, prices, stock labels, sizes and descriptions with your real drop details. Replace placeholder/generated product visuals with real photography when your samples are ready.

Music/research links used:
- SoundCloud: https://on.soundcloud.com/bC4OXgo3Xsho1uKL0y
- Spotify: https://open.spotify.com/artist/5Z7yFcfWDu27jQ1EAVStR5
- Bandcamp: https://farebijalebi.bandcamp.com/
- Parvati Records artist source: https://parvati-records.com/farebi-jalebi/
- Parvati Records booking/contact: https://parvati-records.com/contact/
- Instagram: https://www.instagram.com/farebi_jalebi/
- Facebook: https://www.facebook.com/farebiJalebi
- Goa trance background: https://en.wikipedia.org/wiki/Goa_trance
- Roots of Goa trance reference: https://bibliolore.org/2016/03/31/the-roots-of-goa-trance/

Before publishing:
1. Add live checkout URLs.
2. Replace product placeholders with final products and photos.
3. Connect the newsletter form to Klaviyo, Mailchimp, Shopify Email or Brevo.
4. Add final shipping, returns, privacy and terms policy pages or links.
5. If you move this to Shopify/WooCommerce, use this HTML as the visual and interaction reference, then connect the real platform cart and checkout.
