Magento-Bitcoin
===============

Bitcoin extension for Magento Commerce

Redirect issues
===============

If you run into trouble redirecting users to theBitcoin payment page, 
make sure to copy the extension's layout and template files to your 
custom theme. This is only necessary if your custom theme lives outside
of base/ or default/ themes.

Copy:
/app/design/frontend/default/default/template/appmerce/bitcoin/*.*
/app/design/frontend/default/default/layout/appmerce/bitcoin/*.*

To:
/app/design/frontend/MYTHEME/MYSUBTHEME/template/appmerce/bitcoin/*.*
/app/design/frontend/MYTHEME/MYSUBTHEME/layout/appmerce/bitcoin/*.*

(Change 'MYTHEME/MYSUBTHEME' accordingly.)
