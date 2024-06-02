## В JavaScript new Date() является конструктором, который создает новый объект типа Date, представляющий текущую дату и время. Если вызвать new Date() без аргументов, будет создан объект, содержащий текущую дату и время. В этом объекте можно получить информацию о годе, месяце, дне месяца, часах, минутах, секундах и миллисекундах. Также с помощью методов этого объекта можно выполнять различные операции с датами и временем.

### С помошью пустого конструктора Date без параметров. В этом случае зданный объект хранит текущие дату и время

![alt text](code.png)

### В конструктор Date передается количества миллисекунд, которые прошли с начала эпохи, то есть с 1 января 1970 года 00:00:00 GMT:

![alt text](1.png)

### В конструктор Date передаются день, месяц и год:

![alt text](2.png)

### Четвертый способ состоит в передаче в конструктор Date всех параметров даты и времени:

![alt text](3.png)

### В данном случае используются по порядку следующие параметры: new Date(год, месяц, число, час, минуты, секунды, миллисекунды). При этом надо учитывать, что отсчет месяцев начинается с нуля, то есть январь - 0, а декабрь - 11.

# Получение даты и времени

### getDate(): возвращает день месяца
### getDay(): возвращает день недели (отсчет начинается с 0 - воскресенье, и последний день - 6 - суббота)
### getMonth(): возвращает номер месяца (отсчет начинается с нуля, то есть месяц с номер 0 - январь)
### getFullYear(): возвращает год

![alt text](4.png)
![alt text](5.png)

### getHours(): возвращает час (от 0 до 23)
### getMinutes(): возвращает минуты (от 0 до 59)
### getSeconds(): возвращает секунды (от 0 до 59)
### getMilliseconds(): возвращает миллисекунды (от 0 до 999)
### getTime(): возвращает числовое значение, соответствующее указанной дате по всемирному координированному времени. 

![alt text](104.png)

# Установка даты и времени

## Кроме задания параметров даты в конструкторе для установки мы также можем использовать дополнительные методы объекта Date:

### setDate(): установка дня в дате
### setMonth(): уставовка месяца (отсчет начинается с нуля, то есть месяц с номер 0 - январь)
### setFullYear(): устанавливает год
### setHours(): установка часа
### setMinutes(): установка минут
### setSeconds(): установка секунд
### setMilliseconds(): установка миллисекунд

![alt text](106.png)

### setTime() устанавливает время объекта Date в значение, представляемое количеством миллисекунд, прошедших с 1 января 1970 00:00:00

![alt text](107.png)
