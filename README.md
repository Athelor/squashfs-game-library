# squashfs-game-library
Набор bash-скриптов для упаковки и запуска игр на squashfs <br>

Основные файлы: <br>
scripts/gamepacker  программа для автоматической упаковки игр и настройки конфигурационных файлов (для работы необходим kdialog) <br>
scripts/mounter     скрипт для монтирования squashfs для его корректной работы необходимо разрешить его исполнение без пароля в /etc/sudoers  <br>
scripts/run-games   основная программа для запуска игр (для работы необходим kdialog или zenity) <br>

примеры файлов конфигурации размещены в conf-samples 
