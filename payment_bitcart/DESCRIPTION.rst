Bitcart Payments
##################

Accept cryptocurrency payments in BTC, LTC, BCH, ETH, BNB, XMR cryptocurrencies and arbitrary ERC20 and BEP20 tokens with no middleman

Features
********

- Quick and easy setup: only your Bitcart instance needed
- Marking orders as paid automatically and adding paid amounts in selected currency
- Fast and light cryptocurrency checkout
- Full integration with your Bitcart instance's admin dashboard - each invoice in odoo will have corresponding invoice in Bitcart


FAQ
***

How can I find my instance URL?
-------------------------------

You should either set up your own instance or use third-party hosting, please read Bitcart docs.

How can I configure invoice expiration time?
--------------------------------------------

All invoice and store related settings are configured in your Bitcart instance's admin panel


Integration Requirements
************************

This version requires the following:

-  Your Odoo instance
-  Running Bitcart instance

Plugin Configuration
********************

After you have enabled the Bitcart plugin, the configuration steps
are:

1. Enter your admin panel URL without slashes. If deployed via configurator, you should use your instance URL with ``/admin`` at the end
2. Enter your merchants API URL without slashes. If deployed via configurator, you should use your instance URL with ``/api`` at the end
3. Enter your store ID (click on id field in Bitcart’s admin panel to
   copy id)

Enjoy!