# Пример иснтрументов, для разработки по тоше.
### GUI_TOOL  утилита для просмотра, графика зависимости длинны сигнала, от прочитанного значения
  Получает данные по сокет соединению, подключаясь к порту 5000 
### SERIAL_TOOL утилита для чтения с ардуинны данных
  Получает данные из ардуино десериализует и отправляет по 5000 порту через сокет соединение  
  `ВНИМАНИЕ!! надо указать port в code`

### Instalation
  pip3 install -r requirements.txt

### Usage
  Первой запускаем serial tool
  Затем запускаем gui tool

### Рекомендации 
  Получение данных, и их запись осуществить, внутри serial tool

### Полезные ссылки
  * [Статья тоше](https://s3-us-west-1.amazonaws.com/disneyresearch/wp-content/uploads/20140805145650/touchechi20121.pdf)
  * [DIY CODE](https://github.com/damellis/ESP/wiki)