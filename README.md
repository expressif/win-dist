# Windows libraries for expressif

Windows VC11 libraries :

## Distributed versions :

| Library       | Version  |
|---------------|---------:|
| Libevent      |   2.0.22 |
| Pecl Libevent |    0.1.x |

---

## Downloads

### x64

| PHP      | Thread Safe | Not Thread Safe |
|----------|-------------|-----------------|
| 7.0      | [download](https://github.com/expressif/win-dist/archive/php-7.0-ts-x64.zip) | [download](https://github.com/expressif/win-dist/archive/php-7.0-nts-x64.zip)

### x86

| PHP      | Thread Safe | Not Thread Safe |
|----------|-------------|-----------------|
| 7.0      | [download](https://github.com/expressif/win-dist/archive/php-7.0-ts-x86.zip) | [download](https://github.com/expressif/win-dist/archive/php-7.0-nts-x86.zip)


---

## Enabling modules :

Edit your php.ini, adding the modules (order matters) :

```ini
extension=php_libevent.dll
```