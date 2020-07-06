=== Mobipaid ===

Contributors: mobipaid
Tags: credit card, mobipaid, google pay, apple pay, nedbank, payment method, payment gateway
Requires at least: 2.3.0
Tested up to: 2.3.5
Requires PHP: 7.2
Stable tag: 1.0.0
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Payments over multiple channels

== Description ==

= Because you want more than just a shopping cart experience =

* Take payments online and offline
* Use your preferred merchant service provider
* Promote directly on Facebook, LinkedIn and Twitter

= Changing the way you take card-not-present payments. =

Mobipaid is a single card-not-present payment platform that allows you to accept payments in a variety of ways: SEPA, Paypal, Credit/Debit Card, Nedbank EFT, google pay, apple pay and more. Add Mobipaid to your shopping cart for easy and secure payments during checkout, or use your Mobipaid portal to deliver payment requests to your customers using text messaging (SMS), email, social media, and QR codes.

Mobipaid is the best payment solution available for merchants who need payment flexibility, or if your business has grown beyond just eCommerce and the service you offer requires you to take payments anywhere, anytime.
 
== Features ==

* Accept payments via Mobipaid.
* Partial / Full refund.
 
== Localization ==

* English (default) - always included.
* Arabic (ar)
* Danish (da_DK)
* German (de_DE)
* English(US) (en_US)
* Spanish(Spain) (es_ES)
* Finnish (fi)
* French (fr_FR)
* Indonesian (id_ID)
* Italian (it_IT)
* Japanese (ja)
* Korean (ko_KR)
* Dutch (nl_NL)
* Polish (pl_PL)
* Portuguese(Portugal) (pt_PT)
* Russian (ru_RU)
* Swedish (sv_SE)
* Turkish (tr_TR)
* Chinese(China) (zh_CN)

== Installation ==

Note: Magento 2.3.0 - 2.3.5 must be installed for this plugin to work.

1. copy file from src directory to your magento2 root directory.
2. go to your magento2 root directory.
3. run this command :
   - php bin/magento module:enable Mobipaid_Mobipaid
   - php bin/magento setup:upgrade
   - php bin/magento setup:di:compile
   - php bin/magento setup:static-content:deploy
4. clear cache
5. setting folders and files permission.

How to reindex on magento2 :
1. go to your magento2 root directory.
2. run this command : php bin/magento indexer:reindex

How to update extension on magento2 :
1. copy file from src directory to your magento2 root directory.
2. go to your magento2 root directory.
3. run this command :
   - sudo rm -rf var/generation/*
   - sudo rm -rf pub/static/*
   - php bin/magento setup:upgrade
   - php bin/magento setup:static-content:deploy
4. setting folders and files permission.
5. clear cache.

How to deploy static content language :
1. go to your magento2 root directory.
2. run this command :
   - sudo rm -rf pub/static/*
   - php bin/magento setup:static-content:deploy
   - php bin/magento --ansi setup:static-content:deploy {language code}
     for example germany language :
	   - php bin/magento --ansi setup:static-content:deploy de_DE
3. setting folders dan files permission.


== Frequently Asked Questions ==

= Does this require an SSL certificate? =

Yes! In Live Mode, an SSL certificate must be installed on your site to use Mobipaid.

= Does this support both production mode and sandbox mode for testing? =

Yes, it does - production and sandbox mode is driven by the API Access keys you use.

= Where can I can get support? =

You can contact developer with this [link](https://mobipaid.com/contact/).

== Screenshots ==

1. Mobipaid title.
2. The settings panel used to configure Mobipaid.
3. Checkout with Mobipaid.
4. Mobipaid payment page.

== Changelog ==

= 1.0.0 2020-07-06 =
* Initial release
