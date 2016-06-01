# prestashop_eiinstallmodulescli
Install prestashop module from the commande line or a navigator

=======
This module is deprecated and will not be updated anymore
In order to use CLI with prestashop you can use the module Prestashop Console :
https://github.com/nenes25/prestashop_console
=======

How to use it ( CLI Mode )
----

Example with prestashop module "productscategory"

Go into the directory of the module eiinstallmodulesi

install
<pre>
	php install_module.php module_name=productscategory
</pre>
  or
<pre>
	php install_module.php module_name=productscategory  action=install
</pre>

uninstall
<pre>
	php install_module.php module_name=productscategory  action=uninstall
</pre>

enable
<pre>
	php install_module.php module_name=productscategory  action=enable
</pre>

disable
<pre>
	php install_module.php module_name=productscategory  action=disable
</pre>

check status
<pre>
	php install_module.php module_name=productscategory  action=status
</pre>

How to update Configuration ( CLI Mode )
----

You can also set Prestashop Configuration Values

Example for Google Analytics

Configure Analytics Key
<pre>
php install_module.php mode=configuration key=GA_ACCOUNT_ID value="MY-KEY"
</pre>

Delete Key
<pre>
php install_module.php mode=configuration key=GA_ACCOUNT_ID action_conf=delete
</pre>

Get Key
<pre>
php install_module.php mode=configuration key=GA_ACCOUNT_ID action_conf=get
</pre>




