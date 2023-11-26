# План автоматизации тестирования сценария перехода к форме записи на профессию "Тестировщик ПО" и заполнения этой формы на сайте [Нетология](https://netology.ru/)  

## Оглавление
1. [Перечень автоматизируемых сценариев](#1-перечень-автоматизируемых-сценариев)
    - [Сценарии перехода на страницу профессии "Тестировщик ПО"](#сценарии-перехода-на-страницу-профессии-тестировщик-по)
    - [Сценарии перехода к форме записи на курс "Тестировщик ПО"](#сценарии-перехода-к-форме-записи-на-курс-тестировщик-по)
    - [Сценарии заполнения формы записи на курс при авторизованном пользователе](#сценарии-заполнения-формы-записи-на-курс-при-авторизованном-пользователе)
    - [Сценарии заполнения формы записи на курс при неавторизованном пользователе](#сценарии-заполнения-формы-записи-на-курс-при-неавторизованном-пользователе)
2. [Перечень используемых инструментов](#-перечень-используемых-инструментов)
3. [Перечень необходимых разрешений, данных и доступов](#3-перечень-необходимых-разрешений-данных-и-доступов)
4. [Перечень и описание возможных рисков при автоматизации](#4-перечень-и-описание-возможных-рисков-при-автоматизации)
5. [Перечень необходимых специалистов для автоматизации](#5-перечень-необходимых-специалистов-для-автоматизации)
6. [Раздел 6](#6)

## Перечень автоматизируемых сценариев
### Сценарии перехода на страницу профессии "Тестировщик ПО"
*Предусловия*: 
Открыта страница [Нетология](https://netology.ru/).
<br>
</br>

### Сценарий 1. Переход на страницу курса через выпадающее меню каталога курсов и поиск.    

*Шаги воспроизведения*:
1. Нажать на "Каталог курсов".
2. В поиске ввести "Тестировщик ПО".
3. Нажать на "Найти курс".
4. Найти в списке и нажать на профессию "Тестировщик ПО".

*Ожидаемый результат*:
Переход на страницу с профессией "Тестировщик ПО".  
<br>
</br>
**Сценарий 2.** Переход на страницу курса через выпадающее меню каталога курсов и поиск и подсказку профессий.    

*Шаги воспроизведения*:
1. Нажать на "Каталог курсов".
2. В поиске ввести "Тестировщик ПО".
3. Из подсказок нажать на профессию "Тестировщик ПО".

*Ожидаемый результат*:
Переход на страницу с профессией "Тестировщик ПО".
<br>
</br>

**Сценарий 3.** Переход на страницу курса через выпадающее меню каталога курсов и поиск и подсказку запросов.    

*Шаги воспроизведения*:
1. Нажать на "Каталог курсов".
2. В поиске ввести "Тестировщик ПО".
3. Нажать на "Все курсы по запросу "тестировщик ПО".
4. Найти в списке и нажать на профессию "Тестировщик ПО".

*Ожидаемый результат*:
Переход на страницу с профессией "Тестировщик ПО".
<br>
</br>

**Сценарий 4.** Переход на страницу курса через каталог "Все курсы" и поиск.  

*Шаги воспроизведения*:
1. Нажать на "Каталог курсов".
3. Нажать на "Все курсы".
4. В поиске ввести "Тестировщик ПО".
5. Нажать на "Найти курс".
6. Найти в списке и нажать на профессию "Тестировщик ПО".

*Ожидаемый результат*:
Переход на страницу с профессией "Тестировщик ПО".
<br>
</br>

### Сценарий 5. Переход на страницу курса через каталог "Все курсы" и поиск и подсказку профессий.  

*Шаги воспроизведения*:
1. Нажать на "Каталог курсов".
3. Нажать на "Все курсы".
4. В поиске ввести "Тестировщик ПО".
5. Из подсказок нажать на профессию "Тестировщик ПО".

*Ожидаемый результат*:
Переход на страницу с профессией "Тестировщик ПО".
<br>
</br>

**Сценарий 6.** Переход на страницу курса через каталог "Все курсы" и поиск и подсказку запросов.  

*Шаги воспроизведения*:
1. Нажать на "Каталог курсов".
3. Нажать на "Все курсы".
4. В поиске ввести "Тестировщик ПО".
5. Нажать на "Все курсы по запросу "Тестировщик ПО".

*Ожидаемый результат*:
Переход на страницу с профессией "Тестировщик ПО".
<br>
</br>

**Сценарий 7.** Переход на страницу курса через каталог "Все курсы" и фильтр.  

*Шаги воспроизведения*:
1. Нажать на "Каталог курсов".
3. Нажать на "Все курсы".
4. Поставить в фильтре "Навык" чекбокс "Тестировщик ПО".
5. Нажать на профессию "Тестировщик ПО".

*Ожидаемый результат*:
Переход на страницу с профессией "Тестировщик ПО".
<br>
</br>

**Сценарий 8.** Переход на страницу курса через каталог "Программирование" и поиск.  

*Шаги воспроизведения*:
1. Нажать на "Каталог курсов".
2. Нажать на "Программирование".
3. В поиске ввести "Тестировщик ПО".
4. Нажать на "Найти курс".
5. Найти в списке и нажать на профессию "Тестировщик ПО".

*Ожидаемый результат*:
Переход на страницу с профессией "Тестировщик ПО".
<br>
</br>

**Сценарий 9.** Переход на страницу курса через каталог "Программирование" и поиск и подсказку профессий.  

*Шаги воспроизведения*:
1. Нажать на "Каталог курсов".
2. Нажать на "Программирование".
3. В поиске ввести "Тестировщик ПО".
4. Из подсказок нажать на профессию "Тестировщик ПО".

*Ожидаемый результат*:
Переход на страницу с профессией "Тестировщик ПО".
<br>
</br>

**Сценарий 10**. Переход на страницу курса через каталог "Программирование" и поиск и подсказку запросов.  

*Шаги воспроизведения*:
1. Нажать на "Каталог курсов".
2. Нажать на "Программирование".
3. В поиске ввести "Тестировщик ПО".
4. Нажать на "Все курсы по запросу "тестировщик ПО".
5. Найти в списке и нажать на профессию "Тестировщик ПО".

*Ожидаемый результат*:
Переход на страницу с профессией "Тестировщик ПО".
<br>
</br>

**Сценарий 11**. Переход на страницу курса через каталог "Программирование".  

*Шаги воспроизведения*:
1. Нажать на "Каталог курсов".
2. Нажать на "Программирование".
3. Найти в списке и нажать на профессию "Тестировщик ПО".

*Ожидаемый результат*:
Переход на страницу с профессией "Тестировщик ПО".
<br>
</br>

**Сценарий 12**. Переход на страницу курса через каталог "Программирование" и фильтр.  

*Шаги воспроизведения*:
1. Нажать на "Каталог курсов".
2. Нажать на "Программирование".
3. Поставить в фильтре "Навык" чекбокс "Тестировщик ПО".
4. Нажать на профессию "Тестировщик ПО".

*Ожидаемый результат*:
Переход на страницу с профессией "Тестировщик ПО".
<br>
</br>

**Сценарий 13**. Переход на страницу курса через раздел "Направление обучения" и каталог "Программирование".  

*Шаги воспроизведения*:
1. Найти раздел "Направление обучения".
2. Нажать на "Программирование".
3. В поиске ввести "Тестировщик ПО".
4. Нажать на "Найти курс".
5. Найти в списке и нажать на профессию "Тестировщик ПО".

*Ожидаемый результат*:
Переход на страницу с профессией "Тестировщик ПО".
<br>
</br>

**Сценарий 14**. Переход на страницу курса через раздел "Направление обучения" и полный каталог.  

*Шаги воспроизведения*:
1. Найти раздел "Направление обучения".
2. Нажать на "Полный каталог".
3. Поставить в фильтре "Навык" чекбокс "Тестировщик ПО".
4. Нажать на профессию "Тестировщик ПО".

*Ожидаемый результат*:
Переход на страницу с профессией "Тестировщик ПО".

<h3><center>Сценарии перехода к форме записи на курс "Тестировщик ПО"</center></h3>
*Предусловия*:
Открыта страница курса [Тестировщик ПО](https://netology.ru/programs/qa).
<br>
</br>

**Сценарий 1.** Переход к форме записи из начала страницы.  

*Шаги воспроизведения*:
1. Нажать на "Записаться".

*Ожидаемый результат*:
Переход к форме записи на курс "Тестировщик ПО".
<br>
</br>

**Сценарий 2.** Переход к форме записи из панели страницы.  

*Шаги воспроизведения*:
1. Прокрутить страницу вниз до появления вверху панели страницы.
1. Справа сверху нажать на "Записаться".

*Ожидаемый результат*:
Переход к форме записи на курс "Тестировщик ПО".
<br>
</br>

**Сценарий 3.** Переход к форме записи из низа страницы.  

*Шаги воспроизведения*:
1. Прокрутить страницу вниз до формы записи.
1. Справа сверху нажать на "Записаться".

*Ожидаемый результат*:
Переход к форме записи на курс "Тестировщик ПО".
<br>
</br>

**Сценарий 4.** Переход к форме записи через выбор обучения.  

*Шаги воспроизведения*:
1. Прокрутить страницу вниз до раздела "Выберите свой вариант обучения".
1. Нажать на "Выбрать" на одном из варинатов обучения.

*Ожидаемый результат*:
Переход к форме записи на курс "Тестировщик ПО".
<br>
</br>

### Валидные входные данные для полей формы записи курс:
1. Поле имя: Латиница или кириллица, минимум 2 символа, допустимы дефисы.
2. Поле телефон: Цифрами в формате +9 (999) 999-99-99, допустимы коды других стран.
3. Поле email: формат username@hostname.com, латиница, буквы, знаки в имени и доменной части email.

### Невалидные входные данные для полей формы записи курс:
1. Поле имя: цифры, знаки, спецсимволы, иероглифы, пустое поле, 1 буква.
2. Поле телефон: буквы, знаки, спецсимвол, иероглифы, пустое поле, 1 цифра, более 11 цифр после кода города.
3. Поле email: email без точек в доменной части, отсутствие @, email с пробелами в именной или доменной части,
отсутсвие именной или доменной части.
<br>
</br>

<h3><center>Сценарии заполнения формы записи на курс при авторизованном пользователе</center></h3>
*Предусловия*:
Открыта страница форма записи на курс на станице [Тестировщик ПО](https://netology.ru/programs/qa).
Пользователь авторизован.
<br>
</br>

**Сценарий 1.** Отправка формы заполненными данными.  

*Шаги воспроизведения*:
1. Нажать на записаться.

*Ожидаемый результат*:
Появилось сообщение "Вы успешно записались на курс "Тестировщик ПО. Менеджер свяжется с Вами по указанному 
номеру для консультации по оплате".
<br>
</br>

**Сценарий 2.** Отправка формы с перезаполненными валидными данными.  

*Шаги воспроизведения*:
1. Заполнить поля формы имя и телефон валидными данными.
2. Нажать на записаться.

*Ожидаемый результат*:
Появилось сообщение "Вы успешно записались на курс "Тестировщик ПО. Менеджер свяжется с Вами по указанному
номеру для консультации по оплате".
<br>
</br>

**Сценарий 3.** Отправка формы с перезаполненным именем невалидными эквивалентыми данными.  

*Шаги воспроизведения*:
1. Заполнить поле имя невалидными эквивалентыми данными.
2. Заполнить поле телефон валидными данными.
3. Нажать на записаться.

*Ожидаемый результат*:
Форма не отправлена, ошибка "Должно состоять из букв".
<br>
</br>

**Сценарий 4.** Отправка формы с перезаполненным именем невалидными граничными данными.  

*Шаги воспроизведения*:
1. Заполнить поле имя невалидными граничными данными.
2. Заполнить поле телефон валидными данными.
3. Нажать на записаться.

*Ожидаемый результат*:
Форма не отправлена, ошибка "Должно быть не короче 2 символов".
<br>
</br>

**Сценарий 5.** Отправка формы с перезаполненным телефоном невалидными данными.  

*Шаги воспроизведения*:
1. Заполнить поле имя валидными данными.
2. Заполнить поле телефон невалидными данными.
3. Нажать на записаться.

*Ожидаемый результат*:
Форма не отправлена, ошибка "Номер в формате +9 (999) 999-99-99".
<br></br>

<h3><center>Сценарии заполнения формы записи на курс при неавторизованном пользователе</center></h3>
*Предусловия*:
Открыта страница форма записи на курс на станице [Тестировщик ПО](https://netology.ru/programs/qa).
Пользователь неавторизован.
<br>
</br>

**Сценарий 1.** Отправка формы с валидными данными.  

*Шаги воспроизведения*:
1. Заполнить поля формы имя, телефон и почту валидными данными.
2. Нажать на записаться.

*Ожидаемый результат*:
Появилось сообщение "Вы успешно записались на курс "Тестировщик ПО. Менеджер свяжется с Вами по указанному
номеру для консультации по оплате".
<br>
</br>

**Сценарий 2.** Отправка формы с невалидным эквивалентым именем.  

*Шаги воспроизведения*:
1. Заполнить поле имя невалидными эквивалентыми данными.
2. Заполнить поле телефон и email валидными данными.
3. Нажать на записаться.

*Ожидаемый результат*:
Форма не отправлена, ошибка "Должно состоять из букв".
<br>
</br>

**Сценарий 3.** Отправка формы с невалидным граничным именем.  

*Шаги воспроизведения*:
1. Заполнить поле имя невалидными граничными данными.
2. Заполнить поле телефон и email валидными данными.
3. Нажать на записаться.

*Ожидаемый результат*:
Форма не отправлена, ошибка "Должно быть не короче 2 символов".
<br>
</br>

**Сценарий 4.** Отправка формы с невалидными данными телефона.  

*Шаги воспроизведения*:
1. Заполнить поле имя валидными данными.
2. Заполнить поле телефон невалидными данными.
3. Заполнить поле email валидными данными.
3. Нажать на записаться.

*Ожидаемый результат*:
Форма не отправлена, ошибка "Номер в формате +9 (999) 999-99-99".
<br>
</br>

**Сценарий 5.** Отправка формы с невалидными данными email.  

*Шаги воспроизведения*:
1. Заполнить поле имя валидными данными.
2. Заполнить поле телефон валидными данными.
3. Заполнить поле email невалидными данными.
3. Нажать на записаться.

*Ожидаемый результат*:
Форма не отправлена, ошибка "Неверный email".
<br>
</br>

**Сценарий 5.** Отправка пустой формы.  

*Шаги воспроизведения*:
1. Очистить поля, если заполнены данные
2. Нажать на записаться.

*Ожидаемый результат*:
Форма не отправлена, ошибка "Обязательное поле".


## Перечень используемых инструментов
* IntelliJ IDEA. Интегрированная среда разработки программного обеспечения для Java.
Java. Высокоуровневый язык программирования с открытым исходным кодом; наличие большого количества библиотек и 
фреймворков; качественная документация; постоянно развивается и обратно совместима с предыдущми версиями.
* Gradle. Гибкая и мощная система сборки проекта с высокой производительностью, которая обеспечивает эффективное управление
зависимостями, поддерживая различные репозитории и форматы; много плагинов; поддержка CI; большая документация; хорошо 
интегрируется с IntelliJ IDEA.
* Selenide. Удобный инструмент для автоматических тестов, построенный на базе Selenium WebDriver; удобные методы; 
автоматическое управление браузером; автоматические скриншоты; поддержка ajax.
* JUnit 5. JUnit - одна из самых популярных сред модульного тестирования в экосистеме Java. Версия JUnit 5 (также известная 
как Jupiter) содержит множество интересных нововведений, включая поддержку новых функций в Java 8 и выше.
* Datafaker. Инструмент для генерации тестовых данных.
* Lombok. Библиотека для сокращения кода в классах и расширения функциональности языка Java. Подключается к среде 
разработки (IDE) или инструменту сборки приложений Gradle в качестве плагина.
* Postman. Для тестирования API, если форма записи взаимодействует с сервером через API.
* Git. Чтобы отслеживать изменения в тестовых сценариях и обеспечивать совместную работу.
* Git Bash. Командная строка для использования функции Git, которая эмулирует среду bash в Windows.
* GitHub. Веб-сервис для хостинга IT-проектов и их совместной разработки; основан на системе контроля версий Git.
* Appveyor. Веб-сервис CI, предназначенный для сборки и тестирования программного обеспечения расположенного на GitHub.

## 3. Перечень необходимых разрешений, данных и доступов:
* разрешение на тестирование и автоматизацию;
* доступ к базе данных и api;
* доступ к тестовой среде, чтобы избежать влияния на реальные данные пользователя.
* доступ к тестовой документации.


## 4. Перечень и описание возможных рисков при автоматизации:
* отсутствие тестовых данных;
* отсутствие тестовых селекторов, увеличивается время на разработку автотестов;
* изменения в дизайне или функционале сайта могут нарушить работу автоматизированных тестов;
* много дефектов в функциональности;
* технические сбои.


## 5. Перечень необходимых специалистов для автоматизации: 
Инженер по автотизированному тестированию


## 6. 




