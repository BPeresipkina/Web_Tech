Основные задачи семинара 3

Задание №1 Вычислить результат 158+2 и вывести значение выражения в диалоговое окно.

Задание №2 Передать строковый параметр в диалоговое окно. Например, вывести «Привет, Алевтина!», где имя — это передаваемый параметр.

Задание №3 Вызвать диалоговое окно с заголовком «Как вас зовут?» и подсказкой «Имя» в поле ввода. Затем вывести имя, которое ввели.

Задание №4 Написать функцию, выводящую в диалоговом окне текст и переменную. Например, «Привет, Алевтина». Где «Алевтина» — это внешняя переменная.

Задание №5 вывести на экран ****в диалоговом окне текст с сообщением “Вы уверены?” и кнопками «ОК» , «Отмена».
При нажатии на кнопку “ОК” вывести в диалоговом окне текст с сообщением “Мы рады, что Вы уверены!”.
При нажатии на кнопку “Отмена” вывести в диалоговом окне текст с сообщением “Жаль, что Вы не уверены…”.

Задание №6 перепишите код, используя конструкцию switch-case, запрашивая возраст пользователя через диалоговое окно.
<script>
    let age = 101;

    if (age == 18) {
        alert('Вы совершеннолетний, все можно!');
    } else if (age == 10) {
        alert('Вам надо учить уроки!');
    } else if (age == 30) {
        alert('Ложитесь спать, завтра на работу');
    } else {
        alert('Мы не знаем что Вам делать');
    }
</script>

Дополнительные задачи, выполняются после того, как выполнятся основные задания(если успеете и получится)

Задание №7. Создайте массив с произвольными элементами. Выведите в документе или консоли все данные из массива. При желании можете его предварительно отсортировать, как вам будет удобно(по возрастанию или убыванию)

Задание №8. Создайте массив с элементами 'a', 'b', 'c'. Запишите вместо первого элемента слово, вместо второго - предложение, вместо третьего - новую букву. Массив должен состоять только из строк. Выведите итоговый массив в документ или в консоль.

Задание №9. Создайте массив с произвольными элементами(числами). Увеличьте каждый элемент массива на единицу. Выведите итоговый массив в документ или в консоль.

Для тех, кому мало и скучно и он хочет больше.

Задача 10. Самостоятельно добавьте в текущий проект кнопку, по нажатию которой появляется всплывающее окно с любой из задач семинара 3. Вывод события сделайте через функцию onclick()

Задача 11. Самостоятельно добавьте в текущий проект кнопку-переключатель со светлой темы на темную. Кнопка может быть любая, должен меняться цвет фона со светлого на темный при нажатии и обратно.

Задача 12. Самостоятельно создайте файл с HTML-формой. Разработайте код JavaScript, в котором анализируются введенные пользователем данные, позволяющие изменить размер, положение на странице и цвет горизонтальной линии.

Горизонтальная линия - тег hr. Атрибуты - color, width, size. Вместо линии можно использовать блок div - свойства CSS - width, height, backgroundColor. Для выравнивания используйте свойство margin.

Примеры выполнения уже(как вариант, но следовать ему не обязательно!), которые могут у вас получится:

изображение

изображение

Задача 13. Самостоятельно добавьте в текущий проект слайдер с кнопками-переключателями изображений. Можно самый простой, главное - чтобы благодаря js скрипту, по нажатию на кнопку переключения фото, фото перелистывалось с первого на следующее.

Сдавать задания ссылкой на Github в чат, каждую задачу - в отдельном html файле!