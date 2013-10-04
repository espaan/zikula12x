zikula12x
=========

The legacy Zikula 1.2.x branch.

Notice for the upgrade to 1.2.10
--------------------------------

In addition to the patch you have to rename the document.location variables in your modules:

* document.location.entrypoint => Zikula.Config.entrypoint
* document.location.ajaxtimeout => Zikula.Config.ajaxtimeout
* document.location.pnbaseURL => Zikula.Config.pnbaseURL
 
See also the wiki page on upgrading from Zikula Core 1.2.9 to the unofficial Zikula Core 1.2.10:
https://github.com/espaan/zikula12x/wiki/Upgrade-procedure-from-the-Zikula-Core-1.2.9-to-the-Zikula-Core-1.2.10
