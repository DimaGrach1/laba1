## Лабораторная работа 1

1) Я перешел в директорию `Документы` и создал там каталог `laba1`, где, в свою очередь, создал файл `script.bash`
2) 
   [!IMG](https://github.com/DimaGrach1/laba1/blob/3d6e0e77337be7ab46e2a70c4e73c65c89ecce21/1.jpg)
   
3) С помощью команды `gedit script.bash` открыл только что созданный файл для редактирования и вписал в него необходимый скрипт. Сохранил файл и закрыл редактор текста gedit
4) 
   [!IMG](https://github.com/DimaGrach1/laba1/blob/3d6e0e77337be7ab46e2a70c4e73c65c89ecce21/2.jpg)

5) Затем выполнил в терминале команду `bash script.bash` и, действительно, терминал вывел строку `Welcome to ITMO University`
6) 
   [!IMG](https://github.com/DimaGrach1/laba1/blob/3d6e0e77337be7ab46e2a70c4e73c65c89ecce21/3.jpg)

7) Приступил к выполнению задачи. Открыл файл `script.bash` в текстовом редакторе gedit. С помощью дополнительных источников (https://stackoverflow.com/ и https://www.google.ru/) смог найти нужную информацию по языку программирования `bash` и написал скрипт, представленный ниже. После сохранил изменения и закрыл текстовый редактор gedit
   
```bash
#!/bin/bash

echo "Welcome, $@"
```

   [!IMG](https://github.com/DimaGrach1/laba1/blob/3d6e0e77337be7ab46e2a70c4e73c65c89ecce21/4.jpg)
   
5) С помощью команд `bash script.bash Vasya Pupkin` и `bash script.bash Benedict Timothy Carlton Cumberbatch` протестировал свой скрипт, получив требуемый результат
   
   [!IMG](https://github.com/DimaGrach1/laba1/blob/3d6e0e77337be7ab46e2a70c4e73c65c89ecce21/5.jpg)
