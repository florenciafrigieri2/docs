---
slug: disable_odoo_online
title: Remove odoo.com Bindings
---
This module deactivates all bindings to odoo.com that come with the standard code:

* update notifier code is deactivated and the function is overwritten. It's deactivated only in community version, because 

  [it's not legal](https://www.odoo.com/documentation/user/12.0/legal/terms/enterprise.html#customer-obligations)

   to deactivate notifier code in odoo enterprise
* apps and updates menu items in settings are hidden inside Technical Parameters
* documentation, support and odoo.com account are removed from user menu
