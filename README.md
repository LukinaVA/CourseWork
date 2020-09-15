# CourseWork
SPbPU / Spring 2020 / Java

Клиент-серверное приложение.

Сервер:
- работа с БД H2
- SpringData/Hibernate для работы с БД
- Spring Security
  * проверка подлинности пользователя и обеспечении безопасности данных обеспечиваются с помощью JSON Web Tokens (JWT)
- взаимодействие с клиентом осуществляется посредством REST API

В работе реализована трехуровневая модель клиент-сервер. Клиентский слой — интерфейс пользователя, в нашем случаем веб-браузер, которому отправляются HTML-страницы. Слой логики — сервер, на котором происходит обработка запросов/ответов. Слой данных — сервер баз данных: к нему обращается наш сервер. В этом слое сохраняется вся необходимая информация, которой пользуется приложение при работе.

