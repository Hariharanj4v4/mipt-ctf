CTF на Физтехе
==============

Курс по подготовке к соревнованиям по компьютерной безопасности формата CTF.
Занятия проходят по средам в 20:00 в 202 ЛК.

Каждое занятие состоит из небольшой лекции и практики в виде решения задачек на определенную тему.
Предварительная подготовка не требуется.
Желательно наличие собственного компьютера, но пользоваться компьютерами в аудитории тоже возможно.

[Группа ВКонтакте](https://vk.com/mipt_ctf).

## Прошедшие занятия

**28 октября.** [Компьютерная безопасность. Что такое CTF. Attack-defence, jeopardy (task-based). УК РФ. Командная оболочка bash. Полезные команды и утилиты.](https://github.com/xairy/mipt-ctf/tree/master/01-intro/01-bash)

**11 ноября.** [Язык программирования Python. Основы синсаксиса. Некоторые полезные модули.](https://github.com/xairy/mipt-ctf/tree/master/01-intro/02-python)

**18 ноября.** [Менеджер пакетов Pip. Функция eval. Как выбраться из sandbox'а в Python с помощью эксплуатации функции eval.](https://github.com/xairy/mipt-ctf/tree/master/01-intro/03-eval)

**25 ноября.** [Кодировки. ASCII, ANSI Code Pages, Unicode, UTF-8/16/32. Base64. Классические шифры. Шифр Цезаря. Шифр простой замены. Частотный анализ. Шифр Вижинера. Индекс совпадений. Одноразовый блокнот. Современные симметричные шифры. DES, 3DES, AES.](https://github.com/xairy/mipt-ctf/tree/master/02-crypto/01-symmetric)

**2 декабря.** [Асимметричные шифры. Протокол Диффи-Хеллмана. RSA. Электронная цифровая подпись. Сертификат открытого ключа. Как работает HTTPS.](https://github.com/xairy/mipt-ctf/tree/master/02-crypto/02-asymmetric)

**24 февраля.** [Криптографические хеш-функции (MD5, SHA-1, SHA-2, SHA-3, bcrypt). Обзор реализации MD5. Length extension attack. Как хранить пароли пользователей. Как ломать хеши. John the Ripper, hashcat.](https://github.com/xairy/mipt-ctf/tree/master/02-crypto/03-hashing)

**2 марта.** [Стеганография. Основные понятия. Least Significant Bit (LSB). Контейнеры: текст, изображения, аудио, видео. Стегоанализ.](https://github.com/xairy/mipt-ctf/tree/master/02-crypto/04-stego)

**9 марта.** [Модель OSI. Стек TCP/IP. Протоколы IP, TCP, UDP. netcat, nmap, nestat, ping. Основы HTTP. Методы, заголовки, cookies, авторизация. Session hijecking attack. HTML. curl, wget, lynx, tcpdump. Python requests. Browser development tools. Полезные плагины для браузеров.](https://github.com/xairy/mipt-ctf/tree/master/03-web/01-http)

**16 марта.** [Различные типы веб уязвимостей. OWASP Top 10. Injections: SQL, Command, Log. RFI, LFI. XSS, CSRF. Full path disclosure. .git, .svn. .hg. .htaccess, .htpasswd. Malicious file upload. robots.txt, sitemap.xml. Bug bounty.](https://github.com/xairy/mipt-ctf/tree/master/03-web/02-vulns)

**23 марта.** [SQL инъекции. Error-based. Blind (content-based, time-based). Union-based. Stacked queries. Поиск. Защита. Web Application Firewall. Cheat Sheets. sqlmap.](https://github.com/xairy/mipt-ctf/tree/master/03-web/03-sqli)

**30 марта, 6, 13, 20 апреля.** [Серия занятий по ассемблеру.](https://github.com/xairy/mipt-ctf/tree/master/04-binary/01-asm)

**27 апреля.** [Reverse engineering. Ассемблеры. Форматы бинарных файлов. ELF. Утилиты: file, strings, readelf, objdump, nm, ldd. Дизассемблеры: objdump, IDA Pro, Hopper, radare2, ODA. Декомпиляторы: Hex-Rays, Hopper. Дебаггеры: strace, ltrace, gdb, qira. Hex редакторы: ghex, hexdump, xxd.](https://github.com/xairy/mipt-ctf/tree/master/04-binary/02-reverse)

**4 мая.** [Бинарные уязвимости. Buffer-overflow: shellcodes, return-to-libc. Format-string-vulnerability: arbitrary read, arbitrary write, overwriting GOT. Дебаг эксплоитов с помощью gdb.](https://github.com/xairy/mipt-ctf/tree/master/04-binary/03-exploits)

## План на 2015-2016

Предварительный план того, что возможно будет в этом году.

* Binary
    * Buffer overflow. Shellcode. Non-executable stack, stack canaries, ASLR, RELRO. checksec.sh. String format exploit. Overwriting PLT. Controlling gdb environment, keeping stdin open.
    * ROP. return-to-libc. gadgets, gadget finders. python struct, zio. Bypassing ASLR on x32. Heap buffer overflow.
