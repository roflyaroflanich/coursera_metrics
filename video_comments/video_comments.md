Комменты к видео:

на кафедре публичной политики я уже не работаю, поэтому это упоминание в синей полосе имеет смысл убрать


1.1.
1.1.1. Суть метода наименьших квадратов
http://youtu.be/oLWRDmVSUwc
1:03 в таблице добавить заголовок и единицы измерения

"Данные по России"
Год | Население (тыс. чел.) | Безработица (%)

1:50 в таблице добавить заголовок 

"Олимпийские игры 2014"

3:15 добавить скобки или запятые:

* одна зависимая (объясняемая) переменная
* несколько регрессоров (объясняющих переменных)

5:22 исправить 

неизвестные параметры: \beta_1 и \beta_2
8:09 обещание разобрать в R пример с cars ok, выполнено


1.1.2. Регрессия на константу
http://youtu.be/lQr6t4yqH0g
3:41 оговорка, сказал "максимум" вместо "минимум"
около 5:00 тусклый маркер, но читабельно
задолбал логотип, может вышке не стоит так комплексовать?

1.1.3 Вывод оценок в парной регрессии - 1 
http://youtu.be/Dg9wCHXgHvM
1:45 RSS --- еще не было в лекциях ?
4:30 и далее ---  тусклый маркер

1.1.4. Вывод оценок в парной регрессии - 2
http://youtu.be/LDvyUxUxGF0
3:50 --- тусклый маркер
5:28 оговорка, нужно "числитель" вместо знаменатель
5:40 ужасно тусклый маркер

1.1.5 Метод наименьших квадратов (картинка для парной, условия для 3-х коэффициентов)
http://youtu.be/no5J_iVVC8s
1:06 добавить внизу синюю формулу: $\hat{\beta}_1=\bar{y}-\hat{\beta}_2 \bar{x}$
10:40 тусклый маркер

1.1.6. Ликбез по линейной алгебре
http://youtu.be/y_k3eVcRdKY
около 0:50 добавить английскую расшифровку сокращений:
Сумма квадратов остатков, Residual Sum of Squares
Общая сумма квадратов, Total Sum of Squares
Объяснённая сумма квадратов, Explained Sum of Squares

3:24 вторую формулу не показывать пока что!
3:33 под первой формулой толкьо теперь должна появиться вторая с подписью:

Квадрат длины вектора
|y|^2=y_1^2+y_2^2+\ldots+y_n^2=\sum_i  y_i^2

RSS и TSS появляться не должны пока что!

для себя: можно вопрос про ESS (квадрат длины какого вектора есть ESS?)


1.1.7. Геометрическая иллюстрация МНК без регрессеров 
http://youtu.be/05w89-4ir1k

1.1.8. Геометрическая иллюстрация МНК для множества регрессеров 
http://youtu.be/_Kzpzuzea88
0:28 Добавить сверху:

Модель:
$y_i=\beta_1+\beta_2 x_i+\beta_3 z_i + \varepsilon_i$

1.1.9 Коэффициент детерминации и доказательство (можно пропустить)
http://youtu.be/LDrl_HTc5p8

1:32 Немного переставить и добавить:

В моделях со свободным членом:
$TSS=ESS+RSS$

$TSS=\sum (y_i-\bar{y})^2$ --- общий разброс y
$ESS=\sum (\hat{y}_i-\bar{y})^2$ --- объяснённый разброс y
$RSS=\sum \hat{\varepsilon}_i^2$ --- сумма квадратов ошибок

Коэффициент детерминации $R^2 \in [0;1]$
$R^2=ESS/TSS$
* доля объяснённого разброса в общем

2:41 добавить промежуточный кусочек в формулу:
$R^2=(sCorr(y,\hat{y}))^2= (далее та дробь, что уже есть)^2$

3:10 начало доказательства

7:00 тусклый маркер

1.1.10. Мораль и формула по линейной алгебре
http://youtu.be/eCTjqY0_NQ8

 
 
 
1.2.1. здесь по ошибке идет фрагмент 1.2.3 
а должен идти фрагмент с работой в консольном режиме!!
то есть название правильное, а видео --- не то.
https://www.youtube.com/watch?v=ZMuu77mJX6E


1.2.2. Написание первого скрипта в R
(видны команды с пропущенного первого фрагмента)
https://www.youtube.com/watch?v=eC3d5DpuUjQ

1.2.3. Установка пакетов в R, Получение справки 
https://www.youtube.com/watch?v=leZ6UcLuvac

1.2.4. Первый взгляд на данные, описательные статистики, графики
https://www.youtube.com/watch?v=mJhXwb1dh1o
7:17 и далее вместо d надо было взять на графике d2. переснять?

1.2.5. Метод наименьших квадратов. Пример с машинами
тут тоже d вместо d2 (! переснять, коэффициенты не как в лекции!)
(здесь r2 руками)
https://www.youtube.com/watch?v=ll-KE1q5b4U

1.2.6. Метод наименьших квадратов. Пример с фертильностью
(сверху следы следы с d)
(начать заново с пакетов, установить splom)
(здесь R2 через summary)
(8:22 и далее --- отрезать)
https://www.youtube.com/watch?v=_Ii9zpUt-2I



1.1.1 - всё ОК, только на мой вкус быстровато.

Дальше: мысль вслух - не слишком ли много формул? Испугаются ведь. Может, про эти видюшки 1.1.2 - 1.1.4 написать, что они
для желающих? Чтобы поначалу всё было попроще и повеселее, больше картинок и слов?

А установку R и R Studio показывать не будем, только текстом опишем?


2.1.9 - 2:35 написано se(\beta_j) = \sqrt{\beta_j|X}. Надо \sqrt{var(\beta_j|X)}


2 1 1 Условное математическое ожидание. Определение
http://youtu.be/ldbqnBKwtto
ок

2 1 2 Условное математическое ожидание. Пример подсчёта
http://youtu.be/KUglGmmeXHE
0:18 исправить опечатку в синей строке внизу, написано "Пример подсТчёта"
4:14 тусклый маркер, местами ужасно тусклый

2 1 3 Условная дисперсия. Пример подсчёта
http://youtu.be/gpAemI7ODVI
0:26 ошибка в формуле. В интеграле вместо dx должно быть ds

1:19 вместо "список свойств" лучше написать "Свойства условного математического ожидания"
добавить небольшим шрифтом сверху
a, b --- константы
s, r --- случайные величины

Сначала появляется только E(as+b|r)=aE(s|r)+b
в 1:31 дополнительно появляется E(E(s|r))=E(s)

2:48-2:52 --- удалить оговорку
текст должен быть:
"Аналогично определяется и условная ковариация"
он звучит дальше, просто вырезать 4 секунды с оговоркой

3:12 уточнить название сверху "Свойства условной дисперсии"
добавить небольшим шрифтом сверху:
a, b --- константы
s, r --- случайные величины

4:02---до конца (весь пример расчета) - вырезать и вставить в момент времени 2:56

6:30, 7:07 --- очень тусклый маркер

2 1 4 Геометрическая иллюстрация условного математического ожидания
http://youtu.be/HsxokLgBWUw
отрезать и полностью убрать начало вплоть до 1:23

2:25 тусклый маркер
3:50 тусклый маркер
7:18 тусклый маркер
8:10 он же такой же

2.1.5. Условная дисперсия МНК оценок. 
http://youtu.be/sUnzxnE9pqs
0:33 немного поменять подписи:
- Дисперсия, Var(r) --- квадрат длины случайной величины r
- Корреляция, Corr(r,s) --- косинус угла между величинами r и s
2:01 ковариационная матрица вектора $\varepsilon$ --- сделать букву эпсилон синей как во всех формулах

3:42-3:52: разместить формулы 2 и 3 чуть правее формулы 1 (возможно не с кружочками, а с черточками перед ними)
по сути формулы 2 и 3 поясняют формулу 1 и формула 1 полностью их заменяет
3:52: добавить (с таким же отступом как формулу 1) формулу $E(\varepsilon_i |X)=0$
4:20 внизу вставить "|X" в формулы, то есть должно быть:
$Var(\hat{\beta}_j|X), Cov(\hat{\beta}_j,\hat{\beta}_l|X)$

4:27 Формулы и предпосылки исчезают, появляется:
"Для парной регрессии:
Var(\hat{\beta}_1)=\sigma^2\frac{\sum x_i^2}{n\sum (x_i-\bar{x})^2}
Var(\hat{\beta}_2)=\frac{\sigma^2}{\sum (x_i-\bar{x})^2}
Cov(\hat{\beta}_1, \hat{\beta}_2)=\sigma^2\frac{-\bar{x}}{\sum (x_i-\bar{x})^2}"

4:37 --- до конца ---- отрезать в отдельное видео. Этот фрагмент назвать "Условная дисперсия МНК оценок. Начало доказательства"


6:30 и далее тусклый маркер


2 1 6 Условная дисперсия МНК оценок. Завершение доказательства.
http://youtu.be/nQa3JuLHIu8
0:20 --- 0:50 предполагалось ускорение видео, я специально там молчал. Или от этой идеи отказались почему-то?

2 1 7 Дисперсии оценок в общем виде
http://youtu.be/Sbtm_aMCgS0
1:42 заменить ответ на
--- При случайных регрессорах безусловная дисперсия считается слишком сложно...
3:09 убрать те надписи, что есть и заменить их на:

Теорема:

(формула остается без изменений)

3:41 дополнительно появляется:
Свойства дисперсии:
$Var(a\cdot x_i)=a^2 Var(x_i)$
3:55 появляется только формула, а слово "свойство" перед ней убираем
4:10 вместо "напомним что" появляется "Свойства транспонирования:"




2 1 8 Доказательство формулы для ковариационной матрицы
http://youtu.be/1GG46RDfZSs

2 1 9 Оценка ковариационной матрицы (доверит инт для беты)
http://youtu.be/GFx6vJm7MQI
0:26 Как оценить \sigma^2? --- поставить знак вопроса в конце заголовка
1:48 Поставить запятую после "А именно,"
2:22 под корнем пропущено Var с крышкой. То есть должно быть:
$se(\hat{\beta}_j)=\sqrt{\widehat{Var}(\hat{\beta}_j)}$
3:16 заменить "ЛИНАЛ" на "В общем виде:"

3:40---до конца начало доски  --- отрезать и вставить в 5:55 фрагмента 2.1.11
4:52 (безусловная на условная)
6:13 (безусловная на условная)
6:28 (безусловная на условная)


2 1 10 Статистические свойства оценок коэффициентов
http://youtu.be/C9-N957ZORY
0:25 убрать сокращение "БСХС", оставить только "Большой Список Хороших Свойств" 
1:44 убрать "БСХС" оставить "Предпосылки"
2:30 пропущена запятая после слова константа и нижний индекс i у игрека, должно быть:
"С помощью МНК оценивается регрессия y_i на константу, x_i и z_i"
3:04 оценка \hat{\beta} в матричном виде???
3:15. Убрать "БСХС", оставить "Предположения на \varepsilon_i"
3:41 между строчками "E(e_i^2 | все регрессоры)" и "В матричном виде" вставить строку:
"Или: $Var(\varepsilon_i | все регрессоры )=\sigma^2$"
3:53 выше формулы добавить "Условная некоррелированность:"
4:21 убрать "БСХС", оставить заголовок "Предпосылки на регрессоры:"
4:21 "Векторы отдельных наблюдений..." должно появляться в 4:48
4:48 "С вероятностью 1..." должно появляться в 4:21
6:02--6:17   Вырезать этот кусок и вставить в момент 4:46
6:02 Во фразе добавить ":" и слово "существует". Сделать одинаковый отступ с пунктом "С вероятностью 1 среди регрессоров нет линейно зависимых". Чтобы в сумме этот пункт выглядел примерно так:

* С вероятностью 1 среди регрессоров нет линейно зависимых.
  Синонимы в матричном виде: rk(X'X)=k, (X'X)^{-1} существует или det(X'X)\neq 0
6:35, долой "БСХС", оставляем "Базовые свойства (теорема Гаусса-Маркова)"
7:56 заменяем на 
* Оценки несмещены:
условно, E(\hat{\beta}_j |X)=\beta_j
и безусловно, E(\hat{\beta}_j)=\beta_j
10:05 меняем заголовок на "Базовые свойства:"
10:51 к последней формуле добавляем запятую в конце и ниже пишем
"где $\hat{\sigma}^2=RSS/(n-k)"
11:25 оставляем "Асимптотические свойства:" без БСХС
11:35 дописываем в конце "... по вероятности, т.е. $\hat{\beta}_j$ состоятельны"
12:35 заголовок без бсхс, "При нормальности $\varepsilon_i$:"
в формулу добавляем "|X", т.е.
Если дополнительно известно, что $\varepsilon_i | X \sim N(0,\sigma^2)$




2.1.11 Построение доверительных интервалов и проверка гипотез
http://youtu.be/a36WGysGPnA
0:57 появляется формула 
$\frac{\hat{\beta}_j-\beta_j}{se(\hat{\beta}_j)} \to N(0,1)$
1:25 появляется текст:
Проверять гипотезы можно в двух случаях:
* Число наблюдений велико
* Случайные ошибки нормальны
1:48 заменяем фразу "Возможно строить в двух подходах" на "Проверка гипотезы о коэффициенте \beta_j:"
3:03 "Проверяемая гипотеза H_0"
3:16 вместо дописывания "против H_a" делаем новый пункт "Конкурирующая гипотеза H_a"
4:01 Стираем старые строки и делаем новый заголовок "Практические шаги:"
4:05 добавляем под заголовком
1. Формулируем гипотезу H_0 и выбираем уровень значимости $\alpha=\P(отвергнуть H_0|H_0 верна)$
4:33 добавляем еще пункт
2. Рассчитываем наблюдаемое значение тестовой статистики, $S_{obs}$
4:40 добавляем еще пункт
3. Находим критическое значение тестовой статистики, $S_{cr}$
4:47 добавляем еще пункт
4а. Сравниваем $S_{obs}$ и $S_{cr}$, делаем вывод об $H_0$
5:25 добавляем еще пункт:
4б. Сравниваем $P$-значение и $\alpha$, делаем вывод об $H_0$

5:55 сюда вставляется отрезанный кусок от 2.1.9
текущий фрагмент 5:55---11:23 удаляется!!! так как он уже идет во фрагменте 2.1.12!!!

R как таблица? да, есть, в лабах!

2.1.12 Доверительный интервал для $\sigma^2$
http://youtu.be/llSCwxEUjNw
ок

2.1.13 Проверка гипотез о $\beta_j$
http://youtu.be/belwLt1rBiY
6:30 заменяем заголовок "Описание любого теста" на "Распространенная форма записи:"


2.1.14 Интерпретация стандартной таблички 
http://youtu.be/FwqwO3E1NEA
пожелание: растянуть табличку на сколько можно, много не получится, но всё же

2.1.15. Особенности проверки гипотез
http://youtu.be/CfMEeFb8g5k
7:56 немного подредактировать пункты:
* Асимптотически --- N(0,1)
* При нормальности $\varepsilon_i$ --- t_{n-k}

2.1.16 Гипотеза о линейном ограничении [сделать факультативным]
http://youtu.be/WSjoAeujXe4
вырезать собирание с мыслями 7:04 - 7:32
9:58 маленький кусочек не отражен зеркально
 

2 2 1 Работа со случайными величинами в R 
http://youtu.be/92v1Br60Ys4
ок

2 2 2 Проверка гипотез о коэффициентах
http://youtu.be/a27n8-DZVNQ
удалить кусок 3:51--4:03 полностью 
удалить кусок 5:32--5:43 (тишина)

есть ли в третьей лабе способ с linearHypothesis?

2 2 3 Стандартизированные 
http://youtu.be/qvMbDVrSBWI
кусок 3:41 - 8:55 удаляем полностью
 
2 2 4  Сохранение и загрузка данных 
http://youtu.be/8chddRL-EK4
10:48 --- до конца --- удалить

2 2 5 Загрузка данных RLMS
http://youtu.be/DYfk64xhl1U
переснять полностью

"r21i_os24a.sav"
установить пакет "rlms"
select qm1, qm2, qh6 (отбор переменных) добавить пол
glimpse
describe
mutate (возраст функция от года)
qplot( rost, ves)
qplot + geom_hex()
отбор наблюдений
отбираем мужчин старше чего-то строим тот же график
каждый раз новый df (df1, df2, df3, df4...)






===================

Первая измененная глава доска+ лого, как вы просили:

 
1 1 8 Геометрическая иллюстрация МНК для множества регрессеров 
http://youtu.be/40IXgQN1CC8

1 1 9 Коэффициент детерминации
http://youtu.be/Sag4ZnIlguY

1 1 5 Метод наименьших квадратов
http://youtu.be/pacc_MRwzhw

1 1 7 Геометрическая иллюстрация МНК без регрессеров
http://youtu.be/GGWZwRIAc2o

1 1 4 Два примера на метод наимменьших квадратов
http://youtu.be/4o8R0mQ3dhw

1 1 2 Два примера на метод наимменьших квадратов 
http://youtu.be/FWKG0gHNuhE

 

4 глава:

http://youtu.be/9MhZ0UCb_Cc
http://youtu.be/yXQGrWGVpoo
  http://youtu.be/fwqs8mPEZFc
http://youtu.be/6LnUUI0Iotw
http://youtu.be/oRYyXjZJipo
 http://youtu.be/-UcSI47ITfU
http://youtu.be/9P4pCJN9ENw
http://youtu.be/ixdKGZJeSt0
http://youtu.be/dAJu-BUyvks
http://youtu.be/g83D9xxOWzE

 

 

6 глава

 

http://www.youtube.com/watch?v=0f-U3CXq8jM&feature=youtu.be

http://www.youtube.com/watch?v=wgwHoPw30Rs&feature=youtu.be

http://www.youtube.com/watch?v=_JcRGYmoDvM&feature=youtu.be

http://www.youtube.com/watch?v=i0jSdLWH4NE&feature=youtu.be

http://www.youtube.com/watch?v=5XCeTZi3efk&feature=youtu.be

http://www.youtube.com/watch?v=wDQriAxT_4E&feature=youtu.be

http://www.youtube.com/watch?v=kTmEBWWN68Y&feature=youtu.be

http://www.youtube.com/watch?v=hszXyt1nt4w&feature=youtu.be

http://www.youtube.com/watch?v=O8aX-AU4KiA&feature=youtu.be

http://www.youtube.com/watch?v=63HbND96rIQ&feature=youtu.be

 

Исправленное видео 6 главы 

1.4 http://www.youtube.com/watch?v=A0CdRimMEHw&feature=youtu.be

==================================

 

Иван Станкевич -- аспирант кафедры математической экономики и эконометрики НИУ ВШЭ

Анна Тихонова -- студентка первого года магистерской программы «Финансовая экономика» МИЭФ








видео третьей главы:

3.1.1. Прогнозирование во множественной регрессии

\url{http://youtu.be/6x5FmRuTk08}

1:17 сейчас появляется надпись <<Доверительный интервал ...>> с формулой внизу. Они должна появиться только в 2:20

1:30 добавляем надпись <<Точность прогноза определяется шириной доверительного интервала>>

4:10 исправить на:

условное среднее, $E(y_i | X)$

ошибка прогноза условного среднего, $\hat{y}_i - E(y_i | X)$

дисперсия ошибки прогноза:

$Var(\hy_i - E(y_i | X)  | X )= ... $ (далее формула уже есть)

5:04 исправить на:

конкретное наблюдение, $y_i$

ошибка прогноза, $\hy_i - y_i$

дисперсия ошибки прогноза:

$Var(\hy_i - y_i | X) = Var(\hy_i- E(y_i | X) - \e_i |X) = ... $ (далее формула уже есть, сейчас опечатка в начале формулы )

6:25 опечатка --- пропущен пробел в <<предположении о нормальности>>

7:14 опечатка --- пропущен пробел в <<предположении о нормальности>>


3.1.2 Пример построения интервалов для прогнозов
http://youtu.be/swWNng-RBho
ок

3.1.3. Интерпретация коэффициента при логарифмировании
http://youtu.be/NdsfDkPOqVI

7:50 пропущен нижний индекс 2 у коэффициента бета, должно быть:

C ростом x на единицу у растет на $\beta_2$ единиц

7:57 пропущен нижний индекс 2 и окончание "ов"

C ростом x на один процент у растет на $\beta_2$ процентов

8:05 пропущен нижний индекс 2 у коэффициента бета, должно быть:

C ростом x на единицу у растет на $100\beta_2$ процентов

8:18 пропущен нижний индекс 2 и ошибка, должно быть:

C ростом x на один процент у растет на $\beta_2/100$ единиц

done

3.1.4. Исправить название на "Дамми-переменные. Разные зависимости для подвыборок"

http://youtu.be/wJj_oasiKgU

0:28 немного исправить на: ($male_i$ --- синим цветом, тк это формула):

Например, переменная $male_i$, равная 1 для мужчин и 0 --- для женщин

4:02 перепутаны М и Ж, и лишний плюс в формуле, должно быть:

Для мужчин:

$wage_i=(\beta_1+\beta_4) + (\beta_2+\beta_5)exper_i+\beta_3 educ_i +\e_i$

4:16 перепутаны М и Ж, должно быть:

Для женщин:

(формула верно)

5:31 перепутаны М и Ж, должно быть:

Для мужчин:

5:39 перепутаны М и Ж, должно быть:

Для женщин:

6:34 перепутаны М и Ж, должно быть:

(формула)

Для мужчин: 

(формула)

Для женщин:

(формула)

7:45 сделать $season_i$ синим цветом 

8:03 в новом пункте немного переставить слова:

* Вводим три дамми-переменных
(четыре сезона минус один базовый)

8:08-8:24 сделать $vesna_i$, $leto_i$, $osen_i$ синим цветом 

8:30 очистить старые надписи и вывести такую табличку 




3.1.5. Проверка гипотез о линейных ограничениях.
http://youtu.be/NqJH0VGeEhU

3.1.6. Пример проверки гипотезы о линейных ограничениях. Соотношение RSS_R---RSS_UR
http://youtu.be/xludTSWApYM

3.1.7. Гипотеза о незначимости регрессии. Вывод формулы из общего случая.
http://youtu.be/fxnJk6bb7Yo

3.1.8. Пример проверки гипотезы о незначимости регрессии.
http://youtu.be/xbpA6Dji5mY

3.1.9. Предпосылки классической линейной модели. Лишние и пропущенные регрессоры.
http://youtu.be/8O_36Dfeba8

3.1.10. RESET тест Рамсея
http://youtu.be/51qvueLMChw

3.1.11. Простые показатели качества (R^2_adj, AIC, BIC)
http://youtu.be/ZGlOncL0H4w


3.2.1. Диаграмма рассеяния для большого количества переменных, мозаичный график
http://youtu.be/eZssYMz7Fgs

3.2.2. Графики для сочетания количественной и качественной переменных (гистограммы разным цветом, фасетки)
http://youtu.be/Ng-W5BqlpzE

3.2.3. Оценивание моделей с дамми-переменными. Интерпретация.
http://youtu.be/Syab2Kc9Cs0

3.2.4. Построение прогнозов. Доверительный и предиктивный интервал.
http://youtu.be/c0wFwacaAV8

3.2.5. Проверка гипотезы о линейных ограничениях. Графическое представление результатов.
http://youtu.be/Du0GNgkmyR8

3.2.6. Ловушка дамми-переменных. Информационные критерии. Тест Рамсея.
http://youtu.be/FW3v22BDY98

3.2.7 Написание отчёта (Word+Latex)
http://youtu.be/ySVk5QgHGfQ




1 глава (повторный отсмотр)
1-1-1 Суть метода наименьших квадратов
http://youtu.be/UGD_u4tpZQU

0:52 сейчас в этот момент появляется надпись "* временные ряды" --- убираем
1:05 сейчас в этот момент появляется таблица --- убираем
1:06 появляется список:
* временные ряды
* перекрестные данные
* панельные данные
1:17 появляется "Временные ряды" и ниже табличка (которая была в 1:05)
над табличкой заголовок: "Данные по России"
3:24 во фразе "по каждой переменной n наблюдений y_1, y_2, ..., y_n" сделать перенос
строки после слова "переменной", т.е.
"по каждой переменной
n наблюдений: y_1, y_2, ..., y_n"
и "n" сделать синим цветом
7:25 сделать букву "Q" синим цветом

1-1-2 изменить название на "Пример 1. Регрессия на константу."
http://youtu.be/qS66GY0bDR0


1-1-3 изменить название на "Пример 2. Парная регрессия. Начало."
http://youtu.be/TNodFvAHxDA


1-1-4 изменить название на "Пример 2. Парная регрессия. Окончание."
http://youtu.be/0NHwfP6cvTU


1-1-5 изменить название на "МНК на графике. Случай множества регрессоров."
http://youtu.be/SB1TMb8Si9U
10:52 вставить синим цветом $\hb_1$, $\hb_2$, $\hb_3$ во фразу над системой уравнений
"Оценки $\hb_1$, $\hb_2$, $\hb_3$ находятся из системы"

1-1-6 Ликбез по линейной алгебре
http://youtu.be/TieRRpVBFy4
0:31---1:07 сделать выезжающие надписи пунктами, то есть
0:31 добавить кружочек (буллет) перед "Сумма квадратов остатков"
0:44 добавить кружочек (буллет) перед "Общая сумма квадратов"
1:07 добавить кружочек (буллет) перед "Объясненная сумма квадратов"
чтобы выглядело:
* Сумма квадратов остатков
...
* Общая сумма квадратов
...
* Объясненная сумма квадратов

5:06 сделать "т.к." черным цветом. Общий принцип: синий --- для формул, черный для текста
5:24 сделать "т.к." черным цветом. Общий принцип: синий --- для формул, черный для текста


1-1-7 изменить название на "Геометрическая иллюстрация регрессии на константу" 
http://youtu.be/TxaiEPyaCdU

1-1-8 исправить название на "Геометрическая иллюстрация МНК для множества регрессОров" (опечатка в последнем слове) 
http://youtu.be/9Iw9spYTCNM
0:27 исправить формулу под словом "Модель" на $y_i=\beta_1+\beta_2 x_i +\beta_3 z_i + \varepsilon_i$

1-1-9 Коэффициент детерминации
http://youtu.be/gjczkpnxd3E
1:32 вместо "доля объясненного разброса в общем разбросе" должно быть "сумма квадратов остатков"
1:43 дополнительно (ниже уже написанного) появляется формула $R^2=ESS/TSS$

1-1-10 Мораль первой лекции
http://youtu.be/7Qniqa3e_2g

1-2-1 Консольный режим в R
http://youtu.be/DKgFFjJjpjI


1-2-2 Написание первого скрипта в R
http://youtu.be/6eIIEgemYh8

1-2-3 Установка пакетов в R Получение справки
http://youtu.be/T2Drwb0FZis

1-2-4 Первый взгляд на набор данных
http://youtu.be/WozZC2XR1ro

1-2-5 Метод наименьших квадратов. Пример с машинами
http://youtu.be/Hq_sbkNdxFk

1-2-6 Метод наименьших квадратов. Пример с фертильностью
http://youtu.be/6vmJAjWrgl4


