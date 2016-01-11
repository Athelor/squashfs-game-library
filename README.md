# squashfs-game-library
Набор bash-скриптов для упаковки и запуска игр на squashfs <br>

Основные файлы: <br>
scripts/gamepacker  программа для автоматической упаковки игр и настройки конфигурационных файлов (для работы необходим kdialog) <br>
scripts/mounter     скрипт для монтирования squashfs для его корректной работы необходимо разрешить его исполнение без пароля в /etc/sudoers  <br>
scripts/run-games   основная программа для запуска игр (для работы необходим kdialog или zenity) <br>

примеры файлов конфигурации размещены в conf-samples <br>

пример расположения файлов в игровой директории <br>
.<br>
├── game<br>
├── game1.fs<br>
├── game2<br>
├── geme2.fs<br>
├── envs<br>
│   ├── game-list<br>
│   ├── LIB_game1<br>
│   └── LIB_game4<br>
├── scripts<br>
│   ├── gamepacker<br>
│   ├── mounter<br>
│   └── run-games<br>
├── game<br>
├── game3.fs<br>
├── srt_need<br>
├── steam-runtime<br>
├── steam-runtime.fs<br>
├── game4<br>
└── game4.fs<br>

пример строки в /etc/sudoers для scripts/mounter расположенного в /usr/local/bin<br>
%wheel  ALL =  NOPASSWD:/usr/local/bin/mounter<br>

