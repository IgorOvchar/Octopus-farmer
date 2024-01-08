      Octopus farmer

  ___Вход в программу___
  
1. Откройте исполняемый файл Octopus farmer.exe

<img width="329" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/5b1f336d-85ef-4ecc-a924-ee5c6e4fa401">

2. Чтобы получить логин и пароль перейдите по ссылке (https://t.me/octopus_key_giver_bot) нажав на кнопку Telegram в телеграмм бота, нажмите старт и получить пароль

3. Введите логин, пароль в программу

4. Далее потребуется открыть ADSPower, в меню API из ссылки скопировать порт после http://local.adspower.net:, вставить его в поле программы "ADS Port"
   
<img width="868" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/900790d1-08e4-4d86-ae6f-a4786fae93df">

6. После заполнения нажмите на кнопку "Login in"

___основное меню___

Навигация по программе происходит при нажатии на консоль меню в левой части программы

<img width="41" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/ab7416e2-91b5-42d2-a0be-76f99008f32e">

1. Home -> Приветственная страница
2. Accounts -> вкладка с профилями вашего ADS, программа загружает эти данные из ADS (эти данные хранятся локально на вашем ПЭВМ). Также есть изменяемые столбцы, которые можно заполнять, они требуется для работы некоторых тасков
4. Tasks -> вкладка с проектами программы, которые можно выполнять
5. Octopus -> ссылка на наш телеграмм
6. Setting -> Настройки программы (Желательно заполнить все поля)

___Создание таска для выполнения___
1. Откройте вкладку Tasks
   <img width="811" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/d9e071e3-67aa-4627-89b8-36a2b0ad4f17">

2. Выберете нужные вап проекты в левом меню Projects
   
   <img width="118" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/551b05d1-1825-42b0-9a8b-b2e92a733238">
   
4. Выберете профиля ADS и нужную функцию, выделите их, нажмите на правую кнопку мыши и выберите Select
   
   <img width="248" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/1a8263f2-0008-4311-909a-8c745c918d33"> <img width="275" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/f101863f-c572-451a-b9fd-a4a7cbbd51e4">

5. После того как вы выделили нужные профиля и функции, введите имя для вашего таска и нажмите Create task
   
   <img width="266" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/a4735c95-f22e-4ed8-b007-37bf3370b4b8">
   
7. Таск создан, теперь он будет отображаться в списке тасков
   <img width="669" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/4db30698-cee7-4c74-b67c-cd87e20db8b1">
8. чтобы перейти в список тасков нажмите на имя таска <img width="91" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/fcd0f6c1-62ce-4b75-98ac-e972008342d5">
 или на <img width="116" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/fe7725f3-23f3-4a52-8652-e01c0bd0b700"> во вкладке Tasks

___Запуск таска и управление выполнением___
1. Введите необходимые вам параметры во все поля в меню Parameters
   
   <img width="322" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/b432cfdf-b6e7-4269-a05e-790adc1ff004">

1.1. number of processes -> число одновременно работающих процессов. Будьте осторожны!!! Не рекомендуется выбирать число процессов больше чем позволяет ваше железо !!! Рекомендуется использовать число процессов не превосходящее количество ядер системы (в основном нагрузка идет при старте браузеров), 
оперативная память расходуется примерно 300 мб на каждый процесс 

1.2. pause between start -> пауза между профилями в отдельном процессе. Можно указать как точное число "5.5", так и интервал "5.5|10.3" тогда пауза будет выбрана случайным образом.

1.3. Random functions start -> при выборе данного флага функции каждого профиля будут перемешаны

1.4. Random profile open -> при выборе данного флага при старте профиля будут перемешаны

1.5. Open handle work after ERRORS -> при выборе данного флага после возникновения ошибки пофиль не будет закрываться, а будет ждать действия пользователя

<img width="321" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/7104c67d-9d10-422d-bc39-e19789e9dc6f">

2. После ввода параметров нажмите <img width="83" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/56695a27-2fc7-4491-9575-869c7bc0d168"> и <img width="152" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/a627d9a7-dd85-4072-8ea1-eb05c90ea17e">

 Task запущен, результаты выполнения функций бедет отображаться в таблице таска и общей таблице со всеми проектами 

<img width="200" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/0f6f17c0-cab9-4bf5-97d8-829a5daf8e5a">

3. Вы можете управлять процессом выполнения таска
   
<img width="332" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/573334b0-8bab-40b2-9443-36f87bca643a">

Пауза приостанавливает выполнение, запущенные процессы продолжают выполняться, новые не запускаются 

Остановка завершает текущие процессы и останавливают программу

Сбросс Сбрасывает результат выполнения всего таска

4. <img width="86" alt="image" src="https://github.com/IgorOvchar/create_project/assets/112720105/a439f3ca-d8ec-46fa-9680-5561c87e4ee2"> удаляет таск






