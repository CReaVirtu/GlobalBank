# GlobalBank

GlobalBank — это веб-приложение, предназначенное для управления банковскими услугами. Приложение реализовано на Vue.js с использованием Vite для сборки и Pinia для управления состоянием. Включает главную страницу, форму регистрации и личный кабинет пользователя.

## Демо

Вы можете ознакомиться с работой приложения, перейдя по следующей ссылке:  
[GlobalBank Demo](https://rina2316.github.io/GlobalBank/)

## Особенности

- **Главная страница** с приветствием и общей информацией о банке.
- **Форма регистрации** для новых пользователей.
- **Личный кабинет** для авторизованных пользователей с возможностью просмотра и управления личными данными.
- Использование **Pinia** для управления состоянием приложения.
- Быстрая сборка с **Vite**.

## Установка

Для того чтобы запустить проект локально, выполните следующие шаги:

1. Клонируйте репозиторий:

    ```bash
    git clone https://github.com/CReaVirtu/GlobalBank.git
    ```

2. Перейдите в каталог проекта:

    ```bash
    cd GlobalBank
    ```

3. Установите зависимости:

    ```bash
    npm install
    ```

4. Запустите проект:

    ```bash
    npm run dev
    ```

Приложение будет доступно по адресу [http://localhost:3000](http://localhost:3000).

## Структура проекта

- **src** — исходный код приложения:
  - **components** — компоненты Vue.
  - **store** — Pinia для управления состоянием.
  - **views** — страницы приложения (главная, регистрация, личный кабинет).
  - **assets** — ресурсы, такие как изображения и стили.
  
- **public** — статичные файлы, которые будут доступны для загрузки.

## Использование

1. Перейдите на главную страницу, чтобы ознакомиться с приложением.
2. Для регистрации создайте учетную запись, заполнив форму регистрации.
3. После регистрации войдите в личный кабинет, чтобы просматривать и редактировать свои данные.

## Тестирование

Для запуска тестов используйте команду:

```bash
npm run test


```sh
npm run lint
```
