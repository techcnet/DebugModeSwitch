# Debug Mode Switch for ProcessWire

![GitHub](https://img.shields.io/github/license/techcnet/DebugModeSwitch)
![GitHub last commit](https://img.shields.io/github/last-commit/techcnet/DebugModeSwitch)
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/techcnet)

This module for ProcessWire enables the debug mode to bypass the restriction to install modules. This is useful if you are tired to manually set the debug mode in the configuration.

## Note
Please note that this module doesn't replace the real debug mode in the configuration file **/site/config.php**. With this module you will not receive any errors/notices/warnings like in the real debug mode. It serves only to bypass the restriction to install modules.

## Installation
To install this module you have to enable the real debug mode. After installation you should deactivate debug mode again. To enable the real debug mode, download **/site/config.php** via FTP and open it in a text editor. Look for a line where you can find **$config->debug = false;** change it to **$config->debug = true;** save the file and upload it again. After module installation change it back to **$config->debug = false;**.

!["Real Debug Mode"](https://tech-c.net/site/assets/files/1214/debug-mode.jpg)

For all future module installations, you just have to enable the debug mode in the module settings like described below. After module installation, you should deactivate it in the same way.

## Settings
The settings for this module are located in the menu Modules=>Configure=>DebugModeSwitch.

!["Settings"](https://tech-c.net/site/assets/files/1214/settings.jpg)

## Enable or deactivate debug mode
Set the checkmark **(1)** and click the submit button **(2)** will enable the debug mode **(3)**. The debug mode can be also restricted for superusers only **(4)**.

!["Enable or deactivate debug mode"](https://tech-c.net/site/assets/files/1214/enable.jpg)
