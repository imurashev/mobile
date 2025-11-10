## Тестирование мобильных приложений
В рамках данного раздела я работал с [Android приложением "shopping-list"](https://drive.google.com/file/d/1wSz1J4Ba-VDgjv82RIk59EaQ1Ys16ph8/view?usp=share_link) (для тестирования использовался эмулятор устройства Google Pixel 9 в Android Studio) и создал следующие артефакты:
- [Чек-лист](https://docs.google.com/spreadsheets/d/1qrYEyXL0olEO4zsIEYPECWNsSej22lO2xgqQeJ-UGN4/edit?usp=sharing)
- [Тест-кейсы в Qase (pdf)](https://github.com/imurashev/mobile/blob/main/Test%20cases%20for%20'shopping-list'%20mobile%20app.pdf)
- [Тестовый прогон в Qase (pdf)](https://github.com/imurashev/mobile/blob/main/%D0%A2%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D1%8B%D0%B9%20%D0%BF%D1%80%D0%BE%D0%B3%D0%BE%D0%BD%20-%20shopping-list.pdf)
- [Отчет о дефектах в YouTrack (xlsx)](https://github.com/imurashev/mobile/blob/main/%D0%9E%D1%82%D1%87%D0%B5%D1%82%20%D0%BE%20%D0%B4%D0%B5%D1%84%D0%B5%D0%BA%D1%82%D0%B0%D1%85%20-%20shopping-list.xlsx)
- [Отчет о результатах тестирования (pdf)](https://github.com/imurashev/mobile/blob/main/%D0%9E%D1%82%D1%87%D0%B5%D1%82%20%D0%BE%20%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D0%B0%D1%85%20%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20shopping-list.pdf)

Также с помощью Charles Proxy я выполнил следующие задания, связанные с перехватом и изменения трафика на https://demoshopping.ru/:
- Изменение запроса на удаление одного товара из корзины, при котором удаляется совсем другой товар
- Моделирование ситуации, когда при обращении к ресурсу пользователь увидит в браузере любую картинку
- Показать любой перехваченный HTTPs-запрос с мобильного устройства, чтобы в header User-agent была отображена информация об этом мобильном устройстве

Для просмотра моих решений [смотрите данное видео](https://drive.google.com/file/d/12JUp94OQ3aukj8ZIEbW3Z-dFPWOcvF9M/view?usp=sharing)
