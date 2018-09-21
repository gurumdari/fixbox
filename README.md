# FixBox
FixBox is a system that manages domains and accounts in Postfix and Dovecot environments. If you are filtering spam with Apache SpamAssassin, you can also set up a required score and manage whitelists and blacklists. FixBox also provides automatic installation and integration of RainLoop, a Webmail client server that can be built freely with a modern UI.

<p align="center"><img src="images/architecture_en.png?raw=true" width="409" /></p>

FixBox is implemented as a responsive web, so it can be used easily in PC as well as mobile environment.

### Guide
To know more details, you can visit the official FixBox site below:

[https://fixbox.gurumdari.com](https://fixbox.gurumdari.com)

### Support Environment
FixBox is a PHP based web application that can be installed on a Linux server environment that supports PHP 7.0 or later. It should be an environment in which mail servers are built in advance with Postfix and Dovecot. The Mail account must be configured as a virtual account to be managed by MySQL (including MariaDB). Client PC environment does not require installation of a separate client program, and it can be used immediately when connecting PoPoPa installed server anytime and anywhere through Web browser supporting HTML5. However, Internet Explorer only supports 10 and 11 versions.

<p align="center"><img src="images/html5.png?raw=true" width="352" /></p>

<p align="center"><img src="images/ie10_11.png?raw=true" width="352" /></p>

### Multilingual support
FixBox provides a language pack function that automatically displays the language according to the language set in the Web Browser. Currently, Korean, English, and Japanese are built in. If necessary, language packs can be created and used. It provides functions that can be used only in a specific language, regardless of the language set in the Web Browser, as system settings and personal settings.

<p align="center"><img src="images/languages.png?raw=true" width="399" /></p>

### Donation
FixBox is a free software made with Jnode Framework. If you use FixBox and Jnode Framework, and take some benefits, please donate for PoPoPa and Jnode Framework. Through your donation, FixBox and Jnode Framework will be better. Also, I hope to see more free software and donation culture.

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6YYMTECUZXM9S)

### Read in anther language
[Korean (한국어)](https://github.com/gurumdari/fixbox/blob/master/README_ko.md)