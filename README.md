# Гайды

Здесь я собрала закреплённую инфу из слака и тг каналов по проектам. Да и вообще всё, что может пригодиться для сдачи проектов на интре.

Содержание
----------
**Common-core**
- [Libft](#libft)
- [Born2beroot](#b2b)
- [ft_printf](#printf)
- [get_next_line](#gnl)
- [push_swap](#push_swap)
- [pipex](#pipex)
- [minitalk](#minitalk)
- [so_long](#so_long)
- [FdF](#fdf)
- [fract-ol](#fract_ol)
- [Philosophers](#philo)
- [minishell](#minishell)
- [cub3d](#cub3d)
- [miniRT&cub3d](#minirt_cub3d)
- [NetPractice](#netpractice)
- [CPP_Piscine](#cpp)
- [Inception](#inception)
- [ft_containers](#containers)
- [ft_irc](#irc)
- [webserv](#webserv)

**Экзамены**

**Проекты за кругом**
- [ft_linear_regression](#linear_regression)

**Сабджекты**

**Чек-листы**

**Книги**


# Common-core

<a name="libft">Libft</a>  
----------

[Unit-тесты](https://github.com/alelievr/libft-unit-test)

<a name="b2b">Born2beroot</a>  
----------

[Материалы](https://gitlab.com/NickKeepKind/born2beroot) по проекту, собранные @kreginal, включая видео от @mmargene

<a name="printf">ft_printf</a>  
----------
@meunostu собрал собрал тесты ft_printf  
[Тест 1](https://github.com/charMstr/printf_lover_v2)  
[Тест 2](https://github.com/Mazoise/42TESTERS-PRINTF)  
[Тест 3](https://github.com/cacharle/ft_printf_test)  
[Тест 4](https://github.com/gavinfielder/pft)  
[Тест 5](https://github.com/cclaude42/PFT_2019)  

<a name="gnl">get_next_line</a>  
----------
<a name="push_swap">push_swap</a>  
----------
[ресурс для генерации чисел](https://stattrek.com/statistics/random-number-generator.aspx#error)  
[Wiki](https://github.com/VBrazhnik/Push_swap/wiki/Algorithm) с алгоритмом бражника  
[Бинарная сортировка](https://www.programiz.com/dsa/radix-sort) объяснение и реализация на разных языках  
[Видео](https://www.youtube.com/watch?v=KeDXVukgd9g) от @lajudy

<a name="pipex">pipex</a>  
----------
Инструкция от @jkate:  
>Начинаем с открытия файлов и fd-ников: [one](http://www.c-cpp.ru/content/open-rtlopen), [two](http://codewiki.wikidot.com/c:system-calls:open) , [three](http://www.ccfit.nsu.ru/~deviv/courses/unix/unix/ng1e3d8.html), [four](https://coderoad.ru/2245193/Почему-open-создает-мой-файл-с-неправильными-разрешениями);  
Полезный лайфхак: если закрыть 0-й fd-ник, а потом открыть файл, то ему запишется 0-й;  
[Продолжаем, делая pipe](https://www.geeksforgeeks.org/pipe-system-call/);  
[Делаем первый fork https](//man7.org/linux/man-pages/man2/fork.2.html);  
[В форках меняем fd-ники с помощью https](//www.opennet.ru/man.shtml?topic=dup2&category=2&russian=0);  
Используем execve [one](https://man7.org/linux/man-pages/man2/execve.2.html), [two](https://www.opennet.ru/man.shtmltopic=execve&russian=0&category=&submit=%F0%CF%CB%C1%DA%C1%D4%D8+man);  
[Ищем путь](https://www.opennet.ru/man.shtml?topic=access&russian=0&category=&submit=%F0%CF%CB%C1%DA%C1%D4%D8+man);  
[Для ошибок](http://www.c-cpp.ru/books/exit);  
[Если решите использовать waitpid](https://stackoverflow.com/questions/21248840/example-of-waitpid-in-use); 

[Видео про пайпы](https://www.youtube.com/watch?v=vLl7P0PCfE4) от МФТИ  
[Видео-лекции](https://www.youtube.com/watch?v=6xbLgZpOBi8&t=2s) на YouTube  

<a name="minitalk">minitalk</a>  
----------

[Видео](https://youtu.be/E-bk6EkNsnY) от @ftassada  
[Видео на Youtube](https://www.youtube.com/playlist?list=PLfqABt5AS4FkW5mOn2Tn9ZZLLDwA3kZUY) про fork()  
[Видео про сигналы](https://www.youtube.com/watch?v=xrdUAfAHf-s) от МФТИ  
[Статья](https://www.opennet.ru/docs/RUS/glibc/glibc-21.html#ss21.1) про сигналы

<a name="so_long">so_long</a>  
----------
[Документация](https://harm-smits.github.io/42docs/libs/minilibx.html) по minilibx   
[Конвертер в XPM](https://www.online-utility.org/image/convert/to/XPM) без ограничений  
[Беслпатные png-картинки](https://www.freepng.ru/) (работает только с VPN)  
[Канал по minilibx](https://42born2code.slack.com/archives/C9VCML4KB/p1624302999003100) в глобальном слаке   
[Дополнительная информация](https://aurelienbrabant.fr/blog/getting-started-with-the-minilibx) по minilibx

<a name="fdf">FDF</a>  
----------

<a name="fract_ol">fract-ol</a>  
----------
[Документация](https://harm-smits.github.io/42docs/libs/minilibx.html) по minilibx   
[Алгоритмы построения графиков для множества Мандельброта](https://en.m.wikipedia.org/wiki/Plotting_algorithms_for_the_Mandelbrot_set) статья на википедии  

<a name="philo">Philosophers</a>  
----------
[Визуализатор](https://nafuka11.github.io/philosophers-visualizer/)  
[Статья](https://learnc.info/c/pthreads_deadlock.html) про дедлок  
[Книга Столярова](http://www.stolyarov.info/books/pdf/osintro.pdf) про обедающих философов с на стр. 162 (Лекция 13)  
[Тестер 1](https://github.com/cacharle/philosophers_test)  
[Тестер 2](https://github.com/nesvoboda/socrates)  
[Актуальные ссылки в readme](https://github.com/4-o-4/42_philosophers)  

<a name="minishell">minishell</a>  
----------
вместе с флагом -lreadline нужно прописать вот эти флаги:  
```
-L/Users/ваш ник/.brew/Cellar/readline/8.1/lib/  
-I/Users/ваш ник/.brew/Cellar/readline/8.1/include  
```
[Тестер 1](https://pypi.org/project/minishell-test/#description) (старый, может неправильно работать)  
[Тестер 2](https://github.com/alchrist42/msh_tester) (новый, должен работать)  
[Видео-лекция](https://www.youtube.com/watch?v=Um3pzuee-4Y) от weambros  
[Полезная табличка]() для обработки сигналов   
Терминология shell по стандарту (чтобы было взаимопонимание в команде):  
 [AND-OR list](https://pubs.opengroup.org/onlinepubs/9699919799/utilities/V3_chap02.html#tag_18_09_03) :: [pipeline](https://pubs.opengroup.org/onlinepubs/9699919799/utilities/V3_chap02.html#tag_18_09_02) :: [(simple) command](https://pubs.opengroup.org/onlinepubs/9699919799/utilities/V3_chap02.html#tag_18_09_01)  
[Кейсы](https://docs.google.com/spreadsheets/d/1RPxSWKzRELfAirkaLeqqzoEArkaq9Vy7tTEHEnamlgA/edit#gid=0) для проверки  
[Настройка цветов](https://github.com/tlucanti/minishell/blob/master/inc/color.h) для ридлайна  
[Гайд](http://ccfit.nsu.ru/~deviv/courses/unix/unix/menu.html) по системным вызовам  
[Список разрешённых функций](https://github.com/bakyt92/09_minishell/blob/master/Functions_approved.md) с описаниями  
[Maindmap](https://miro.com/app/board/uXjVOnCCft4=/) от @ufitzhug  
> Как зайти отладчиком в дочерний процесс:  
Для LLDB не знаю, есть возможность или нет.  
Для GDB на его панели в отладчике ПЕРЕД ВЫПОЛНЕНИЕМ fork() надо ввести ```set follow-fork-mode child``` и ```set detach-on-fork off```. То есть можно прямо на fork() точку останова установить, и во время отладки до прохода этой точки ввести команды и продолжать отладку как обычно.  
Это на связке WSL-CLion через Windows 10 работает, ну и на Linux должно (edited).  

<a name="cub3d">cub3d</a>
----------
@cdrennan:
>
```
target_link_libraries(cub3d
        /Users/cdrennan/Desktop/cub3d/libmlx.dylib
        "-framework OpenGL"
        "-framework AppKit"
        /Users/cdrennan/Desktop/cub3d/libft.a)
```
>Не знаю что значит куча этих строк, у меня вот такая простая  конструкция работала

@nGragas:
> Хеллоу!!  
Хочу поделиться результатом того, что затянуло меня на 50 дней кодинга в школе (спасибо продлённым дедлайнам) - [проект cub3D](https://youtu.be/ujFoM7Q15zM) 
Текстурированные пол-потолок, полный обзор мышкой и прыжки-приседания, фрицы с овчарками с поиском пути, позиционированный звук, двери и секретные двери и прочие мелочи, чтобы повторить оригинал Wolfenstein 3D (>3000 отнорминетченных строк кода).  
К этой игре задизайнили свои доп уровни   
@mharriso - horror.cub и   
@Сkendall - neon.cub.  
Возможно это вдохновит кого-то на написание крутого cub3D, как когда-то меня вдохновило [видео](https://www.youtube.com/watch?v=a0tBn15kaXw) от @amalliar   
Скачать поиграть на школьных маках можно [отсюда](https://github.com/Rush-iam/nGragasstein3D-cub3D/releases)

>В Интре есть [видео](https://elearning.intra.42.fr/notions/wolf3d-doom-nukem/subnotions/wolf3d-demonstration/videos/demonstration) с интересной реализацией cub3D - лестницы, многоэтажность, полигональные выступы

<a name="minirt_cub3d">miniRT&cub3d</a>
----------
@DXhoan
>А никого не смущает, что функции для реверса цвета в 42docs с ошибкой написаны?
Должно быть вот так:
```
	r = (figure_color & (0xFF << 16)) >> 16;
	g = (figure_color & (0xFF << 8)) >> 8;
	b = figure_color & 0xFF;
```
>Добавление: или так можно, если не используете прозрачность:
```
	r = figure_color >> 16;
	g = (figure_color & (0xFF << 8)) >> 8;
	b = figure_color & 0xFF;
```
 
@enena
>Кто выбирает динамическую на свифте ради get_screen_size - я написал ее на статику через фреймворк AppKit:  
прототип в mlx.h - реализацию в mlx_get_screen_size.m - не забудьте добавить файл к сборке в Мэйкфайле  
```cpp
#import <AppKit/NSScreen.h>
void    mlx_get_screen_size(int *width, int *height)
{
    NSRect disp = [[NSScreen mainScreen] frame];
    *height = (int)disp.size.height;
    *width = (int)disp.size.width;
}
```
[Документация](https://harm-smits.github.io/42docs/libs/minilibx.html) по minilibx
[Описание](https://qst0.github.io/ft_libgfx/man_mlx.html) функций mlx  
[Статья](https://medium.com/sysf/bits-to-bitmaps-a-simple-walkthrough-of-bmp-image-format-765dc6857393) про BMP  
[Видио на интре](https://elearning.intra.42.fr/notions/minilibx/subnotions) про mlx

[miniRT в терминале](https://www.youtube.com/watch?v=QkETiyYWh2o) - видео на YouTube   
Теория по цилиндрам miniRT: [link1](https://mrl.cs.nyu.edu/~dzorin/rend05/lecture2.pdf), [link2](http://hugi.scene.org/online/hugi24/coding%20graphics%20chris%20dragan%20raytracing%20shapes.htm)  
[Видео на YouTube](https://youtu.be/jKjbeWHujV0) про трассировку лучей  
[Видеолекция](https://www.notion.so/miniRT-tutorials-eedfa239615042d582eeed1fae0209bc) на notion про miniRT    

Ссылка на улучшенную браузерную версию есть в сабджекте: [Wolfenstein 3D](http://users.atw.hu/wolf3d/)  
Чтобы ещё лучше понимать то, как игра спроектирована, а также те трудности, которые преодолевали разработчики - несколько лет назад вышла крутая фанатская книга Game Engine Black Book: Wolfenstein 3D - на 300 страниц с множеством скриншотов, из которой можно почерпнуть множество интересных деталей. [Книга](https://vk.com/doc255577237_573973985?hash=JDaz325DdWZQ6HebiQKX2pKPRDAi7b2qeuaGxw4mEEL&dl=vvZ0w9jjsKCVfBLhxri4Ld9j2ZWgF9hw2nJ2SeRaM1T) бесплатна для скачивания.  
[Видеолекция](https://www.notion.so/Cub3D-fd79729951a84906807af2b252f1d0bc) на notion про cub3d  

<a name="netpractice">NetPractice</a>  
----------
[Общее объяснение](https://github.com/ifanzilka/NetPractice) задач проекта  
[Курс](https://www.asozykin.ru/courses/networks_online) по компьютерным сетям  
[Гайд](https://github.com/Sglossu/net_practice) от @sglossu  
[Туториал](https://github.com/luta-wolf/NetPractice) от @einterdi  

<a name="cpp">CPP_Piscine</a>
----------
[]()
[]()
[]()
[]()
[]()
[]()

<a name="inception">Inception</a>  
----------
[Гайд](https://github.com/rbiodies/inception) от @rbiodies  
[Гайд](https://github.com/codesshaman/inception) от @jleslee  
[Гайд](https://github.com/luta-wolf/inception) от @einterdi  

<a name="containers">ft_containers</a>  
----------
[Видеолекция по бинарным деревьям](https://mipt.lectoriy.ru/lecture/CompTech-Informat-L10-Derbysh-141128.01) от МФТИ  
[Тестер](https://github.com/divinepet/ft_containers-unit-test) от @elaronda и @cshells  
[Гайд](https://github.com/StrongUzumaki/FT_Containers/wiki) от @suzumaki  
[Визуализатор](https://www.cs.usfca.edu/~galles/visualization/RedBlack.html) красно-черных деревьев  

<a name="irc">ft_irc</a>
----------
[Материалы и реализация](https://github.com/levensta/IRC-Server) от @levensta  
[Видеолекция](https://www.youtube.com/watch?v=I9o-oTdsMgI) от @gmorra

<a name="webserv">webserv</a>
----------

Про селект и сокеты [статья](http://www.wangafu.net/~nickm/libevent-book/01_intro.html) и [видео](https://www.youtube.com/watch?v=9J1nJOivdyw).  
[Пояснения заголовков](https://developer.mozilla.org/ru/docs/Web/HTTP/Headers/Accept-Ranges)  
[Гайд](https://www.coderdocs.ru/d/webserver-21-CbLKRlBcZCIbf)  
Webserv на C [статья](https://medium.com/from-the-scratch/http-server-what-do-you-need-to-know-to-build-a-simple-http-server-from-scratch-d1ef8945e4fa)  
Реализация этой статьи на C++:  
[Видео 1](https://www.youtube.com/watch?v=YwHErWJIh6Y)  
[Видео 2](https://www.youtube.com/watch?v=pTIZ9YjE3Pw)  
[Видео 3](https://www.youtube.com/watch?v=bEsRapsPAWI)  
[Видео 4](https://www.youtube.com/watch?v=N49UyTlUXp4)  
Другой подход к ООП архитектуре:  
[Видео 1](https://www.youtube.com/watch?v=Kc1kwm1WyVM)  
[Видео 1](https://www.youtube.com/watch?v=YqEqjODUkWY)  
[Видео 1](https://www.youtube.com/watch?v=wKxbjB6zqS8&list=PLZo2FfoMkJeEogzRXEJeTb3xpA2RAzwCZ&index=32)  
Лекция написанию Weberv на С:  
[Видео](https://www.youtube.com/watch?v=HezLPzr75gE)  
HTTP:  
[Статья](https://flagstudio.ru/blog/http-metody-status-cody-zagolovky)  
[Видео](https://www.youtube.com/watch?v=PpdQQjPS0MA&list=WL&index=18)  
Nginx:  
[Видео 1](https://www.youtube.com/watch?v=fo5KYjqPfWs)  
[Видео 2](https://www.youtube.com/watch?v=EuSTB84VB9E)  
[Статья 1](https://runebook.dev/ru/docs/nginx/http/request_processing)  
[Статья 2](https://www.digitalocean.com/community/tutorials/understanding-nginx-server-and-location-block-selection-algorithms-ru)  
Sockaddr:  
[Статья](https://russianblogs.com/article/8587603498/)  
CGI:  
[Видео 1](https://www.youtube.com/watch?v=mMLJvZgkNQ8)  
[Видео 2](https://www.youtube.com/watch?v=sE8TATrW8k0)  
boundary:  
[Видео](https://www.youtube.com/watch?v=_j5spdsJdV8&t=562s)  

# Экзамены

# Проекты за кругом

<a name="linear_regression">ft_linear_regression</a>
----------
[Теоретичиеские материалы](https://github.com/shuygena/linear_regression/wiki)

# Сабджекты
[Сборник сабджектов](https://github.com/evgenkarlson/ALL_SCHOOL_42) с навигацией на русском.  
Ещё один [сборник сабджектов](https://github.com/fpetras/42-subjects), но уже не первой свежести.  
[Сабджекты](https://github.com/Binary-Hackers/42_Subjects) шестилетней давности (а вдруг...).

# Чек-листы 
[Чек-листы](https://github.com/mharriso/school21-checklists) собирали всей школой :)

# Книги

Книги, которые очень помогут в преодолении коммон-кора (это база!):
[Изучаем программирование на C](https://vk.com/doc30298395_298187334?hash=kdPaoukP0pZywBgLXlPPrGAro3b8RYoS06iizVRkTmc&dl=fYQepAuttPz4jWbZ9c2Yy9eFYVXNKfOEsN3YpgcS2wD) - Д. Гриффитс, Д. Гриффитс  
[Введение в операционные системы](http://www.stolyarov.info/books/pdf/osintro.pdf) - А. Столяров  
[Алгоритмы. Построение и анализ](https://vk.com/doc179585542_437543470?hash=83777f0404cb6d6d7d&dl=5c71c40cb399227ec9) - Т.Кормен, Ч.Лейзерсон, Р.Ривест, К.Штайн 
