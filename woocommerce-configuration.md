# Woocommerce Configuration

> This section will guide how to make the app work with your existing Wordpress website


### Required Setup

As the app is required connect with the Wordpress site and WooCommerce plugin via Rest API, please refer to the 
<a target="_blank" href="http://woocommerce.github.io/woocommerce-rest-api-docs">Rest Document</a> for more detail info.

### Enable Worpdress setting

#### Permalink URL

Go to <b>Common Setting</b>, change the URL to `post name`, this is required for the setting otherwise some images could not loading.

### App Config

Go the storexpro project folder open the file: `src/config.js` and follow below steps to setup the app.

- Change your woocommerce `SITE_URL`
- Change your consumer key `WC_CONSUMER_KEY`
- Change your consumer secret `WC_CONSUMER_SECRET`

 
 ### Install Plugins

Install required plugins for user auth and payments features in the applic 

https://github.com/kayaui/Storex-Pro-Docs/raw/master/wordpress-plugins/json-api.zip
https://github.com/kayaui/Storex-Pro-Docs/raw/master/wordpress-plugins/json-api-user.zip
https://github.com/kayaui/Storex-Pro-Docs/raw/master/wordpress-plugins/woocommerce-gateway-paypal-express-checkout.zip

