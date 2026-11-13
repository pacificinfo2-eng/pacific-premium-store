# Pacific Premium — free static electronics store

This is a static HTML/CSS/JavaScript storefront. It includes product search, category filters, sorting, a cart, and WhatsApp order-message generation.

## 1. Configure your store

1. Open `index.html` in a text editor.
2. Find `const STORE_WHATSAPP = "91XXXXXXXXXX";`.
3. Replace it with your WhatsApp number in international format, digits only. Example for an Indian number: `919876543210` (country code 91 + 10-digit mobile number).
4. Edit the `products` array below it. Change product names, categories, prices, ratings, and emoji. The displayed catalogue is sample content.
5. Change `Pacific Premium` to your store name in the page title, header, and footer if desired.

## 2. Test locally

Double-click `index.html` to open it in a browser. Add an item to the cart, enter a name and address, and test the WhatsApp button. It opens WhatsApp with a pre-filled message; the customer must press Send.

## 3. Publish free with GitHub Pages

1. Create a free account at https://github.com/.
2. Create a new public repository, for example `electromart-store`.
3. Upload `index.html` to the repository root (the top-level folder).
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then click **Save**.
7. Wait a few minutes. GitHub will show your public website address in the Pages section, usually `https://YOUR-USERNAME.github.io/electromart-store/`.

GitHub Pages hosting is free for public repositories. A custom domain is optional and usually costs money; use the free `github.io` address to keep costs at zero.

## Important limitations

- No database or admin panel: edit the product array in `index.html` to update inventory.
- No online card/UPI checkout: orders are sent to WhatsApp. Agree payment and delivery directly with the customer.
- No customer accounts, automated stock tracking, or order history.
- Product photos are represented by emoji in this starter so it works without image hosting or external dependencies. You can replace each emoji with an `<img>` element and a hosted image URL later.
- The store does not verify inventory, calculate shipping, or collect payments. Confirm all order details manually.
