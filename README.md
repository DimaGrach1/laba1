## Лабораторная работа 1

1) Я перешел в директорию `Документы` и создал там каталог `laba1`, где, в свою очередь, создал файл `script.bash`
 
 ![Image alt](https://github.com/DimaGrach1/laba1/blob/assets/1.jpg)
   
2) С помощью команды `gedit script.bash` открыл только что созданный файл для редактирования и вписал в него необходимый скрипт. Сохранил файл и закрыл текстовый редактор gedit
 
![Image alt](https://github.com/DimaGrach1/laba1/blob/assets/2.jpg)

3) Затем выполнил в терминале команду `bash script.bash` и, действительно, терминал вывел строку `Welcome to ITMO University`
 
![Image alt](https://github.com/DimaGrach1/laba1/blob/assets/3.jpg)

4) Приступил к выполнению задачи. Открыл файл `script.bash` в текстовом редакторе gedit. С помощью дополнительных источников (https://stackoverflow.com/ и https://www.google.ru/) смог найти нужную информацию по языку программирования `bash` и написал скрипт, представленный ниже. После сохранил изменения и закрыл текстовый редактор gedit
   
```bash
#!/bin/bash

echo "Welcome, $@"
```

![Image alt](https://github.com/DimaGrach1/laba1/blob/assets/4.jpg)
   
5) С помощью команд `bash script.bash Vasya Pupkin` и `bash script.bash Benedict Timothy Carlton Cumberbatch` протестировал свой скрипт, получив требуемый результат
   
![Image alt](https://github.com/DimaGrach1/laba1/blob/assets/5.jpg)
