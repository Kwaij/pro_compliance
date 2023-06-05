# pro_compliance
test_work for Pro Compliance

тестовое задание на вакансию

--
Необходимо разработать HTTP сервис для работы с импортируемыми данными.

Должна быть реализована загрузка данных в формате csv (напр. датасеты с Kaggle). Структура файлов неизвестна и может изменяться от файла к файлу.

Помимо загрузки файлов необходимо реализовать следующий функционал:

•             Получение списка файлов с информацией о колонках

•             Возможность получения данных из конкретного файла с опциональными фильтрацией и сортировкой по одному или нескольким столбцам

Использовать рекомендуется любой из языков: python, C++, C#,  можно применять любые библиотеки, фреймворки, базы данных и все, что покажется необходимым.

Дополнительно можно реализовать:

•             Покрытие исходного кода тестами

•             Авторизацию пользователя

•             Дополнительные эндпойнты, напр. удаление ранее загруженного файла

•             Dockerfile для запуска сервиса в Docker

•             прочее
--

Проект реалезован на python django с использованием библиотеки django-import-export, функционал осуществляются через админку сайта
