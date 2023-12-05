### Задание
Создайте пустой проект и репозиторий HW19. Запуште readme файл, а затем создайте новую ветку, где будете добавлять скриншоты.
Когда будет готово, то сделайте пул реквест

Выполните команды и приложите скриншоты после каждого действия
Для выполнения задания в докере
docker pull ubuntu
docker run -dit ubuntu
docker ps <- получить ID контейнера
docker exec -it id
Либо используйте SSH, для того, чтобы подключиться к серверу. Логин и пароль будет выслан каждому индивидуально


Переместитесь в ваш домашний каталог.
Используя команду pwd, убедитесь, что вы находитесь в правильной директории.
Создайте новую директорию с названием "UnixPractice".
Войдите в эту директорию.
С использованием nano, создайте текстовый файл с именем "application_logs.txt".
Введите  в файл
- [2023-11-22 18:42:10] DEBUG Initializing application
- [2023-11-22 18:42:12] ERROR Unable to open file /var/log/myapp.log
- [2023-11-22 18:42:14] INFO Connecting to database
- [2023-11-22 18:42:16] ERROR Failed to send email notification
- [2023-11-22 18:42:18] INFO Database connection established
- [2023-11-22 18:42:20] INFO Loading user data
- [2023-11-22 18:42:22] ERROR Application encountered an unexpected error
- [2023-11-22 18:42:24] INFO User data loaded successfully
- [2023-11-22 18:42:26] INFO Rendering application UI
- [2023-11-22 18:42:28] ERROR Unable to connect to external service
- [2023-11-22 18:42:30] INFO Application UI rendered successfully
- Используя команду cat, посмотрите содержания файла.
- Используя команду grep, найдите ERROR логи
- Скопируйте файл "application_logs.txt" в новый файл "backup_application_logs.txt"
- Убедитесь, что файл создан
- Удалите файл "application_logs.txt"
- Убедитесь, что файл был удален
- Создайте копию директории "UnixPractice" с именем "UnixBackup" с использованием команды cp.
- Удалите исходную директорию "UnixPractice" с использованием команды rm.
-Убедитесь, что директория "UnixBackup" создана и содержит те же файлы, что и "UnixPractice".
