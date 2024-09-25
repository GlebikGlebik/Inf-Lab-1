## Отчет о лабораторной работе 1 

1. Создаем новый файл с именем `script.bash`:

![image](https://github.com/user-attachments/assets/2db8c8f8-4353-486a-9b6f-4ebd934fe5e9)

![2](https://github.com/user-attachments/assets/a343de2f-ef40-4812-bf5a-a51ff771f3de)

2. Открываем наш файл `script.bash` в редакторе с помощь терминала:

![image](https://github.com/user-attachments/assets/cce6204a-b238-4d21-9f57-def490a208f6)

![image](https://github.com/user-attachments/assets/94a644db-f0d9-4a2b-92ee-955b9211fb25)

3. Вписываем в файл `script.bash ` скрипт, который будет выводить приветственное сообщение в терминале:

![image](https://github.com/user-attachments/assets/a43f5ade-a472-49f9-8d2b-16737e29d050)

4. Вызываем наш bash-скрипт:

![image](https://github.com/user-attachments/assets/126730b5-ef8e-4f49-a38f-f7b69f47e9a1)

### Задача:

Модифицируйте файл `script.bash` так, чтобы при его запуске в терминале в виде:

`bash script.bash Vasya Pupkin`

программа выводила:

`Welcome, Vasya Pupkin`

### Решение:

Снова открываем наш файл со скриптом и переписываем код на следующий:

![image](https://github.com/user-attachments/assets/93286d96-1dea-490e-9a1f-47ffcb3bf4e6)

![image](https://github.com/user-attachments/assets/87842c1e-ba4b-47b3-a5ca-6fd6bc9206b8)

Функция `$*` считывает информацию напрямую из терминала, добавляя ее в функцию `echo` в нашем скрипте, на выходе мы получаем:

![image](https://github.com/user-attachments/assets/ee27301e-f2ef-41de-9ffa-dbb92d2d6723)

Задание выполнено. 


