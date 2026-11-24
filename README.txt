SAKA KLAPA WEBSITE — UPDATED IMAGE-INTEGRATED VERSION

1. Keep index.html and the assets folder together.
2. Open index.html in a browser to preview (internet is required for the React/font CDN links).
3. The website includes default photos for the homepage, About Us, sourcing, quality and all four product cards.
4. Every product's Barcode / Label Image now displays the SAME generic sample barcode label by default. This is dummy visual data for layout/demo purposes only; it is not a registered product barcode and must not be used for retail scanning, shipping or compliance.
5. In the Products page or product detail page, use Replace label to upload a real product-specific label later. Uploaded labels override the shared sample for that product only. Remove returns that product to the generic sample label.
6. Product photo and label uploads remain stored in the current browser only. To make future uploads visible to all visitors, connect cloud storage (e.g. Supabase Storage or Cloudinary) and add administrator authentication.

Do not separate index.html from the assets folder; the relative image paths depend on it.
