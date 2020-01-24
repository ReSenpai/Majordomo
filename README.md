## Тренировочное задание

### Суть задания
 
1. На предоставленном серевере необходимо установить Nginx  
2. Nginx должен выступать в роли прокси перед Apache2 (с модулем PHP версии 5.X) и
PHP-FPM версии 7.Х.
3. Настроить 2 сайта с использованием указанных CMS
(либо любых других - не принципиально). Один из сайтов должен
обслуживаться Apache2, а второй PHP-FPM.
4. Ознакомится с функциональностью модуля mpm-itk для сервера apache2 (по желанию его
можно применить).
5. При установке MariaDB (или MySQL) рекомендую обратить внимание на то от какого пользователя работает СУБД, где хранит файлы конфигурации и файлы баз данных.

* Используемые технологии: Nginx, Apache2, MariaDB (Либо MySQL), PHP и PHP-FPM.
* Используемые CMS: 1C Bitrix (есть пробные версии), Wordpress


Ссылки:
- https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/
- https://nginx.org/ru/docs/beginners_guide.html
- https://losst.ru/ustanovka-i-nastrojka-servera-apache
- https://androidp1.ru/kak-ustanovit-mariadb-sozdat-bazu-dannyh-polzovatelja-i-parol/
- http://mpm-itk.sesse.net/

CMS:
- https://www.1c-bitrix.ru/download/cms.php
- https://wordpress.org/download/

[Процесс решения](solution.md)

[Вопросы](questions.md)