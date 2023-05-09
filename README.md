# Kupyna-DSTU-7564-2014
C# implementation of the "Kupyna" hash function DSTU 7564:2014. Available in the form of a Dll library and a finished program

Користувачеві надається графічний інтерфейс, який дозволяє йому зручно вводити повідомлення для хешування будь-якого типу із різними варіантами кодування. Інтерфейс програми складає головне меню, поле для введення повідомлення для хешування, область налаштування хеш-функції та кодування, кнопки відкриття файлу та очистки вмісту поля для введення, а також кнопки для початку процесу хешування та для зберігання результату у файл. Сам хеш виводиться у відповідному полі. Головне меню дублює деякі основні кнопки додатку, такі як відкриття або зберігання повідомлення та хешу, очистка даних, а також надає користувачеві можливість змінити мову, відкрити вікно із прикладами повідомлень із ДСТУ 7564:2014 та довідку, в якій розписані можливості застосунку. Принцип роботи із застосунком для всіх випадків однаковий: користувач за допомогою поля введення вводить своє повідомлення, натискає кнопку «обчислити» і отримує результат до поля виводу. У випадку, якщо користувачеві потрібно буде змінити довжину хешу (у бітах) або те, як буде розпізнаватися вхідне повідомлення (доступні ASCII або UTF-8 кодування та розпізнання 16-річного коду). Натиснувши на пункт меню «Приклади» користувач отримує список повідомлень, за допомогою яких здійснювалося тестування функції хешування в ДСТУ 7564:2014, що допоможе швидко перевірити працездатність програми.

The user is provided with a graphical interface that allows him to conveniently enter hash messages of any type with various encoding options. The program interface consists of the main menu, a field for entering a message for hashing, a field for setting up a hash function and encoding, buttons for opening a file and clearing the contents of the input field, as well as buttons for starting the hashing process and saving the result to a file. The hash itself is displayed in the corresponding field. The main menu duplicates some of the main buttons of the application, such as opening or saving a message and a hash, clearing data, and also provides the user with the ability to change the language, open a window with examples of messages from DSTU 7564:2014, and help, which describes the application's capabilities. The principle of working with the application is the same for all cases: the user enters their message in the input field, presses the "calculate" button, and receives the result in the output field. In the event that the user needs to change the length of the hash (in bits) or how the incoming message will be recognized (ASCII or UTF-8 encoding and 16-bit code recognition are available). By clicking on the "Examples" menu item, the user receives a list of messages that were used to test the hashing function in DSTU 7564:2014, which will help to quickly check the program's performance.
