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
- [NetPractice](#netpractice)
- [CPP_Piscine](#cpp)
- [Inception](#inception)
- [ft_containers](#containers)
- [ft_irc](#irc)
- [webserv](#webserv)

**Экзамены**
- [](#)
- [](#)
- [](#)
- [](#)

**Проекты за кругом**

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
[Видео](https://www.youtube.com/watch?v=KeDXVukgd9g) от @lajudy

<a name="pipex">pipex</a>  
----------
Инструкция от @jkate:  
Начинаем с открытия файлов и fd-ников: [one](http://www.c-cpp.ru/content/open-rtlopen), [two](http://codewiki.wikidot.com/c:system-calls:open) , [three](http://www.ccfit.nsu.ru/~deviv/courses/unix/unix/ng1e3d8.html), [four](https://coderoad.ru/2245193/Почему-open-создает-мой-файл-с-неправильными-разрешениями);  
Полезный лайфхак: если закрыть 0-й fd-ник, а потом открыть файл, то ему запишется 0-й;  
[Продолжаем, делая pipe](https://www.geeksforgeeks.org/pipe-system-call/);  
[Делаем первый fork https](//man7.org/linux/man-pages/man2/fork.2.html);  
[В форках меняем fd-ники с помощью https](//www.opennet.ru/man.shtml?topic=dup2&category=2&russian=0);  
Используем execve [one](https://man7.org/linux/man-pages/man2/execve.2.html), [two](https://www.opennet.ru/man.shtmltopic=execve&russian=0&category=&submit=%F0%CF%CB%C1%DA%C1%D4%D8+man);  
[Ищем путь](https://www.opennet.ru/man.shtml?topic=access&russian=0&category=&submit=%F0%CF%CB%C1%DA%C1%D4%D8+man);  
[Для ошибок](http://www.c-cpp.ru/books/exit);  
[Если решите использовать waitpid](https://stackoverflow.com/questions/21248840/example-of-waitpid-in-use); 

[Видео](https://www.youtube.com/watch?v=6xbLgZpOBi8&t=2s) на YouTube

<a name="minitalk">minitalk</a>  
----------

[Видео](https://youtu.be/E-bk6EkNsnY) от @ftassada  
[Видео на Youtube](https://www.youtube.com/playlist?list=PLfqABt5AS4FkW5mOn2Tn9ZZLLDwA3kZUY) про fork()  
[Статья](https://www.opennet.ru/docs/RUS/glibc/glibc-21.html#ss21.1) про сигналы


<a name="so_long">so_long</a>  
----------
