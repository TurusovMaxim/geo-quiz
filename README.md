# GeoQuiz
GeoQuiz app from Android Programming: The Big Nerd Ranch Guide (4th Edition) with all exercises completed.

Приложение состоит из двух простых экранов. На первом пользователя просят проверить верно ли утверждение на экране, если пользователь не знает ответа, он может его подсмотреть на втором экране. Но! Жульничать плохо, количество таких ‘подсказок’ ограничено. При попытке ответить на вопрос, на котором пользователь схитрил, будет выводится сообщение – “Cheating is wrong!”, тем не менее на остальные вопросы пользователь имеет возможность отвечать.

В приложении была использована архитектура MVC с поддержкой библиотеки жизненного цикла viewmodel-savedstate, ведь приложению необходимо уметь переживать смену конфигурации устройства, а также уничтожение процесса приложения операционной системой.

![Screenshot_1623871882](https://user-images.githubusercontent.com/36820756/122281239-b809f580-cef2-11eb-9a3c-e35634815190.png)
![Screenshot_1623871893](https://user-images.githubusercontent.com/36820756/122281302-c7893e80-cef2-11eb-8356-b4c47c69b06e.png)
