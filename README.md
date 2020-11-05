#UC Attribute Option User Interface

##COMPATIBILITY
Drupal 7.x Ubercart 3.x

This module provides an advanced way of managing attribute options. It allows you to view all pages that are using the attribute and make global adjustments to the option(s) for an attribute.

It takes a Global -> Product approach where you can set a price on the store > product > attribute > option and the AOUI will show you this information. You can then choose to use that default price for all other pages with the same option, that way any updates to that default option will reflect on all subsequent pages. If you want to override it per page, then you can simply set a different value and have a mixmatch between pages.

##INSTALLATION
Install in the usual sites/all/modules folder

##SETTINGS
Settings can be found at:
* Home » Administration » Store » Products » Attributes
* /admin/store/products/attributes/aoui
Note: The one setting to pay attention to is: "Autohide disabled options on the Option edit page". If you have a lot of attributes or options, having this enabled is really nice.

##USAGE
1) Create an attribute with several options
2) View an option either from the store > product > attribute > option menu or from any products edit -> options page
3) Click on the [Name] link of the option to view the AOUI page.

Note: This modules UX isn't super hard to understand, but does take a little while to wrap your head around. Spend some time getting familiar with it.
