# OpenCart3.0_Plugin
MOLPay OpenCart Shopping Cart Plugin v3.0

<img src="https://user-images.githubusercontent.com/38641542/39344583-da87c94e-4a15-11e8-9ad4-b2b52165cfe0.jpg">

MOLPay Seamless Integration plugin for OpenCart 3.0.x develop by MOLPay technical team.

Supported version
-----------------
New Update

- Opencart Seamless Plugin
- OpenCart version 3.x

Plugin Releases
-----------------
**Seamless Integration**
* [MOLPay Seamless Plugin for OpenCart Version 3.0 (Journal2 Checkout)](https://github.com/MOLPay/Magento_Plugin/tree/Version-2.2.x/MOLPay%20Seamless%20Plugin%20for%20Magento%202.1.x%202.2.x/DefaultCheckout)

Notes
-------------
MOLPay Sdn. Bhd. is not responsible for any problems that might arise from the use of this module. 
Use at your own risk. For any query or assistance, please email support@molpay.com

If you have existing plugin, please backup your Opencart folder first

Installations
-------------
1. Download from [opencart3.0_seamless_wAccType.zip](https://github.com/MOLPay/OpenCart3.0_Plugin/blob/master/opencart3.0_seamless_wAccType.zip) or clone this repository. Copy all the file and paste it at your opencart root directory.  
`<OpenCart_DIR>/admin/*`  
`<OpenCart_DIR>/catalog/*`

2. Login to OpenCart administration, click on extension menu and click on Payments submenu.

3. You will see list of payment method available on your OpenCart. Click on [Install] link for MOLPay Online Payment Gateway (Visa, MasterCard, Maybank2u, MEPS, FPX, etc) to install this module into your online store.  

4. After you’ve successfully install this module, you need to click on [Edit] link for MOLPay Payment Gateway option to configure this payment module in your OpenCart online store.

5. Fill in your MOLPay Merchant ID & MOLPay Verify Key into the respective fields.

6. Log in your merchant account at https://portal.molpay.com. Click Transaction > Transaction Settings > Endpoint setting.
  
  ``Return URL : http://xxxxxxxxxxxxxx/index.php?route=extension/payment/molpay/return_ipn``

  ``Notification URL : http://xxxxxxxxxxxxxx/index.php?route=extension/payment/molpay/notification_ipn``

  ``Callback URL : http://xxxxxxxxxxxxxx/index.php?route=extension/payment/molpay/callback_ipn`` 
  
  *Replace xxxxxxxxxxxxxx with your shoppingcart domain

7. Save the configuration and done.

Contribution
------------
You can contribute to this plugin by sending the pull request to this repository.

Issues
------------
Submit issue to this repository or email to our support@molpay.com

Support
-------
Merchant Technical Support / Customer Care : support@molpay.com <br>
Sales/Reseller Enquiry : sales@molpay.com <br>
Marketing Campaign : marketing@molpay.com <br>
Channel/Partner Enquiry : channel@molpay.com <br>
Media Contact : media@molpay.com <br>
R&D and Tech-related Suggestion : technical@molpay.com <br>
Abuse Reporting : abuse@molpay.com
