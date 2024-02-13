[![Build Status](https://travis-ci.org/boomerdigital/solidus_flexi_variants.svg?branch=master)](https://travis-ci.org/boomerdigital/solidus_flexi_variants)

# SolidusFlexiVariants

This extension solves two use cases related to variants.  I call them **Ad Hoc Options** and **Product Customizations**.

### Ad Hoc Options

Use these when have numerous (possibly price-altering) product options and you don't want to create variants for each combination.

You can also restrict certain combinations of options from coexisting.  These are called **Ad Hoc Exclusions**.

### Product Customizations

Use these when you want the ability to provide a highly customized product e.g. "Cut to length 5.82cm", "Engrave 'thanks for the memories'", "Upload my image".  Full control over pricing is provided by the Spree calculator mechanism.

## Version Notes

TODO
I have only tested with V2.0, unsure if compatible with other versions as of yet.

## Installation

    # see the notes in Versionfile if you are using an older version of spree
    gem 'solidus_flexi_variants', github: 'boomerdigital/solidus_flexi_variants', branch: 'master'

    bundle install

    bundle exec rails g solidus_flexi_variants:install

## Examples

Build a 'Hoodie' product using **Ad Hoc Options** and **Product Customizations**

![Hoodie](doc/hoodie.png?raw=true "Title")

Build a 'Mug'  product using **Ad Hoc Options** and **Product Customizations**

![Mug](doc/cup.png?raw=true "Title")

Build a 'Bag'  product using **Ad Hoc Options** and **Product Customizations**

![Mug](doc/bag.png?raw=true "Title")
See the [wiki](https://github.com/jsqu99/spree_flexi_variants/wiki) for more detail.
