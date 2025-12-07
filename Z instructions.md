Build me a storefront selling cookies with integrated stripe payments. 

Connect to Stripe as soon as possible.

Make sure to use stripe as the source of truth for my business, including products, customers and orders. Make sure to customer_creation='always' during the checkout to make sure customer objects are always created. 

Do not create users or orders table in my database. Instead rely on the sync stripe customers and charges table.

Keep the app as simple as possible. We need to finish building this within 5 minutes. No admin view. Just a single page displaying my products. 

When you are creating products in Stripe, be sure add the raw image url from Replit for the uploaded image so they are available in the Stripe dashboard.

URLs should be in the form of https://xxxx.riker.replit.dev/assets/xxxxxx.png

Then when you are displaying the product, use the .photos field returned by stripe that are sync'ed into the database so that everything is consistent.

Do NOT use random image urls. Instead when seeding products to Stripe use the photos I uploaded. 

No advanced functionalities like filters. 

All cookie selection should be above the fold. 

Once I add an item to the cart it should immediately pop up the dialog with my cart allowing me to checkout right away.

Don't any any "powered by Stripe" branding to my shop