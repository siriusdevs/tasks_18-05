## 1
Запустить 5 процессов, управляющих одной общей блокировкой. Каждый из процессов:
запускается, запрашивает монопольную блокировку на работу, сообщает о начале своей
работы, спит одну секунду, сообщает об окончании своей работы, освобождает блокировку,
ожидает остальные процессы, завершается и выводит сообщение об этом. Все процессы
проделывают свою работу и ждут друг друга, и завершаются только тогда, когда закончат
работу все. После завершения всех процессов вывести сообщение об этом. Запустить процессы
одновременно. Процессы должны выполниться последовательно, несмотря на одновременный
запуск. Выполнить через создание объектов класса Process, передавая функцию процесса через target
## 2
Написать программу, в которой студенты выполняют практические работы на компьютере. За
компьютером одновременно могут работать два студента. Всего студентов пять. Занятие
заканчивается, когда все студенты завершают выполнение работы. Каждый студент
запрашивает доступ на компьютер, и когда он его получает, он сообщает, что начинает работу
за компьютером и будет выполнять её определенное количество времени (случайное время в
заданном в классе интервале). Потом он спит это время, после чего сообщает о завершении
работы и освобождает место за компьютером. После этого он ждёт, когда закончится занятие.
Когда все студенты выполнят работу, занятие завершается, и об этом выводится сообщение.
Выполнить через наследование класса от Process
