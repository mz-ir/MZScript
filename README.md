# MZScript

Mirror for <https://greasyfork.org/en/scripts/1752-mzscript-por-ccc-vader-serbini-ini>

## Modified Version

If you installed [Mazyar](https://greasyfork.org/en/scripts/476290-mazyar) too, some features of MZScript might not working.  
Please update your MZScript by this version.

Open TamperMonkey Dashboard, go to `utilities` tab and insert link below in 'Import From Url' box and install or reinstall it.

`https://raw.githubusercontent.com/mz-ir/MZScript/modified/index.js`

## Refactored Version

MZScript tries to load JQuery but it seems redundant. ManagerZone itself requires JQuery for its functionality.  
This version tries to use the loaded JQuery.

`https://raw.githubusercontent.com/mz-ir/MZScript/refactor/index.js`
