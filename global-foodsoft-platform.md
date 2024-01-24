---
layout: single
title: Global Foodsoft platform
sidebar:
  nav: links
---
{% include toc %}

When in 2017 the hosting by [about:source](https://www.aboutsource.net/)
[ended](/2017/04/17/foodsoft-hosting-wird-eingestellt) after [ten years](/2007/06/22/foodsoft-portal-startet/),
members of food cooperatives of three countries [came together](/2017/07/14/open-community-driven-foodsoft-platform/)
to form a global hosting platform. Since January 2024 the tech collectiv [rokoli](https://roko.li) has been operating
the platform.

# Foodsoft

The platform provides the main Foodsoft version, complete with email replies and standard
plugins. The web interface supports different [languages](https://github.com/foodcoops/foodsoft/tree/master/config/locales).
There is also a [shared database](#shared-database) of suppliers for some German
and Dutch suppliers (in addition to those managed by your own cooperative).

# Costs

The total costs for maintaing the platform are shared by all cooperatives. Every cooperative can use up to 5 free Foodsoft
user accounts. For each additional Foodsoft user account a fee of 1 € net per month is charged.

# Request a new instance

Please read at first our [Terms of service](/tos) before you request a new instance. If you agree to it send an email
(in German or English) to [hosting@foodcoops.net](mailto:hosting@foodcoops.net) with the following information:

   * Name of your foodcoop
   * Short name (for use in the web address)
   * Contact person (name + email address)
   * Fallback contact person (name + email address)
   * Homepage (if any)

It is also possible to customize some [settings](https://github.com/foodcoops/foodcoops.net/blob/master/Ansible/roles/configure-foodsoft/Configuration.md) for your Foodsoft instance.

After we finished to set up your instance you will receive an email with all the details.

# Support

If you have a question about using the Foodsoft, you can check the [forum](https://forum.foodcoops.net) if someone already has answered
your question. If not just create a new topic. Or maybe the [support wiki](https://github.com/foodcoops/foodsoft/wiki/Support) has what you need already.

In case you have an issue with the global platform, you can send an email to
[hosting@foodcoops.net](mailto:hosting@foodcoops.net).

# Helping out

We're currently looking for people who want to write new documentation for the Foodsoft.
Feel free to email either support address.

# Shared database

Some suppliers are used by several cooperatives and have automated article updates by means
of a shared database. Each food cooperative can make a selection of its articles, and synchronize
prices before opening an order. [Read more on the wiki](https://github.com/foodcoops/foodsoft/wiki/Shared-database).

The following suppliers are available in the shared database:

* DE - [Bio Antakya](http://www.bio-antakya.de): organic wholesale retailer. Delivery to allmost all federal states.
* DE - [Naturkost Elkershausen](https://www.naturkost-elkershausen.de): organic wholesale retailer.
* DE - [Terra Naturkost](https://www.terra-natur.com/): organic wholesale retailer.
* NL - [BioRomeo](http://www.bioromeo.nl/): farmer collective with organic fruits and vegetables from Flevoland.
* NL - [Odin](https://www.odin.nl/): organic wholesale cooperative for dry foods, cheese and some household goods.

Please note that your Foodcoop needs to be an approved customer by any of these suppliers to place an order.
