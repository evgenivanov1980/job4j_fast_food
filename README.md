# job4j_fast_food"
Это учебный проект в котором создается приложение по доставке еды. Приложение построено на микросервисах
Что такое микросервисная система?

Микросервисная система - это система, использующая микросервисную архитектуру.

Микросервисная архитектура - это такой подход разработки ПО, при котором система или бизнес-логика разбивается на микросервисы, каждый из которых имеет свое предназначение.

Микросервис - это как правило, отдельно взятое приложение, решающее поставленные перед ним задачи. Сам микросервис уже может иметь

монолитную архитектуру, т.к. представляет собой небольшое приложение.

Взаимодействие между микросервисами происходит по API, которое они друг другу предоставляют. Например, они могут "общаться" через REST API.

"Общение" происходит в рамках одной подсети.

В совокупности, взаимодействие с системой, использующей микросервисы происходит через так называемое API Gateaway - API, открытое внешнему

миру.

Сервисы бывают state и stateless. Первые обладают состоянием и поэтому являются микросервисами пользовательского интерфейса (веб-сайт, веб-

приложение), поэтому пользователь может взаимодействовать с системой также через них. Причем, эти сайты и приложения могут быть как частью

инфраструктуры системы, так и сторонними ресурсами, использующими API Gateaway.

stateless представляют собой серверные приложения.