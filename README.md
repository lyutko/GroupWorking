# The command work training
### *Підготовка*

1. Для початку треба скопіювати репозиторій. В Git-bash виконати команду:  
        `git clone https://github.com/lyutko/GroupWorking.git`
2. У папці "**-Templates-**" обрати собі макет та повідомити про вибір (або ж самостійно записати назву макету у таблиці нижче).
    > У цій папці макети розташовані у підпапках із назвою макету, а також всі зображення макетів підряд розташовані у підпапці **`_ALL_`**.
3. Налаштувати репозиторій:  
    3.1. Відкрити папку, яка утворилась та встановити ім'я користувача та електронну пошту, виконавшити наступні команди:  
        `git config --local user.name "Name"`  
        `git config --local user.email "email@gmail.com"`

    > Тут замість  **`Name`**  та  **`email@gmail.com`**  вказасти свої значення.  
    > Також при бажанні можна використати **`--global`** замість **`--local`** для збереження для всього комп'ютера, а не лише для проекту.

    3.2. Створити окрему гілку для свого макету:  
        `git checkout -b maketName`  
    > Тут замість **`maketName`** вказати назву свого макету (наприклад, ***`index`***, ***`error_404`***, ***`about`*** тощо). Це і буде назвою нової гілки.  
    > ***Важливо:*** Для кожного макету має бути окрема гілка!

    3.3. Зробити тестовий коміт.  

    Для цього зробити будь-які зміни (наприклад, створити файл із розширенням **`.html`** в корені репозиторію із назвою макету; або ж добавити пробіл у будь-який файл).  

    Потім виконати наступні команди:  
        `git add .`  
        `git commit -m "Connection test"`  
		
	3.4. Перевірити з'єднання.  

    Для цього виконати команду:  
        `git push origin  maketName` 

    > Тут замість **`maketName`** вказати назву своєї гілки, створеної в пункті ***'3.2'*** (тобто співзвучної із назвою свого макету).  

    > Під час появи повідомлення про авторизацію, обрати/натиснути 'у вікні браузера', та ввести логін (електронну пошту) та пароль, що використовуються для авторизації на сайті [github.com](https://github.com).  
    
    > У всіх подальших відправках на сервер (для існуючих на сервері гілок) слід використовувати спрощену команду:  
    > `git push`  

4. Перевірити появу своєї гілки у [репозиторії на github](https://github.com/lyutko/GroupWorking). Це свідчитиме, що з'єднання корректне і можна працювати. 
5. Створити файл із розширенням "**.html**" в корені репозиторію із назвою макету (тобто, назва макету = назва файлу), якщо його не було створено у кроці ***'3.3'***.  
   Також можна створити файл стилю для свого макету (якщо потрібно), та розмістити його у папці "**css**".
6. Зі свого макету (що у папці "**-Templates-/назва_макету**") витягнути необхідні зображення.  
У папці "**img**" створити папку для свого макету, та перемістити туди новоутворені (витягнуті із макету) зображення.  
7. Розпочати роботу з верстки.



## Вимоги
- Кожен має зробити як мінімум один макет (за бажанням та наявністю додаткового часу можна виконати ще один);
- Слід використовувати [**Bootstrap**](https://getbootstrap.com/) або [**Materialize**](https://materializecss.com);
- Обов'язково мають бути створені сторінки **index.html** та **404.html**;
- Всі кнопки та посилання мають кудись приводити;
- У навігаційному меню (*navbar*) та підвалі (*footer*) мають бути посилання на всі наявні макети (інші сторінки);
- В посилання які нікуди не ведуть має бути встановлено посилання на сторінку 404 помилки (***404.html***).



## Хто які макети робить

| Прізвище |  Назва макету1   | Назва макету2 (якщо виконується) |
| -------- | ---------------- | -------------------------------- |
| Наталія  | My_Profile       |
| Ілона    | Order            |
| Катерина | Prices           |
| Олена    | 404              |
| Дмитро   | Samples          |
| Сергій   | Login_&_Register |
| Іван     | Index            |








.