## sysPass Authenticator Plugin

---

Plugin to use two factor based authentication with applications that generate TOTP codes like Google Authenticator, AndOTP or KeepassXC

Please, select the correct branch in order to download a sysPass compatible version:

* sysPass v3.1 --> Master or v2.1 branch
* sysPass v3.0 --> 2.0 branch
* sysPass v2 --> 1.0 branch 

---

### v2.1 Installation

This version is only compatible with **sysPass v3.1** and it needs to be installed through **composer**.

Please select the installation method depending on the instance type:

* If you are running a **non-Docker** based instance:

```composer require syspass/plugin-authenticator:^v2.1```

* If you are running a **Docker** based instance, set `syspass/plugin-authenticator:^v2.1` value within an environment variable called `COMPOSER_EXTENSIONS`.
 
---

### v2.0 Installation

This version is only compatible with **sysPass v3** and it needs to be installed through **composer**.

Please select the installation method depending on the instance type:

* If you are running a **non-Docker** based instance:

Before plugin installation install some libs:

```composer require phpseclib/phpseclib php-di/php-di```

Then install plugin

```composer require syspass/plugin-authenticator:^v2.0```

* If you are running a **Docker** based instance, set `syspass/plugin-authenticator:^v2.0` value within an environment variable called `COMPOSER_EXTENSIONS`.
 
---

### v1.0 Installation

Please download the v1 branch files and unpack them into `.../inc/Plugins` directory.

---

https://syspass.org

https://demo.syspass.org

https://doc.syspass.org

https://github.com/sysPass/plugin-Authenticator
