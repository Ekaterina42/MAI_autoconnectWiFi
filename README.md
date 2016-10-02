Windows:
-------------------------
Для автоподключения на Windows была написана служба.
Чтобы установить её - необходимо запустить файл install.bat **от имени администратора** (Для удаления - запустите uninstall.bat, также от имени администратора).

Испольняемый файл, библиотека и uninstall.bat будут скопированы в `Program Files\CorruptedProject\MAIautoconnect` и запускаться оттуда. 

*NIX:
-------------------------
Bash скрипт. Перед запуском необходимо выдать права на исполнение `chmod +x FILENAME` (Также можно установить скрипт командой `bash ScriptName i` и тогда права на исполнение будут установлены автоматически).
Перед установкой желательно проверить работоспособность - просто запустив скрипт. 
Полезно знать некоторые дополнительные опции при запуске:
* h[elp] - выводит необходимую информацию.
* i[nstall] - установка
* u[ninstall] - удаление

Скрипт требует установленных:
* iwgetid
* crontab

MAC:
-------------------------
Почти тоже самое, что и скрипт для *NIX систем, но с некоторыми особенностями.
**Для этой системы скрипт не тестировался!**
