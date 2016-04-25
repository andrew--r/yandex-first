# Задание 1

Сверстайте телепрограмму. Страница должна работать в современных браузерах:
MSIE, Firefox, Safari, Google Chrome, Яндекс.Браузер, Opera, а также
адаптирована для мобильных браузеров и разные DPI. По возможности используйте
приёмы безопасной деградации CSS.

Страница должна содержать программы не менее пяти телеканалов на текущую неделю.
У каждого телеканала должен быть узнаваемый заголовок и логотип. Данные должны
быть представлены в табличном формате. Пользователь должен иметь возможность
получить дополнительную информацию о телепрограмме во всплывающем окне
(при наведении курсора на программу).

Помимо внешнего вида (покажите своё чувство прекрасного), нам также интересно,
как вы организуете код и оптимизируете результат.

В качестве дополнительного задания реализуйте что-то на выбор:

- возможность показать то, что сейчас в эфире; 
- фильтрацию по фильмам, сериалам и спортивным передачам.

При выполнении задания можно использовать данные и визуальные решения уже
существующих сайтов.

Результат пришлите в виде двух ссылок: 

- на исходный код на GitHub; 
- на рабочий прототип на gh-pages.

## Что мы проверяем этим заданием

В вашем решении мы хотим увидеть, насколько хорошо вы умеете применять языки
HTML и CSS на практике, а ещё — что вы знаете об особенностях работы разных
браузеров. Также мы понимаем, что некоторые задачи сложно решить только
средствами HTML и CSS и допускаем использование JavaScript, но, пожалуйста,
прокомментируйте в коде или текстовом файле README ход ваших мыслей.

## Мой комментарий

Показ информации о программе во всплывающем окне при наведении на программу —
задача немного сложнее, чем показ информации при клике. При клике можно было бы
просто показывать модальное окно на весь экран, но в данном случае нужно
учитывать размещение всплывающего окна — оно не должно выходить за пределы
экрана. Так как времени на выполнение задания оставалось мало, решил взять
готовую библиотеку для создания всплывающих окон, как раз учитывающую этот кейс.

Стоит добавить, что показ всплывающего окна сейчас реализован не самым лучшим
образом. Во-первых, стоило бы самому реализовать логику отображения окна
и показывать его на мобильных. Во-вторых, отображение окна должно происходить
только после загрузки контента для него с сервера.
