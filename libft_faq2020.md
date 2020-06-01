*Этот пост/статья для тех, кто также, как я, начал плыть, постоянно гуглит и собирает разрозненную инфу. Надеюсь будет полезно. Полезные ссылки по проекту libft.*

## 0. Как сделать такую статью
1. Ставите разрешение .md
2. Работаете с разметкой [Markdown](https://github.com/sandino/Markdown-Cheatsheet)

## 1. Мakefile - как в нем разобраться
Сначала читаете вот это:
1. [Вот тут есть все](http://linux.yaroslavl.ru/docs/prog/gnu_make_3-79_russian_manual.html)
2. [Про ar](https://ru.wikipedia.org/wiki/Ar_(Unix))

Потом используете все эти штуки:
**NAME = hello.a"** - делаем шаблон;
**$(NAME)** - обращаемся к шаблону;
**@** - скрываем действия;
**echo ""** - подписываем;
**%.o : %.c** - шаблонные правила; 
**$?**, **$< -o $@** - автоматические переменные;
**.PHONY:** - абстрактные цели.

## 2. Чекеры, но их можно нагуглить еще
- [Libftest](https://github.com/jtoty/Libftest/blob/master/README.md)
- [libft-unit-test](https://github.com/alelievr/libft-unit-test)
- [libft-war-machine](https://github.com/ska42/libft-war-machine) (вот этот раотает лучше всего)

## 3. Полезные статьи от других пиров
1. [Libft FAQ (mid 2020) by Sky](https://github.com/sky-183/42_faq)
2. [Libft FAQ by ayellinү](https://paper.dropbox.com/doc/LIBFT-5TCwT0vJEPasSgd3m6bW)
3. [Полезный блог о учебе в Школе 21](https://42-21-school.blogspot.com/)

## 4. Если у вас стоит винда, и вы не хотите ставить линукс
1. Можно поставить MINGW64 и [доустановить](https://coderoad.ru/9427356/%D0%9A%D0%B0%D0%BA-%D1%81%D0%BA%D0%BE%D0%BC%D0%BF%D0%B8%D0%BB%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D1%82%D1%8C-Clang-%D0%BD%D0%B0-Windows) [clang](https://superuser.com/questions/1505283/how-to-install-clang-format-on-mingw-windows)
2. [Или Linux в Windows 10](https://docs.microsoft.com/ru-ru/windows/wsl/install-on-server)
3. [Превращаем Windows в Ubunu](https://youtu.be/tD7jN5A7GE8)

## 5. VIM
- [Хэдэр в вим](https://github.com/pbondoer/vim-42header)

## 6. Лайфхаки
- Гуглите названия функций в слаке, и читайте треды, там бывает много полезной информации
- Внимательно читайте ман. Очень внимательно
- Если зашли в тупик, выставляйте слоты, проверяйте, общайтесь, учитесь у других пиров
- Я просто писал в слаке запросы на созвон, и созванивался с теми, кто былл готов поболтать (вы скорей всего уже будете учиться в оффлайне, поэтому такой проблемы не будем, можно будет спросить у соседей)
