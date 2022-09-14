<h1>👋 Приветствую, меня зовут Александр Новоселов</h1>

<h3>✉️ Контакты:</h3>
e-mail: sn.mail@mail.ru</br>
Telegram: https://t.me/Alexander_Novo</br>
&nbsp;
&nbsp;
 
💻 Я - Frontend разработчик, занимаюсь версткой (HTML + CSS), программирую на JavaScript/React.
Прошел обучение в Яндекс.Практикуме, изучены и подтверждены успешно сданными проектными работами темы:
- HTML5/CSS3
- React (функциональные и классовые модули)
- JavaScript - циклы, функции, массивы, объекты, работа с DOM, управление по событиям слушателей, валидация форм, ООП (классы, методы, инкапсуляция, наследование, полиморфизм), работа с API, запросы FETCH, ассинхронность, promise
- сборка проекта Webpack, транспиляция JS
- Git/GitHub/GitHub Pages
- Flexbox/Grid верстка
- кроссбраузерная и адаптивная верстка (медиазапросы)
- верстка PixelPerfect
- БЭМ методология
- использование тегов iframe, video, audio
- анимация: transition, transform, @keyframes
- формы (input, checkbox, radio)
- основы backend (Node.js/Express/mongoDB/PM2/NGINX) - создание и настройка бэкенда с нуля, настройка роутинга, защищенные роуты, валиадация данных, хэширование пароля, токены и т.д.

👨‍🎓 Продолжаю изучать React/Redux. Сейчас идет стадия написания дипломного проекта для успешного завершения обучения в Яндекс.Практикуме.

### Стек:
![HTML](https://img.shields.io/badge/-HTML-05122A?style=flat&logo=HTML5)&nbsp;
![CSS](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=CSS3&logoColor=1572B6)&nbsp;
![JavaScript](https://img.shields.io/badge/-JavaScript-05122A?style=flat&logo=javascript)&nbsp;
![React](https://img.shields.io/badge/-React-05122A?style=flat&logo=react)&nbsp;
![JSON](https://img.shields.io/badge/-JSON-05122A?style=flat&logo=JSON)&nbsp;
![BEM](https://img.shields.io/badge/-BEM-05122A?style=flat&logo=BEM)&nbsp;
![OOP](https://img.shields.io/badge/-ООП-05122A?style=flat&logo=StackShare&logoColor=green)&nbsp;
![Node.js](https://img.shields.io/badge/-Node.js-05122A?style=flat&logo=Node.js&logoColor=339933)&nbsp;
![Express](https://img.shields.io/badge/-Express-05122A?style=flat&logo=Express)&nbsp;
![MongoDB](https://img.shields.io/badge/-MongoDB-05122A?style=flat&logo=MongoDB&logoColor=47A248)&nbsp;
![Nginx](https://img.shields.io/badge/-NGINX-05122A?style=flat&logo=NGINX&logoColor=009639)&nbsp;
![PM2](https://img.shields.io/badge/-PM2-05122A?style=flat&logo=PM2&logoColor=2B037A)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git)&nbsp;
![GitHub](https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github)&nbsp;
![Webpack](https://img.shields.io/badge/-Webpack-05122A?style=flat&logo=Webpack)&nbsp;
![Visual Studio Code](https://img.shields.io/badge/-Visual%20Studio%20Code-05122A?style=flat&logo=visual-studio-code&logoColor=007ACC)&nbsp;
![WebStorm](https://img.shields.io/badge/-WebStorm-05122A?style=flat&logo=WebStorm&logoColor=05CE78)&nbsp;
![Figma](https://img.shields.io/badge/-Figma-05122A?style=flat&logo=Figma)&nbsp;
![Photoshop](https://img.shields.io/badge/-Photoshop-05122A?style=flat&logo=adobe-photoshop)&nbsp;
![Slack](https://img.shields.io/badge/-Slack-05122A?style=flat&logo=Slack)&nbsp;
![Confluence](https://img.shields.io/badge/-Confluence-05122A?style=flat&logo=Confluence)&nbsp;
![Jira](https://img.shields.io/badge/-Jira_Software-05122A?style=flat&logo='Jira_Software')&nbsp;


Профиль на CodeWars
<img src="https://www.codewars.com/users/Novoboss/badges/small">



## Текущие выполненные проекты:

### ✔️ Проект: Mesto Russia API Full (React) + backend (Node.js/Express/MongoDB)
![image](https://user-images.githubusercontent.com/97363077/190112441-ec8dca17-e5a5-435a-8448-c3808b54bdf5.png)


Проект демонстрирует функционал соц.сети, предоставляющей возможность зарегистрированным пользователям делиться своими фотографиями, ставить/удалять лайки, удалять свои карточки, редактировать данные своего профиля.
Frontend создан с использованием фреймворка React, backend построен на Node.js/Express/MongoDB/pm2/Nginx.

Функционал приложения позволяет пользователю произвести регистрацию, авторизоваться с использованием указанных ранее email и пароля. Для повышения безопасности приложения используется хранение хэша пароля, в чистом виде пароль в БД не хранится. После авторизации серверная часть высылает токен, который сохраняется приложением в local storage, что позволяет пользователю использовать весь доступный функционал без повторного ввода пароля. Без авторизации доступно только два роута: /sign-up и /sign-in. Остальные роуты защищены от несанкционированного доступа и недоступны без авторизации. 

После авторизации пользователь может:

- изменить свои данные, присвоенные сервером по умолчанию (имя, описание "о себе", ссылка на аватар),
- поставить/удалить лайк на любую из имеющихся на странице фотографий,
- добавить свои фотографии, дав им краткие названия,
- удалить любую из своих фотографий (фотографии других пользователей удалить невозможно).

Данные, которые вводит в поля форм пользователь при выполнении вышеперечисленных задач, валидируются на сервере с использованием модуля validator в схемах модели mongoose и Joi/celebrate в роутах.
Для улучшения UI добавлен функционал, отображающий соответствующие надписи на кнопках в момент обмена информацией с сервером, добавлено всплывающее окно с дополнительным подтверждением удаления карточки.

#### Стек технологий: 
![HTML](https://img.shields.io/badge/-HTML-05122A?style=flat&logo=HTML5)&nbsp;
![CSS](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=CSS3&logoColor=1572B6)&nbsp;
![JavaScript](https://img.shields.io/badge/-JavaScript-05122A?style=flat&logo=javascript&logoColor=F7DF1E)&nbsp;
![React](https://img.shields.io/badge/-React-05122A?style=flat&logo=react&logoColor=61DAFB)&nbsp;
![JSON](https://img.shields.io/badge/-JSON-05122A?style=flat&logo=JSON)&nbsp;
![Node.js](https://img.shields.io/badge/-Node.js-05122A?style=flat&logo=Node.js&logoColor=339933)&nbsp;
![Express](https://img.shields.io/badge/-Express-05122A?style=flat&logo=Express)&nbsp;
![MongoDB](https://img.shields.io/badge/-MongoDB-05122A?style=flat&logo=MongoDB&logoColor=47A248)&nbsp;
![Nginx](https://img.shields.io/badge/-NGINX-05122A?style=flat&logo=NGINX&logoColor=009639)&nbsp;
![PM2](https://img.shields.io/badge/-PM2-05122A?style=flat&logo=PM2&logoColor=2B037A)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git)&nbsp;
![GitHub](https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github)&nbsp;


#### Ссылка на репозиторий: https://github.com/Alexander-Nov/react-mesto-api-full
#### Ссылка на сайт: https://novoselov.nomorepartiesxyz.ru/
&nbsp;
&nbsp;


### ✔️ Проект: To-Do Demo (React)
<img src="https://user-images.githubusercontent.com/97363077/178458775-f35b6785-b097-420d-92b8-fe6a216c016b.png" width="600">

Проект создан для отработки навыков программирования на JavaScript с использованием библиотеки React.
Функционал приложения загружает стартовые демонстрационные задачи из файла initial.js и позволяет добавлять новые задачи, редактировать активные задачи, отмечать их выполненными, удалять из списка.

#### Стек технологий: 
![React](https://img.shields.io/badge/-React-05122A?style=flat&logo=react)&nbsp;
![JavaScript](https://img.shields.io/badge/-JavaScript-05122A?style=flat&logo=javascript)&nbsp;
![HTML](https://img.shields.io/badge/-HTML-05122A?style=flat&logo=HTML5)&nbsp;
![CSS](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=CSS3&logoColor=1572B6)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git)&nbsp;
![GitHub](https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github)&nbsp;


#### Ссылка на репозиторий: https://github.com/Alexander-Nov/react-to-do
#### Ссылка на github pages: https://alexander-nov.github.io/react-to-do/
&nbsp;
&nbsp;


### ✔️ Проект: Mesto Russia (React)
![image](https://user-images.githubusercontent.com/97363077/177821349-606d051c-2ae1-4440-be20-0a23b9c1f6d4.png)

Проект по функционалу аналогичен более раннему проекту Mesto, но создан на React.
Для отельных элементов интерфейса страницы раработаны функциональные компоненты.
Проект дает возможность менять данные и аватар пользователя, добавлять и удалять свои фото, ставить/удалять лайки на любое фото. Для улучшения UI добавлен функционал, отображающий соответствующие надписи на кнопках в момент обмена информацией с сервером. Кроме того добавлено всплывающее окно с дополнительным подтверждением удаления карточки.

#### Стек технологий: 
![HTML](https://img.shields.io/badge/-HTML-05122A?style=flat&logo=HTML5)&nbsp;
![CSS](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=CSS3&logoColor=1572B6)&nbsp;
![JavaScript](https://img.shields.io/badge/-JavaScript-05122A?style=flat&logo=javascript)&nbsp;
![React](https://img.shields.io/badge/-React-05122A?style=flat&logo=react)&nbsp;
![JSON](https://img.shields.io/badge/-JSON-05122A?style=flat&logo=JSON)&nbsp;
![BEM](https://img.shields.io/badge/-BEM-05122A?style=flat&logo=BEM)&nbsp;
![OOP](https://img.shields.io/badge/-ООП-05122A?style=flat&logo=StackShare&logoColor=green)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git)&nbsp;
![GitHub](https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github)&nbsp;
![Webpack](https://img.shields.io/badge/-Webpack-05122A?style=flat&logo=Webpack)&nbsp;


#### Ссылка на репозиторий: https://github.com/Alexander-Nov/mesto-react
&nbsp;
&nbsp;


### ✔️ Проект: Mesto Russia
![image](https://user-images.githubusercontent.com/97363077/173586338-afb94d11-2a8c-49ce-9576-abd134f359e4.png)

Проект предоставляет возможности социальной платформы - добавление фотографий, возможность добавить лайк, удалить фото, отредактировать профиль пользователя. Все фото загружаются с сервера с применением FETCH-запроса. Аналогично вся информация о новых карточках, а лайках и удалении фото синхронизируется с сервером. Для реализации функционала созданы различные классы, с использованием наследования и полиморфизма. Все взаимодействие с сервером организовано в рамках класса Api. Для организации взаимодействия с пользователм используются всплывающие окна, например, организовано всплывающее окно с запросом подтверждения на удаление карточки с фото. Все формы в попапах имеют валидацию корректности введенных пользователем данных. Применена адаптивная верстка для поддержки всего диапазона используемых разрешений. Вся разработка производилась в отдельных ветках Git для каждого отдельного функционала. Кроме того в проекте настроена сборка посредством Webpack.

#### Стек технологий: 
![HTML](https://img.shields.io/badge/-HTML-05122A?style=flat&logo=HTML5)&nbsp;
![CSS](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=CSS3&logoColor=1572B6)&nbsp;
![JavaScript](https://img.shields.io/badge/-JavaScript-05122A?style=flat&logo=javascript)&nbsp;
![JSON](https://img.shields.io/badge/-JSON-05122A?style=flat&logo=JSON)&nbsp;
![BEM](https://img.shields.io/badge/-BEM-05122A?style=flat&logo=BEM)&nbsp;
![OOP](https://img.shields.io/badge/-ООП-05122A?style=flat&logo=StackShare&logoColor=green)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git)&nbsp;
![GitHub](https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github)&nbsp;
![Webpack](https://img.shields.io/badge/-Webpack-05122A?style=flat&logo=Webpack)&nbsp;


#### Ссылка на репозиторий: https://github.com/Alexander-Nov/mesto
#### Ссылка на github pages: https://alexander-nov.github.io/mesto/
&nbsp;
&nbsp;


### ✔️ Проект: Путешествие по России
![image](https://user-images.githubusercontent.com/97363077/173588112-948fb063-233b-4416-9c3d-d9dd9c94ab4d.png)

Проект о путешествиях по России, в том числе и достаточно непривычным способом - на электричках. Проект содержит ссылки на полезные ресурсы, которые омгут пригодиться при организации путешествия - карты, расписаниее ЖД транспорта, сервис бронирования проживания и т.д.
Проект реализован с использованием flexbox и grid вёрстки, 

#### Стек: 
![HTML](https://img.shields.io/badge/-HTML-05122A?style=flat&logo=HTML5)&nbsp;
![CSS](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=CSS3&logoColor=1572B6)&nbsp;
![BEM](https://img.shields.io/badge/-BEM-05122A?style=flat&logo=BEM)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git)&nbsp;
![GitHub](https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github)&nbsp;
#### Ссылка на репозиторий: https://github.com/Alexander-Nov/russian-travel</br>
#### Ссылка на github pages: https://alexander-nov.github.io/russian-travel/index.html</br>
&nbsp;
&nbsp;

### ✔️ Проект: Научиться учиться
![image](https://user-images.githubusercontent.com/97363077/173589016-227de0af-01ad-43db-8894-d9ea5f88fa64.png)

Проект о правильном подходе к обучению, на котором были применены знания о методологии БЭМ, использовалась flexbox-верстка, была добавлена анимация некоторых элементов дизайна, внедрены на страницу видеоролики с Youtube.

#### Стек: 
![HTML](https://img.shields.io/badge/-HTML-05122A?style=flat&logo=HTML5)&nbsp;
![CSS](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=CSS3&logoColor=1572B6)&nbsp;
![BEM](https://img.shields.io/badge/-BEM-05122A?style=flat&logo=BEM)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git)&nbsp;
![GitHub](https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github)&nbsp;
#### Ссылка на репозиторий: https://github.com/Alexander-Nov/how-to-learn
#### Ссылка на github pages: https://alexander-nov.github.io/how-to-learn/

