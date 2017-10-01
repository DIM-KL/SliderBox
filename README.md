# SliderBox

Объект JavaScript который возвращает контейнер HTMLDivElement содержащий элементы переданные в параметре конструктора. А также кнопку рядом с ним, при нажатие на которую, контейнер         сворачивается или расркрывается.

## CONSTRUCTOR ##
<pre>
SliderBox(content: HTMLElement, optional params {btnpos: enum("left", "right", "top", "bottom"),
                                                 btnbg: color,
                                                 btnborderradius: int,
                                                 btncaption: {"open": string, "close": string},
                                                 collapse: boolean})                             
</pre>

## parametrs ##

**content**- содержимое контейнера  

**params** - объект опциональных параметров:  
- **btnpos** - строковой параметр определяющий положение кнопки относительно контейнера. Принимает следующие значения в виде строки;  
    - *"left"*

- btnbg
- btnbg
- btnborderradius
- btncaption
- collapse

 
