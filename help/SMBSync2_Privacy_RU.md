## 1.  Данные, записанные приложением

В приложении будет записан "Список задач синхронизации" и, в зависимости от настроек, "Запись о деятельности приложения". <span style="color: red; "><u>Кроме того, записанные данные не будут отправлены приложением, если только пользователь с ними не манипулировал.</u></span>

### 1.1. список синхронных задач

Приложение записывает данные, необходимые для выполнения синхронизации.
- Имя каталога, имя файла, имя хоста сервера SMB, IP-адрес, номер порта, имя учетной записи, пароль(***1**)
- Пароль приложения для защиты запуска приложений и изменения настроек(***1**)
- установочное значение приложения

***1** Он хранится в зашифрованном виде с помощью сгенерированного системой пароля, хранящегося в хранилище ключей Android.

### 1.2. учёт активности приложений

Приложение записывает следующие данные для верификации результатов синхронизации и устранения неполадок

- ерсия для Android, производитель устройства, название устройства, модель устройства и версия приложения
- Имя каталога, имя файла, размер файла и последнее измененное время файла
- Имя хоста сервера SMB, IP-адрес, номер порта и имя учетной записи
- Имя сетевого интерфейса, IP-адрес
- заданное значение системы
- установочное значение приложения

### 1.3. Экспортированный список синхронных задач

Приложение может записать в файл "1.1. список синхронных задач". Он может быть защищен паролем во время экспорта.
- Имя каталога, имя файла
- Имя хоста сервера SMB, IP-адрес, номер порта, имя учетной записи и пароль
- установочное значение приложения

### 1.4. Отправка записанных данных из приложения

Данные, записанные приложением, могут быть отправлены следующим образом:
- Нажмите кнопку "Отправить" на вкладке "История".
- Нажмите кнопку "Отправить разработчику" из "Системной информации".
- Нажмите кнопку "Поделиться" или "Отправить разработчику" из раздела "Управление лог-файлами".

## 2.  О разрешениях

Приложение использует следующие разрешения

### 2.1. Фотографии, мультимедиа и файлы

**-read the contents of your USB storage**  
**-modify or delete the contents of your USB storage**

Используется для синхронизации файлов во внутреннее хранилище и для чтения/записи административных файлов.

### 2.2. хранилище

**-read the contents of your USB storage**  
**-modify or delete the contents of your USB storage**

Используется для синхронизации файлов на USB-накопитель и для чтения/записи управленческих файлов.

### 2.3. Wi-Fi Подключение Информация

**view Wi-Fi connections**

Это используется для проверки состояния Wi-Fi при начале синхронизации.

### 2.4.Oстальные

### 2.4.1. view network connections

Это используется для проверки того, что вы подключены к сети, когда начинаете синхронизацию.

### 2.4.2.connect and disconnect from Wi-Fi

Используйте его для включения и выключения Wi-Fi с синхронизацией расписания.

### 2.4.3.full network access

Это используется для синхронизации по сети с использованием протокола SMB.

### 2.4.4.run at startup

Это используется для синхронизации расписания.

### 2.4.5.control vibration

Это используется для уведомления пользователя о завершении синхронизации.

### 2.4.6.prevent device from sleeping

Используйте его, чтобы начать синхронизацию с расписанием или внешним приложением.

### 2.4.7.install shortcuts

Используйте его для добавления ярлыка синхронного запуска на рабочий стол.

 