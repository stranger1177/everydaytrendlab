# EverydayTrendLab affiliate website

A responsive, static HTML landing page for EverydayTrendLab. It includes:
- Mobile-friendly layout
- Product cards for the fitness products and LED rope light discussed
- Category filters and product search
- Placeholder Amazon affiliate links
- Affiliate disclosures
- No backend or build process required

## Before publishing

1. Open `index.html` in a browser to preview the website.
2. Replace each product button's `href="https://www.amazon.in/"` with the full tagged Amazon Associates URL for that exact product.
3. Replace the emoji image placeholders with product images you own or are permitted to use. Keep image rights and Amazon Associates content rules in mind.
4. Verify product names and every feature against the current product listing.
5. Keep the affiliate disclosure visible.
6. Add your published website URL to the Sites list in Amazon Associates Central and verify compliance with the current program policies.
7. Publish the folder using GitHub Pages, Netlify, or another static hosting service.

## Add a product image

Replace this:
```html
<div class="product-image"><div class="image-placeholder"><span>💗</span><strong>Thigh Exerciser</strong><small>Replace with an approved product image</small></div></div>
```

With this (place your image in the `images` folder):
```html
<div class="product-image">
  <img src="images/thigh-exerciser.jpg" alt="Adjustable inner and outer thigh exerciser">
</div>
```

Use only images you own or are authorized to use. Do not copy Amazon images or scrape Amazon listings unless the current Associates rules expressly permit the method.

## Add your tagged affiliate links

Search for `href="https://www.amazon.in/"` in `index.html`. Replace each occurrence with the tagged URL generated for the corresponding product in Amazon Associates Central / SiteStripe. Do not use one product's affiliate URL for another product.

## Publish quickly with Netlify

1. Visit https://app.netlify.com/drop
2. Sign in if prompted.
3. Drag the unzipped `EverydayTrendLab` folder onto the page.
4. Netlify will provide a public URL.
5. Open that URL on your phone and test every button.
6. Add the final URL to your Instagram bio and to your Amazon Associates account's website list.

Hosting provider workflows can change; follow the current on-screen instructions.

## Notes

- The product buttons are intentionally placeholders and will show an alert until replaced with your own tagged links.
- This site does not check live prices or inventory.
- This site is a static website; it does not collect user data or require a backend.
