<div align="center">

<a href="README_ZH.md">汉语</a> ｜ <a href="/README.md">English</a> ｜ Русский ｜ <a href="README_FR.md">Français</a> ｜ <a href="README_ES.md">Español</a> ｜ <a href="README_DE.md">Deutsch</a> ｜ <a href="README_KO.md">한국어</a>

# QR Generator - Open Source (QG-OS)

</div>

## Описание

Этот репозиторий (QG-OS) представляет собой реализацию с открытым исходным кодом [Xi Xu's QR Generator](https://qr.xi-xu.me). QG-OS стремится предоставить разработчикам простое, быстрое и бесплатное решение для создания QR-кода.

## Демонстрация

[Официальная демонстрация QG-OS](https://qg-os.xi-xu.me).

## Развертывание

### 1. Зарегистрируйте учетную запись Cloudflare

Посетите [Cloudflare](https://dash.cloudflare.com/sign-up), чтобы зарегистрировать учетную запись.

### 2. Развертывание в Cloudflare Workers

После входа в учетную запись нажмите [![Развертывание в Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/xixu-me/QR-Generator).

Нажмите «Авторизовать Workers» и войдите в свою учетную запись Github, чтобы авторизовать GitHub в Workers.
![image-20240308100821060](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/241edb52-b1ef-4a2c-8525-bfa3d148391b)

Нажмите «У меня есть учетная запись».
![image-20240308100942925](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/219fc538-e412-4a52-913c-6c4878d50325) Нажмите «Панель инструментов рабочих».
![image-20240308101056834](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/4b4a96be-90b3-40cc-9b50-b214980f2ab2) Скопируйте «Идентификатор учетной записи».
![image-20240308101224693](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/da6f8b64-f6e1-40c0-b812-54f86d8b97c0)

Вставьте его в поле ввода «Идентификатор учетной записи».
![image-20240308101342895](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/4df45a68-855f-4acd-a9be-6d0da63a49a5)

Нажмите «Мой профиль».
![image-20240308101452825](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/4d21f38a-f313-4d66-baf9-83ce1df93f02)

Нажмите «Создать токен».
![image-20240308101620496](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/41e82d1b-27ea-44a0-8cfe-ae66233544ad)

Нажмите «Использовать шаблон» в четвертом пункте «Изменить рабочие процессы Cloudflare».
![image-20240308101741689](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/3974817c-2787-4148-95f9-96f58ef78aee)

Выберите значение «Ресурс учетной записи» для «Ваша учетная запись», а «Ресурс региона» для «Все регионы».
![image-20240308102630538](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/cd20fa0a-b75d-489d-85c0-49a063abea8a)

Нажмите «Продолжить, чтобы отобразить сводку».
![image-20240308102827159](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/9d91e08b-743b-476a-b74e-5b2f46b97ac2)

Нажмите «Создать токен».
![image-20240308103110802](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/db6cde35-cf88-4fde-a58a-d3b204dabc17)

Нажмите «Копировать».
![image-20240308103153901](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/0309e295-d77a-4d27-918e-706e2169347f)

Вставьте его в поле ввода «API Token» и нажмите «Подключить учетную запись».
![aac580cdb2ba5305991c02e46baea0de](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/eb3bb593-13df-4a67-976d-4fbb5f369e51) Нажмите «Создать ответвление репозитория» -> «Действия репозитория» -> «Я понимаю свои рабочие процессы, продолжайте и включите их», чтобы включить действие Github.
![image-20240308103835724](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/a0d89011-edb5-4622-9bb0-c40f6420e936)

Вернитесь на предыдущую страницу и последовательно нажмите «Рабочие процессы включены» -> «Развернуть».
![image-20240308104056663](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/d29844b4-6eda-4da1-984c-3f4507e1c213)
![image](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/63691c2a-b26d-48cd-9c42-6fd74e44694b)

Вернитесь в репозиторий Fork, нажмите «Действия», и развертывание будет успешным, если будет получен следующий результат.
![image-20240308104412895](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/ae35e302-c3cf-4662-badb-926b56b19565)

### 3. Получить ссылку доступа

Найдите ссылку ниже на панели инструментов Worker.
![image](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/8fef9dd4-285e-414a-9237-5378e981b96c)

### 4. Последующие обновления

В адресе проекта Fork нажмите «Sync Fork» и дождитесь автоматического развертывания Actions.
![image](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/16ca803a-fe4b-431e-97b0-f04b8a217220)

### 5. Имя пользовательского домена (необязательно)

На панели инструментов Worker выберите «Триггер» и нажмите «Добавить пользовательский домен», чтобы реализовать имя пользовательского домена
![d64fcdab4dc44504909cc6faa86ae8a1](https://github.com/Harry-zklcdc/go-proxy-bingai/assets/21104213/6f0de2c5-1dd4-4801-b163-6d485836c73d)

## Заявление

Этот репозиторий (QG-OS) предназначена только для обучения и общения. Строго запрещено использовать ее в коммерческих или даже незаконных целях. Пользователи должны соблюдать местные законы и правила, в противном случае они действуют на свой страх и риск.

## Лицензия

Авторские права © 2024 [Xi Xu](https://xi-xu.me). Все права защищены.

Лицензируется по лицензии [GPL-3.0](https://github.com/xixu-me/QR-Generator/blob/main/LICENSE).
