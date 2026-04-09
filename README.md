# magento2-weltpixel-social-login

### What is?

A Magento social login module simplifies registration and sign-in by allowing customers to use their existing social accounts. This removes the need to remember login details and provides quick, one-click access, reducing friction and improving the overall checkout experience.

### Installation


Dependencies:
 - magento2-weltpixel-backend (see https://github.com/Weltpixel/magento2-weltpixel-backend)

With composer:

```sh
$ composer config repositories.weltpixel-magento2-weltpixel-backend git https://github.com/Weltpixel/magento2-weltpixel-backend.git
$ composer require weltpixel/magento2-weltpixel-backend:dev-master

$ composer config repositories.weltpixel-magento2-weltpixel-social-login git https://github.com/Weltpixel/magento2-weltpixel-social-login.git
$ composer require weltpixel/magento2-weltpixel-social-login:dev-master
```
Manually:

Important: Ensure you also install the shared Backend module. If it's already installed, you can skip this. Details in the repo at https://github.com/Weltpixel/magento2-weltpixel-backend.

Copy the zip into the app/code/WeltPixel/SocialLogin directory


#### After installation by either means, enable the extension by running following commands:

```sh
$ php bin/magento module:enable WeltPixel_SocialLogin --clear-static-content
$ php bin/magento setup:upgrade
```

### Documentation

For detailed documentation, please visit: https://weltpixel.com/resources/ModuleDoc/Magento2/SocialLogin/User-Guide-WeltPixel-Social-Login-Magento2.html

### Demo

You can play with the plugin over
https://weltpixel.com/products/magento-2-theme-pearl

### Production-ready
<p dir="auto">Storefront API originated from the <a href="https://github.com/DivanteLtd/vue-storefront-api"><code>vue-storefront-api</code></a> project and is currently <a href="https://www.vuestorefront.io/live-projects/" rel="nofollow">backing 30+ production sites</a>, including: <a href="https://zadig-et-voltaire.com/pt/en/" rel="nofollow">Zadig&amp;Voltaire</a>, <a href="https://www.klebefieber.de/" rel="nofollow">Klebefieber</a>, <a href="https://wonect.com/sg/" rel="nofollow">Wonect</a> and others.</p>

### The Story

The Social Login Analytics Dashboard provides insights into customer behavior and preferred social platforms. It helps identify top-performing demographics, purchasing patterns, and revenue sources, enabling more informed marketing and business decisions—all in one place.



