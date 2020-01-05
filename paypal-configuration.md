# Get Started

> This section will help you walk through setup PayPal payment gateway.

### Enable PayPal in Wordpress

Go to wp-admin. Click settings under WooCommerce menu. Click Payment tab and enable paypal payment.

<img src="https://github.com/kayaui/Storex-Pro-Docs/blob/master/img/paypal_enable.png" width="464" height="288">


### Create PayPal app in developer.paypal.com

If you haven’t created a paypal sandbox account, make sure you do that by heading over to: https://developer.paypal.com/developer/accounts/

<img src="https://github.com/kayaui/Storex-Pro-Docs/blob/master/img/paypal_index.png" width="650" height="264.5">

We will be creating two sandbox accounts:

1. Paypal Merchant Account: Used to accept payment from the end user.
2. Paypal Personal Account: Used to make payment to the merchant account.

Next, we need to create a REST API app at paypal that will be used to setup paypal at our backend. Make sure you select the paypal merchant account you created above while creating the REST app. 

Get your client id and secret keep it in source of `PayPalGateway/app.js` file.

<img src="https://github.com/kayaui/Storex-Pro-Docs/blob/master/img/paypal_file.png" width="816" height="111">
 
