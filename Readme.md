# Mission 2

## Part 0

[Link to video] https://drive.google.com/file/d/1QP2W1T3Q7-IZylPcyA7enEgrNl22Sbg4/view?usp=drive_link

## Part1

- Вопрос 1	 
 Зачем нужен SSH?
> Ответ  
SSH (Secure Shell) нужен для безопасного удаленного доступа к серверам. Он шифрует соединение, что позволяет безопасно управлять сервером, выполнять команды и передавать данные. Это особенно важно, когда сервер находится в другом месте, а вам нужен доступ к нему через интернет.

- Вопрос 2
Как добавить SSH-ключ Васи на сервер?
	 
> Ответ  
Чтобы Вася мог подключиться к серверу, его публичный ключ нужно добавить в файл ~/.ssh/authorized_keys на сервере. Для этого:
Открыть файл ~/.ssh/authorized_keys (если его нет — создайте).
Добавить строку с публичным ключом Васи и сохраните файл.
Теперь Вася сможет подключиться через SSH с использованием своего приватного ключа.

- Вопрос 3
 Что такое long polling и webhooks?
	 
> Ответ  
Long polling — это техника, при которой клиент отправляет запрос на сервер и "ждет", пока появится новый ответ. Если данных нет, сервер удерживает соединение открытым до тех пор, пока не появятся данные.
Webhooks — это способ, при котором сервер сам отправляет данные клиенту, когда происходит определенное событие. Клиент заранее указывает серверу URL, на который отправлять данные.
Оба метода используются для обработки обновлений в реальном времени, но webhooks экономят больше ресурсов, так как не требуют постоянных запросов.

- Вопрос 4
Что такое issues на GitHub и для чего они нужны?
	 
> Ответ  
Issues на GitHub — это система для отслеживания задач, ошибок, предложений и обсуждений по проекту. Они позволяют разработчикам и пользователям сообщать об ошибках, предлагать улучшения или отслеживать прогресс работы. Это важный инструмент для управления проектами с открытым исходным кодом и эффективного взаимодействия между командой разработчиков и сообществом.
- Вопрос 5	 
Как добавить пустую папку в Git?
> Ответ  
Git не отслеживает пустые директории, но есть обходной путь. Чтобы сохранить пустую папку в репозитории, можно создать в ней файл-заглушку, например, .gitkeep. Этот файл позволит Git отслеживать папку, даже если она пока пуста