User Invite App - это React-приложение, которое позволяет отображать список пользователей, фильтровать их по имени или email и отправлять им приглашения.

1. Основной функционал
   - Загрузка списка пользователей с API.
   - Фильтрация пользователей по имени или email.
   - Добавление пользователей в список приглашенных.
   - Отображение количества приглашенных пользователей.
   - Возможность отправить приглашения.

2. Используемые технологии
  - React — библиотека для создания пользовательских интерфейсов.
  - React Hooks — для управления состоянием (useState, useEffect).
  - SASS — для стилизации компонентов.
  - React Content Loader — для отображения заглушек во время загрузки данных.
  - API Reqres — для получения списка пользователей.

3. Как запустить проект?
   - Убедитесь, что у вас установлен Node.js.
   - Клонируйте репозиторий: git clone https://github.com/yourusername/user-invite-app.git
   - Перейдите в директорию проекта: cd user-invite-app
   - Установите зависимости: npm install
   - Запустите проект: npm start
  
4. Структура проекта
  - src/App.js — основной компонент приложения.
  - src/components/Success.jsx — отображение успешной отправки приглашений.
  - src/components/Users — включает:
  - Skeleton.jsx — компонент-заглушка.
  - User.jsx — отображение одного пользователя.
  - index.jsx — список пользователей и функционал фильтрации.
  - index.scss — стили приложения.

5. API
Приложение использует публичное API Reqres для получения списка пользователей. В ответе возвращается массив объектов с данными пользователей, такими как id, first_name, last_name, email, и avatar.

6. Скриншоты
   - ![Снимок экрана 2024-12-14 в 18 46 41](https://github.com/user-attachments/assets/f155eccf-792f-472f-87b4-27fe3cae5278)
   - ![Снимок экрана 2024-12-14 в 18 47 05](https://github.com/user-attachments/assets/caa1b0cd-0011-4fb9-a696-d323ce6fcf2f)
   - ![Снимок экрана 2024-12-14 в 18 47 53](https://github.com/user-attachments/assets/603155e3-4653-4cd1-a97a-b66cdc930682)
   - ![Снимок экрана 2024-12-14 в 18 48 19](https://github.com/user-attachments/assets/926ca2a9-0cc2-40af-8616-50e0388e20b4)
