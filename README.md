Лаб. 1 authentication-authorization-identitification

1. Создать 2 виртуальные машины на базе ОС Debian 12
https://www.virtualbox.org/wiki/Downloads https://cdimage.debian.org/debiancd/current/amd64/iso-cd/debian-12.1.0-amd64-netinst.iso
2. Обеспечить между ними сетевой обмен https://www.virtualbox.org/manual/ch06.html
3. Установить keycloak на ВМ 1, произвести первоначальную настройку, добавить realm и
пользователей appadmin, user в него. https://www.keycloak.org/docs/latest/server_admin/
4. Развернуть на ВМ 2 тестовое приложение и подключить его к keycloak
https://kzhekov.medium.com/introduction-to-iam-with-keycloak-7b1127a16e0e
(приложение выбрать самостоятельно)
5. Подключить двухфакторную аутентификацию OTP для защищаемого приложения
https://ultimatesecurity.pro/post/2fa/
https://www.mastertheboss.com/keycloak/how-to-enable-two-factor-authentication-in-keycloak/
