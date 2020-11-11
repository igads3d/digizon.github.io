# Отчет о лабораторных работах
# студент группы [ИДБ-17-07](https://github.com/stankin/design-part-1/wiki/List-IDB-17-07) Сичинава М.В.

## Лабораторная 1
### Задача: слесарь с помощью сварочного аппарата и ножниц по металлу делает мангал из обрезков арматуры и листов трехмиллиметровой стали по запросу родителей.
![pic](https://raw.githubusercontent.com/igads3d/digizon.github.io/master/lab1/01_A0.png)

### Диаграмма классов
![pic](https://raw.githubusercontent.com/igads3d/digizon.github.io/master/lab1/class.png)

### Usecase-диаграмма
![pic](https://raw.githubusercontent.com/igads3d/digizon.github.io/master/lab1/usecase.png)


## Лабораторная 2
### Контекстная модель
![pic](https://raw.githubusercontent.com/igads3d/digizon.github.io/master/lab2/ramus-2-1.png)

### PDC
![pic](https://raw.githubusercontent.com/igads3d/digizon.github.io/master/lab2/ramus-2-2.png)

### DFD
![pic](https://raw.githubusercontent.com/igads3d/digizon.github.io/master/lab2/ramus-2-3.png)

## Лабораторная 3
![pic](https://raw.githubusercontent.com/igads3d/digizon.github.io/master/lab3/erd.png)
### В БД услуг находтся заявки на оказание услуг, для каждой из которых требуются денежные средства, код услуги и номер телефона клиента. Информация из БД доступна для пользования в системе ERP

![pic](https://raw.githubusercontent.com/igads3d/digizon.github.io/master/lab3/seq.png)
### Покупатель, регистрирует заявку на оказание услуги в биллинг системе. Она генерирует запрос на создание ссылки на оплату на кассе или терминале оплаты, после чего возвращает ссылку на портал эквайринга клиенту. Как только оплата успешно прошла, код услуги отправляется на сервер ERP для создания заявки на выполнения задачи и изменения состояния расходных материалов. Эта информация фиксируется в БД. В последствии, управляюшему серверу возвращается сообщение об успешном изменении соответствующих строк в БД, а тот, в свою очередь, возвращает биллинг-системе статус успешности предоставления услуги, откуда эта информация переходит к клиенту.

## Лабораторная 4

## Лабораторная 5

## Лабораторная 6
