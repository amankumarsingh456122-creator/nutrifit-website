# NutriFit Netlify Storefront

## Deploy
1. Extract this ZIP.
2. In Netlify, choose **Add new site → Deploy manually**.
3. Drag the extracted `nutrifit-netlify` folder (or its contents) into the deploy area. Alternatively push the folder to GitHub and import the repository.
4. In Netlify, open **Forms** and ensure form detection is enabled. Trigger a new deploy after enabling form detection if required.
5. Submit a test order from `/checkout.html`. Check Netlify → Forms → `nutrifit-order` for the submission.

## Pages
- `/` home
- `/shop.html` product listing
- `/product.html?id=egg-oats` product detail
- `/cart.html` cart
- `/wishlist.html` wishlist
- `/checkout.html` order request form
- `/thank-you.html` confirmation
- `/our-story.html` about
- `/contact.html` contact form

## Important
- This is a static demand-validation storefront, not a full inventory/order-management backend.
- Cart and wishlist are stored in the visitor's browser.
- Netlify Forms captures form submissions in the Netlify dashboard. Configure notification emails in Netlify Forms settings.
- The order request includes product names, quantities, estimated totals and customer details. No online payment is collected.
- Demo prices, protein and calorie figures are placeholders. Replace with verified data before publishing.
- Product visuals are typographic/emoji placeholders; replace with actual NutriFit pack and ingredient photographs.
- Netlify's free plan limits and form submission quotas apply; check current plan terms.
- Do not use this prototype to sell perishable foods until food safety, cold-chain, licensing, delivery and customer support processes are ready.
