### Transform  

https://developer.mozilla.org/en-US/docs/Web/CSS/transform

The transform CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.

**Transform**- позволяет изменять геометрию и положение элементов как в 2D, так и в 3D.    
translate - перемещает элемент относительно своего изначального положения.  
transform: translateX(10px);  
transform: translateY(50%);  
transform: translate(20px 50px);
  
**scale** - изменяет размер элемента. Указывается в относительных величинах от 0 до 1.  
**skew** - деформирует стороны элемента, указывается в градусах deg;  
  
**perspective** - задает перспективу для элемента, измеряется в px. Чем меньше значение - тем ближе  
элемент находится к зрителю и наоборот. Работает только совместно с rotate();


### Анимация
  
https://docs.google.com/presentation/d/1_e0i5pPcueSae8NhMgtct_9CTrrFedGZ3chBdUtaTZw/edit#slide=id.g9e3fe1c3d9_0_6  
  
@keyframes - Правило, по которому будет анимироваться элемент.  
  
 После ключевого слова @keyframes необходимо добавить имя анимации (рекомендуется использовать имя, описывающее тип анимации).  
  Внутри правила должны находится ключевые кадры содержащие свойства для начала и конца анимации.  
Также можно использовать более двух кадров, в таком случае необходимо использовать проценты.
  ```
  @keyframes move {
   from {transform: translateX(0);}
   to {transform: translateX(10%);}
}
```
Ключевые кадры from и to идентичны 0% и 100% соответственно.  
  
 После создания правила на него можно ссылаться любому элементу, благодаря свойству animation.

```
  .elem-name{
   animation: move 5s  infinite;
}
```
  
https://docs.google.com/presentation/d/1_e0i5pPcueSae8NhMgtct_9CTrrFedGZ3chBdUtaTZw/edit#slide=id.g631b0001c8_0_173  
  
  
Perspective указывает удаление по оси Z, регулирует глубину сцены (расстояние элемента от зрителя).
