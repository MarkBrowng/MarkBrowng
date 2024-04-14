Привет, это статья по созданию бота Финансов! Если ты интересуешься программированием и созданием бота также, как и я, то эта статья для Вас. Здесь я описываю процесс создания финансового бота - бота, способного мониторить все Ваши расходы
1. Первым делом регистрируем бота в Телеграме. Для этого нужно в Телеграме найти BotFather, в котором регистрируем бота и получаем API TOKEN, который понадобится для связи кода бота в Python и Телеграмом![image](https://github.com/MarkBrowng/MarkBrowng/assets/152402901/5c2d8fd1-e51f-4c8d-acb9-f2993c56d2c0)
![image](https://github.com/MarkBrowng/MarkBrowng/assets/152402901/fb086329-f975-435c-a1af-3c9bae253d28)
2. Далее устанавливаем все нужные модули, нужные для корректной работы бота. Все названия модулей находятся в файле под названием requirements. Чтобы установить модули, пропишите в командной строке
   pip install -r requirements.txt
   К сожалению, я не смогу рассказать полностью про работу каждого модуля, так как это очень долго, но Вы можете просмотреть все обЪяснения на ютубе)))
3. После того, как все модули установили, переходим к написанию кода. В основном файле пишем все хендлеры, которые будут отвечать за отправку сообщений ботом и обработки сообщений от пользователя. ![image](https://github.com/MarkBrowng/MarkBrowng/assets/152402901/209c0bcf-c41e-4c1c-9e40-4c23ca2607dd)
4. Далее создаем базу данных, который работает на модуле SQlite. В нем будет храниться информация про всех пользователей. В нем будет информация о затраьтах пользователя за месяц, за день, а также общие и частые расходы пользователя.![image](https://github.com/MarkBrowng/MarkBrowng/assets/152402901/6df446c3-eb7c-4a79-be2a-f0c6b30feff2)
5. Создаем файл, который работает с вышеперечисленными категориями расходов и прописываем всю логику проверки входа информации от пользователя.![image](https://github.com/MarkBrowng/MarkBrowng/assets/152402901/90d0bede-0b0a-4529-883f-0287784dc459)
6.Закончив работу с бзд, переходите к соединению с сервером. Для этого Вам поможет модуль os, который предоставляет множество функций для работы с операционной системой, причём их поведение, как правило, не зависит от ОС, поэтому программы остаются переносимыми
7. Далее пишем MiddleWares для лучшей работы бота на сервере![image](https://github.com/MarkBrowng/MarkBrowng/assets/152402901/bbaf97dc-768b-4cc7-8319-0598f6b07107)
8. В итоге, Вам остается создать облачный сервер и подключить к нему своего бота.

Надеюсь, Вам помогла эта статья, и Вы сможете создать своего собственного бота. Если же все-таки не разобрались в процессе создании, я оставил этого бота здесь, чтобы каждый смог воспользоваться им.

