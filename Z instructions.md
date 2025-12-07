Build me a storefront selling cookies with integrated stripe payments. Make sure to use stripe as the source of truth for my business, including products, customers and orders. Make sure to customer_creation='always' during the checkout to make sure customer objects are always created. 

Do not create users or orders table in my database. Instead rely on the sync stripe customers and charges table.

Keep the app as simple as possible. We need to finish building this within 5 minutes. No admin view. Just a single page displaying my products. 

When you are creating products in Stripe, be sure to upload the photos using multipart/form-data POST request so they are available in the dashboard. 

Then when you are displaying the product, use the .photos field returned by stripe that are sync'ed into the database. 

Do NOT use random image urls. Instead when seeding products to Stripe use the photos I uploaded. 

