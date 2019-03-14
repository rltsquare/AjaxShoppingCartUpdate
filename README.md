# AjaxShoppingCartUpdate-Magento2

# Overview

The AJAX Shopping Cart Update for Magento 2 extension has been developed by the product team at RLTSquare. AJAX Shopping Cart Update With this extension, you can update quantity seamlessly and see total price adjustments on the shopping cart page without having to click 'update to cart' button. You can see total price adjustments on the shopping cart page instantly. There are no needless page reloads. There are buttons to increase or decrease the quantity of items on your cart. It is a much simpler approach for updating the products on your cart. Our extension provides many options for settings from the admin.

Here are some of the salient features for the extension:

```
1. AJAX-based technology to let customers update quantity of the products to the cart
2. Automatically updates the price without having to reload the page
3. Buttons to increase and decrease the quantity of items
4. AJAX call to cart, summary and mini-cart to automatically update the price
5. Updates the cart in real-time. 
6. User-friendly and seamless way to update cart
```

## Installation

### Magento® Marketplace

This extension will also be available on the Magento® Marketplace when approved.

### Manually

1. Go to Magento® 2 root folder

2. Require/Download this extension:

   Enter following commands to install extension.

   ```
   composer require rltsquare/ajax-shopping-cart-update
   ```

   Wait while composer is updated.
   
   #### OR
   
   You can also download code from this repo under Magento® 2 following directory:
    
    ```
    app/code/RLTSquare/AjaxShoppingCartUpdate
    ```    

3. Enter following commands to enable the module:

   ```
   php bin/magento module:enable RLTSquare_AjaxShoppingCartUpdate
   php bin/magento setup:upgrade
   php bin/magento cache:clean
   php bin/magento cache:flush
   ```

4. If Magento® is running in production mode, deploy static content: 

   ```
   php bin/magento setup:static-content:deploy
   ```


## Requirements

1. This Magento® extension works on Magento 2.1,2.2 and 2.3 versions. Tested on versions 2.2.5 and above.

2. Tested on different themes specifically Ultimo, Porto and certain custom themes

For details, read our blog:
https://www.rltsquare.com/blog/most-viewed-magento-2-extension/
