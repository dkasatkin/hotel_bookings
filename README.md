# hotel_bookings
:hotel: :airplane: Analysis of hotel booking data

Here is an analysis of hotel reservations <br/>
Dataset variables and tasks are specified at the beginning of file "hotel_bookings.ipynb


### Dataset data ### 

* <span style="color:red"><b>Hotel</b></span> – тип отеля (<span style="color:blue">City Hotel</span> или <span style="color:blue">Resort Hotel</span>)  
* <span style="color:red"><b>Is canceled</b></span> – бронирование было отменено -> <span style="color:blue">1</span> или <span style="color:blue">0</span> -> нет; не отмененное считается успешным
* <span style="color:red"><b>Lead time</b></span> – количество дней, прошедших между датой бронирования и датой прибытия  
* <span style="color:red"><b>Arrival full date</b></span> – полная дата прибытия
* <span style="color:red"><b>Arrival date year</b></span> – год прибытия  
* <span style="color:red"><b>Arrival date month</b></span> – месяц прибытия  
* <span style="color:red"><b>Arrival date week number</b></span> – номер недели прибытия
* <span style="color:red"><b>Arrival date day of month</b></span> – день прибытия
* <span style="color:red"><b>Stays in weekend nights</b></span> – количество выходных (<span style="color:blue">суббота</span> или <span style="color:blue">воскресенье</span>), которые гость забронировал для проживания в отеле
* <span style="color:red"><b>Stays in week nights</b></span> – количество дней (с понедельника по пятницу), которые гость забронировал для проживания в отеле
* <span style="color:red"><b>Stays total nights</b></span> – общее число забронированных ночей (сумма двух предыдущих колонок)
* <span style="color:red"><b>Adults</b></span> – число взрослых
* <span style="color:red"><b>Children</b></span> – число детей
* <span style="color:red"><b>Babies</b></span> – число младенцев 
* <span style="color:red"><b>Meal</b></span> – выбранный тип питания
* <span style="color:red"><b>Country</b></span> – страна происхождения клиента
* <span style="color:red"><b>Reserved room type</b></span> – тип зарезервированного номера
* <span style="color:red"><b>Assigned room type</b></span> – тип полученного номера (может отличаться от забронированного)
* <span style="color:red"><b>Customer type</b></span> – тип бронирования
* <span style="color:red"><b>Reservation status</b></span> – значение последнего статуса брони: <span style="color:blue">Canceled</span> - было отменено клиентом; <span style="color:blue">Check-Out</span> - клиент зарегистрировался, но уже покинул отель; <span style="color:blue">No-Show</span> - клиент не зарегистрировался и сообщил администрации отеля причину
* <span style="color:red"><b>Reservation status date</b></span> – дата обновления статуса
