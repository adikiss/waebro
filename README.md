# waebro
# WAEBRO Notif - Whatsapp Email Broadcast and Woocommerce Whatsapp Notification

== Description ==

WAEBRO Notif is a WordPress plugin that functions to send broadcast messages in the form of WhatsApp messages and email messages. Additionally, it can also send WhatsApp notification messages when there is a change in the order status in WooCommerce.

== Introduction ==

All in one plugin for Broadcast and notification whatsapp

== Features ==

* WhatsApp Broadcast
* Email Broadcast
* WhatsApp notification messages when there is a change in WooCommerce order status
* Device Management
* Contact Management

Broadcasts are executed using their own cron URL, not wp-cron.php.  
WhatsApp messages are sent using the Whacenter API, https://whacenter.com/ 
with the option to add other APIs in the future.  
Email messages are sent using active SMTP 
via the `wp_mail()` function, 
compatible with any SMTP plugin.  
Contacts can be input manually, 
retrieved directly from WordPress users, or WooCommerce users.

URL CRON = https://yoururl.com/wp-json/wa-broadcast/v1/trigger-cron?secret=12345

you can change the secret in menu setting

== Required Plugins ==

* Woocommerce
* SMTP Plugins

== Installation ==

= Minimum Requirements =

* PHP 5.6 or higher is recommended
* WordPress 3.0.1 or higher is recommended

= Steps to install the plugin =

To install the plugin, follow the below steps:

Step 1: Log in to your WordPress dashboard. 

Step 2: Navigate to Plugins and select Add New. 

Step 3: Upload plugin file

Step 4: click on “Install Now”.

Step 5: After installation, click “Activate” to activate the plugin. 



== Changelog ==

 
= 1.0 =
 * Whatsapp Email Broadcast and Woocommerce Whatsapp Notification
 

