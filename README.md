﻿# ParkingLotWebAPI

Academy'18 • 2nd stage • 3. .NET Core
На основі домашньої роботи №2 необхідно реалізувати ASP.NET Core Web API додаток (не потрібно розробляти графічний інтерфейс).

Для тестування роботи додатка можна скористатися наступними тулзами: Postman (https://www.getpostman.com/) або Fiddler (https://www.telerik.com/fiddler)


__REST API:__


__Parking__


| URL | Description |
| --- | --- |
| http://localhost:59687/api/ParkingLot/ParkingFreeSpaces | Кількість вільних місць (GET) |
| http://localhost:59687/api/ParkingLot/ParkingOccupiedSpaces | Кількість зайнятих місць (GET) |
| http://localhost:59687/api/ParkingLot/ParkingBalance | Загальний дохід (GET) |



__Cars__

| URL | Description |
| --- | --- |
| http://localhost:59687/api/ParkingLot/ShowAllCars | Список всіх машин (GET) |
| http://localhost:59687/api/ParkingLot/ShowCarDetails/{id} | Деталі по одній машині (GET) |
| http://localhost:59687/api/ParkingLot/RemoveCar/{id} | Видалити машину (DELETE) |
| http://localhost:59687/api/AddCar/{type}/{id} | Додати машину (POST) |
| http://localhost:59687/api/ParkingLot/RefillCarBalance/{id}/{sum} | Поповнити баланс машини (PUT) |



__Transactions__


| URL | Description |
| --- | --- |
| http://localhost:59687/api/ParkingLot/ReadTransactionLog| Вивести Transactions.log (GET) |
| http://localhost:59687/api/ParkingLot/LastMinuteTransactions | Вивести транзакції за останню хвилину (GET) |
| http://localhost:59687/api/ParkingLot/CarTransactionLastMinute/{id} | Вивести транзакції за останню хвилину по одній конкретній машині (GET) |


