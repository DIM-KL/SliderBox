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
    - *"right"*: string - кнопка справа от контейнера  
    - *"left"*: string - кнопка слева от контейнера  
    - *"top"*: string - копка сверху от контейнера  
    - *"bottom"*: string - кнопка снизу от контейнера  

по умолчанию *"left"*
- **btnbg**: color - строка содержащая цвет в лбой форме допускаемой стандартом цвета css. По умолчанию *'#DAA520'*
- **btnborderradius**: number - число определющее на сколько пикселей будут закруглены выступающие краи кнопки. По умолчанию на *4* пикселя
- **btncaption**: object - объект определяющий надпись кнопки:  
    - **open**: string - надпись при открытом контейнере
    - **close**: string - надпись при закрытом контейнере
    
значение полей по умолчанию зависит от значение параметра **btnpos**:  
при **btnpos** = *"right"* **btncaption** = {**"open"**: *"&#8656"*, **"close"**: *"&#8658"*}    
при **btnpos** = *"left"* **btncaption** = {**"open"**: *"&#8658"*, **"close"**: *"&#8656"*}    
при **btnpos** = *"top"* **btncaption** = {**"open"**: *"&#8659"*, **"close"**: *"&#8657"*}    
при **btnpos** = *"bottom"* **btncaption** = {**"open"**: *"&#8657"*, **"close"**: *"&#8659"*}    


- **collapse**: bolean - при *true* контейнер свёрнут. При *false* развёрнут. Значение по усолчание - *true*  
## properties ##


 
