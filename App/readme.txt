1. Реализован основной функционал переключения между окнами в программе.
2. Добавлен логотип программы, и картинки в меню "Dictionary".
3. Созданы классы отвечающие за отображения окон меню "Dictionary"-> "Найти слово или фразу" и "Dictionary"-> "Добавить в словарь".
4. Реализована функция всплывающего окна, в котором выполняются действия, в это время основное окно не доступно, пока popup не будет закрыто.
5. Реализована функция поиска в словаре с введенным текстом на русском или на эстонском, программа сама определяет язык.
6. Реализована функция озвучивания (имя файла собирается из est-rus названия, и хешируется в md5, сохраняется в папку). Если имя муз. файла уже существует, будет включено озвучивание существующего файла, иначе будет создан новый файл и запущено озвучивание.
7. При выходе специальной кнопкой, папка с озвучиванием очищается, при запуске программы удаляет последний оставшийся файл с папки sounds. 
8. Реализована функция исправления текста.
9. Реализована функция добавления в словарь, в случае если поиск в переводчике не дал результатов, в таком случае будет подгружена фраза или слово, которое пользователь не смог найти, пользовательно нужно будет только ввести перевод, и нажать - "добавить".
10. Реализована функция в режиме тренировок "Викторина". С вопросами на русском языке, на эстонском языке, в конце викторины вывод на экран результатов
11. Игра пазлы. Генерируются вопросы, показывются кнопки состоящие из букв слова, при нажатии проверяется правльность следующей буквы и сопровождается звуком, если выбор правильный - дописывается строка, при выходе в главное меню очищаются списки кнопок и тексты. Категории пазлов: цвета, месяцы, дни недели, семья