# Конспекты по DevOps

## Linux

### Быстрый доступ

- [Команды Docker и примеры](01%20-%20linux/7-soa-and-docker/docker-commands-and-examples.md) — образы, запуск контейнеров, порты, логи, exec, остановка и удаление.
- [Практические задания по Linux](01%20-%20linux/practice/linux-fundamentals-exercises.md) — 20 заданий по теории, командам, файлам, потокам и анализу журналов.
- [Команды и примеры](01%20-%20linux/2-working-in-terminal-and-commands/commands-and-examples.md) — `pwd`, `cd`, `ls`, `touch`, `mkdir`, `rm`, `rmdir`, `cat`, `less`, `cp`, `head`, `wc`, `grep`, `id`, `chmod`.
- [Ввод, вывод, перенаправления и конвейеры](01%20-%20linux/2-working-in-terminal-and-commands/streams-redirection-and-pipes.md) — `stdin`, `stdout`, `stderr`, `>`, `>>`, `<`, `2>`, `|`.

### 1. Основы Linux — `1-history-linux`

| Файл                                                                                       | Что внутри                                                  |
| ------------------------------------------------------------------------------------------ | ----------------------------------------------------------- |
| [os-kernel-and-distributions.md](01%20-%20linux/1-history-linux/os-kernel-and-distributions.md)     | Устройство ОС, ядро, окружение и дистрибутивы Linux         |
| [networking-ipv4-tcp-udp-ports.md](01%20-%20linux/1-history-linux/networking-ipv4-tcp-udp-ports.md) | Основы сетевого взаимодействия: OSI, IPv4, TCP, UDP и порты |

### 2. Терминал и команды — `2-working-in-terminal-and-commands`

| Файл                                                                                                          | Что внутри                                      |
| ------------------------------------------------------------------------------------------------------------- | ----------------------------------------------- |
| [bash-shell-and-command-syntax.md](01%20-%20linux/2-working-in-terminal-and-commands/bash-shell-and-command-syntax.md) | Оболочка, приглашение Bash, опции и аргументы   |
| [commands-and-examples.md](01%20-%20linux/2-working-in-terminal-and-commands/commands-and-examples.md)                 | Справочник команд с опциями и примерами         |
| [streams-redirection-and-pipes.md](01%20-%20linux/2-working-in-terminal-and-commands/streams-redirection-and-pipes.md) | Стандартные потоки, перенаправления и конвейеры |

### 3. Файлы и права — `3-files-and-rules`

| Файл                                                                                           | Что внутри                                              |
| ---------------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| [filesystem-paths-and-filenames.md](01%20-%20linux/3-files-and-rules/filesystem-paths-and-filenames.md) | Файловая система, каталоги, пути, имена и скрытые файлы |
| [files-and-access-permissions.md](01%20-%20linux/3-files-and-rules/files-and-access-permissions.md) | Пользователи и группы, системные файлы учётных записей, аутентификация, ссылки, SUID и chmod |

### 4. Регулярные выражения — `4-regular-expressions`

| Файл | Что внутри |
| --- | --- |
| [regular-expressions.md](01%20-%20linux/4-regular-expressions/regular-expressions.md) | Шаблоны поиска, классы символов, повторения, группы и примеры с `grep` |

### 5. Программирование на Bash — `5-bash`

| Файл | Что внутри |
| --- | --- |
| [bash.md](01%20-%20linux/5-bash/bash.md) | Коды возврата, &&/\|\|, переменные, окружение, for, скрипты и файлы настройки |
| [test.sh](01%20-%20linux/5-bash/test.sh) | Пример скрипта с циклом for |

### 6. Веб-сервисы — `6-webservices`

| Файл | Что внутри |
| --- | --- |
| [webservices.md](01%20-%20linux/6-webservices/webservices.md) | HTTP, Apache, Nginx, обратный прокси, пакеты, службы, порты, конфигурация сайтов и DNS |

### 7. SOA, виртуализация и Docker — `7-soa-and-docker`

| Файл | Что внутри |
| --- | --- |
| [theory.md](01%20-%20linux/7-soa-and-docker/theory.md) | Монолит и сервисы, VM и контейнеры, образы, хранение данных и сеть Docker |
| [docker-commands-and-examples.md](01%20-%20linux/7-soa-and-docker/docker-commands-and-examples.md) | Отдельный справочник Docker CLI с опциями, примерами и сценарием запуска Nginx |
