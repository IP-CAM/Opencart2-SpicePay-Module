Opencart2 SpicePay Module

Important: Module works with Opencart 2.0.x - 2.2.x. Is not compartible with Opencart 2.3.x.

Installation:

1. Download plugin and save it to local disk. No need to unpack.

2. Go to Opencart2 Admin -> Extension Installer -> Upload.

3. Choose file with Spicepay module (opencart20.ocmod.zip). 

4. If you get FTP error message, may be you need FTP fix for your installation (read more https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=18892). 
If you get file permission error, please check that all opencart2 fileas are owned by user "www-data".

5. If installation was succesful, go to Extensions -> Payments. Find SpicePay module in the list. Enable it by clicking button with "+" sign.
 
6. Set module settings:  
SpicePay site ID:  add new site on https://www.spicepay.com/tools.php, set in module settings site ID.
Spicepay Callback Secret: - set the same random secret string at when adding site and in opencart2 spicepay module settings. 
Order Status after pay: - Complete
Status: enabled.
Result URL: http://your-site.com/index.php?route=payment/spicepay/callback
Success URL: http://your-site.com/index.php?route=checkout/success
Fail URL: http://your-site.com/index.php?route=checkout/failure

Find more info on https://www.spicepay.com


SpicePay Team