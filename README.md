# Здесь мы храним файлы сверстанных сайтов. 
## Рекомендации по работе над проектом:

### Код
1. **Комментировать код.** 
    * Начинать и заканчивать секцию комментарием. 
        * `<!--Начало секции название секции-->` - для HTML,
        * `//Начало секции название секции` - для CSS и JS
2. **Делать названия классов и id, отражающими суть контента**
    ```
     <div class = "header">
        <div class = "header_menu">
          <a class = "header_menu_a">
        </div>  
     </div>
    ```
3. **Media-запросы пишем в последнюю очередь и после основных стилей.**

### Сторонние компоненты
4. **Допускается подключение отдельных JS библиотек**, например [слайдер](http://kenwheeler.github.io/slick/).
   > Код управления и настройки подключенной JS библиотеки пишется в общем JS-файле или специально созданном JS-файле, отделяясь от остального кода пустой строкой и комментарием начала и конца.
5. **Допускается подключать различные CSS фреймворки для ускорения и упрощения процесса.**

### Изображения
6. **Картинки сразу сохраняем в формате PNG-24 и минимизируем**
   > Для минимизации картинки или группы картинок, можно воспользоваться [этим сервисом](http://imagecompressor.com/ru/).
7. **Использование SVG изображений**

### Git и GitHub
8. **Каждый новый проект сайта должен располагаться в отдельной директории, находящейся в директории "Sites".**
   >|-/verstka   
   >|--/project-1    
   >|--/project-2   
   >|--/project-3
9. **Каждый новый проект должен иметь в своей дериктории определённую структуру папок в которых будут храниться небходимые файлы.** 
   >|--/style..   
   >|--/js..    
   >|--/img..   
   >|--*.html
10. **Коммиты пишутся максимально информативно**
    >Добавил в блок "О нас" описание наших возможностей с илюстрациями..
### Настройка проекта
- Создайте на GitHub репозиторий с названием `свое_название`
- Откройте консоль (терминал) у себя на компьютере
- Наберите и запустите: `git` (по умолчанию при установке git заносится в PATH. Если он не находится, [занесите](https://www.java.com/ru/download/help/path.xml) git в переменную окружения PATH и перезапустите консоль)
- Создайте локальную копию проекта: `git clone url_своего_репозитория`
- Перейдите в каталог проекта: `cd название_каталога`
- Настройте git в локальном проекте на свой проект в GitHub:
  - `git remote -v`
  - `git remote set-url origin url_на_твой_репозиторий.git` - настройка pull
  - `git remote set-url --push origin url_на_твой_репозиторий.git` - настройка push
  - `git push -u origin master`    
