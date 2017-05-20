# Среда для разработки проекта Scatar

Настройки для Vagrant и Ansible для того, чтобы быстро развернуть среду для разработки проекта Scatar.

## Системные требования

 * Ubuntu 16.04 64-bit
 * Vagrant 1.8.6
 * VirtualBox 5.1
 * Ansible 2.3.0
 * Git 2.7.4

## Использование

Примонтировать директорию с исходным кодом
```bash
sudo mount -t cifs -o uid=ilya,gid=ilya,password=vagrant,username=vagrant,iocharset=utf8,sec=ntlm //192.168.34.10/www ./www
```

Запустить приложение в режиме разработчика
```bash
php artisan serve --host=0.0.0.0
```