zikula12x
=========

The legacy Zikula 1.2.x branch.

Notice for the upgrade to 1.2.10
--------------------------------

In addition to the patch you have to rename the document.location variables in your modules:

* document.location.entrypoint => Zikula.Config.entrypoint
* document.location.ajaxtimeout => Zikula.Config.ajaxtimeout
* document.location.pnbaseURL => Zikula.Config.pnbaseURL
