
**Бра́узер** — программное обеспечение для просмотра страниц.  
**Веб-страница** — документ или информационный ресурс Всемирной паутины, доступ к которому осуществляется с помощью веб-браузера.  
**HTML document**
  http://www.etsav.upc.edu/assignatures/portafoli/tutorial1/3.html#:~:text=It's%20a%20text%20document%20saved,tutorials%20when%20applied%20and%20needed.

**1 What is HTML?**
An **element** is a part of a webpage.  
In XML and HTML, an element may contain a data item or a chunk of text or an image, or perhaps nothing.  
A typical element includes an opening tag with some attributes, enclosed text content, and a closing tag.  
Elements and tags are not the same things.  
Теги начинают или заканчивают элемент в исходном коде, тогда как элементы являются частью DOM, модели документа для отображения страницы в браузере.  
In HTML, a **tag** is used for creating an element.  
The name of an HTML element is the name used in angle brackets such as <p> for paragraph.  
Тег HTML — это часть языка разметки, используемая для обозначения начала и конца элемента HTML в документе HTML.  
As part of an HTML element, HTML tags help web browsers convert HTML documents into web pages.  
For example, the <p> tag is used to organize text content into paragraph elements and the <img> tag is used to embed image elements.
  
Empty elements https://developer.mozilla.org/en-US/docs/Glossary/Empty_element   


Разработан был британским физиком-ядерщиков Тимом Бернерсом-Ли в 1991 году в Швейцарском  ЦЕРНе.  
Создавался как язык обмена научной и технической документацией между людьми, которые не обязаны быть большими  
специалистами в области верстки.

![Screenshot_26](https://user-images.githubusercontent.com/66359081/168785624-3b9a2536-9228-46c2-8dd7-cf53a6ee43ec.png)  
![Screenshot_1](https://user-images.githubusercontent.com/66359081/168785754-8c81cb0e-50df-4ac3-9c00-2cf887ad1017.png)

 ### DOM    
https://developer.mozilla.org/en-US/docs/Glossary/DOM
  
**DOM** (объектная модель документа) — это API, который представляет и взаимодействует с любым документом HTML или XML.  
**DOM** — это модель документа, загруженная в браузер и представляющая документ в виде дерева узлов,  
  где каждый узел представляет часть документа (например, элемент, текстовую строку или комментарий).
  
### API  https://developer.mozilla.org/en-US/docs/Glossary/API  
  

**2 Структурные теги**  

**Доктайп**  

Любой код разметки начинается с объявления типа документа, этот элемент говорит браузеру,  
на каком языке разметки и его версии написан документ.  
```
<!doctype html>
```

Для описания структуры HTML - файла используются следующие 4 парных тега:  



**2 Meta**  

Метаданные HTML — это данные о HTML-документе. Метаданные не отображаются.  
Метатеги используются для хранения информации предназначенной для браузеров и поисковых систем.  
Два метатега предназначены специально для поисковых серверов: description (описание) и keywords (ключевые слова).   
**description**
Большинство поисковых серверов отображают содержимое поля description  при  
  выводе результатов поиска. Если этого тега нет на странице, то поисковый движок просто перечислит  
  первые встречающиеся слова на странице, которые, как правило, оказываются не очень-то и в тему. 
  
**keywords**
Этот метатег был предназначен для описания ключевых слов, встречающихся на странице .  
Но в результате действия людей, желающих попасть в верхние строчки поисковых систем любыми средствами, теперь дискредитирован.  
Поэтому многие поисковики пропускают этот параметр.
  
Authore and Setting the viewport to make your website look good on all devices   
  
https://developers.google.com/search/docs/advanced/crawling/special-tags
  
## Семантика  

В программировании, Семантика означает значение фрагмента кода - например,  
«к какому результату приведёт выполнение этой строки JavaScript?», или «каково предназначение или какая роль  
у этого элемента HTML» (а не «как он выглядит ?».)


**3 Атрибут**  

**Атрибут — не обязательное свойство тега.**

Нужен для описания более детальных характеристик html-элемента. Помещается внутри тега, и состоит из конструкции: ключ="значение".  
**src** — Указывает адрес файла, который будет загружаться на сайте.  
**href**— Указывает адрес документа, на который следует перейти.  
**class** — определяет одно или несколько имен для HTML элемента.  Позволяет связать определенный тег с его стилями или javascript логикой.

Путь может быть абсолютным или относительным.  
Абсолютный - представляет из себя полный URL адрес файла или страницы.  
Относительный - выглядит как путь к файлу, относительно сайта.

div  
Универсальный блочный элемент, используется для группировки и разделения контента. 

CSS стили отвечают за визуальное представление документа пользователю. Представляют собой набор css селекторов,  
и перечня css стилей для этого селектора, состоящих из конструкции ключ: значение; разделенных точкой с запятой.  
CSS селектор - это описание элемента, к которому будут применяться свойства. Может выбираться по:   
Тегу (селектору): div{...}  
Классу (атрибут класс) .element{...}  
Идентификатору, атрибуту и/или его содержимому (в более редких случаях).  

Свойство **box-sizing** позволяет изменить логику расчета ширины. Принимает три значения:  

**border-box** - ширина/высота суммирует элемент, его padding и border.  
**padding-box** - ширина складывается из элемента и его padding.  
**content-box** - к ширине контента ничего не добавляется. Используется по-умолчанию.


**HTML-атрибуты** это специальные слова, которые управляют поведением HTML-элемента. Они добавляют  
дополнительную функциональность, либо меняют поведение элемента по умолчанию. Атрибуты элемента выражаются внутри начального тега элемента.
  
**Атрибут** — не обязательное свойство тега.
Нужен для описания более детальных характеристик html-элемента. Помещается внутри тега, и состоит из конструкции: ключ="значение".
  
**src** — Указывает адрес файла, который будет загружаться на сайте.  
**href**— Указывает адрес документа, на который следует перейти.  
**class** — определяет одно или несколько имен для HTML элемента.  Позволяет связать определенный тег с его стилями или javascript логикой.
  
## HTML absolute and relative path
  
**The relative path** means that the path to the file or page of the site is specified relative to  
the directory in which the current page is located, or relative to the root directory of the site. 
  
**An absolute path** is usually used to specify the path to a file that is located on another network resource.  
It is a complete URL to a file or page. In the absolute path, the protocol is first specified, followed by  
the domain name (site name). For example: http://www.example.com - this is how the absolute path to a particular  
website looks. http:// is a data transfer protocol, and www.example.com is the name of the site (domain)
  
  
**CSS стили** отвечают за визуальное представление документа пользователю. Представляют собой набор css селекторов,  
и перечня css стилей для этого селектора, состоящих из конструкции ключ: значение; разделенных точкой с запятой.  
CSS селектор - это описание элемента, к которому будут применяться свойства. Может выбираться по:  
Тегу (селектору): div{...}  
Классу (атрибут класс) .element{...}  
Идентификатору, атрибуту и/или его содержимому (в более редких случаях).
  
Табуляция  
https://guruweba.com/web/tabulyatsiya-v-html-4-sposoba-sdelat-otstup-nerazryvniy-probel/#:~:text=%D0%A1%D0%BF%D0%BE%D1%81%D0%BE%D0%B1%D1%8B%20%D1%81%D0%B4%D0%B5%D0%BB%D0%B0%D1%82%D1%8C%20%D1%82%D0%B0%D0%B1%D1%83%D0%BB%D1%8F%D1%86%D0%B8%D1%8E%20%D0%B2%20HTML%3A&text=%D0%A1%20%D0%BF%D0%BE%D0%BC%D0%BE%D1%89%D1%8C%D1%8E%20%D1%81%D0%BF%D0%B5%D1%86%D1%81%D0%B8%D0%BC%D0%B2%D0%BE%D0%BB%D0%B0%20%D0%BD%D0%B5%D1%80%D0%B0%D0%B7%D1%80%D1%8B%D0%B2%D0%BD%D1%8B%D0%B9%20%D0%BF%D1%80%D0%BE%D0%B1%D0%B5%D0%BB,white%2Dspace%20%D0%B8%20%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D1%8C%20%D0%BF%D1%80%D0%BE%D0%B1%D0%B5%D0%BB%D1%8B.
  
###  Проходим псевдоклассы :link; :visited; :active; :focus; :hover рассказать про сброс hover на примере

  



