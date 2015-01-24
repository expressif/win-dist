# Windows libraries for expressif

Windows VC11 libraries `THREAD SAFE` version :

## Contents

- `PHP`   : **5.6** TS
- `ARCH`  : **x64**

---

| Library       | Version  |
|---------------|---------:|
| Libevent      |   2.0.22 |
| Pecl Libevent |    0.1.0 |
| Pecl Propro   |    1.0.0 |
| Pecl Raphf    |    1.0.4 |

---

## Enabling modules :

Edit your php.ini, adding the modules (order matters) :

```ini
extension=php_libevent.dll
extension=php_propro.dll
extension=php_raphf.dll
extension=php_http.dll
```