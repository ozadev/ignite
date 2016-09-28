#Homework 

###Задача 1 
Создайте HTTP сервер, который записывает заголовки каждого запроса в отдельный файл. При обработке каждого запроса должен создаваться отдельный файл, имя которого - номер запроса(1 - для первого запроса, 2 - для второго и т.д.).

###Задача 2 
Добавьте в код предыдущей задачи код, отправляющий POST запрос по пути '/test'. Тело запроса - произвольный текст. Ответ сервера должен быть в формате JSON в следующем виде: '{"message": "ТЕКСТ ТЕЛА ЗАПРОСА"}'.   

###Задача 3 
Добавьте в код предыдущих задач обработку ошибок: при запросе по несуществующему пути(все пути, кроме '/' и '/test'(с POST запросом)) на экран должно выводиться сообщение об ошибке, а статус-код ответа сервера должен быть 404.  