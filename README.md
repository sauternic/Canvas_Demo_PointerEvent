# Canvas Demo PointerEvent

## Einfaches Zeichnen Programm

**Das Pointer Event ist Genial! :)**

Mit ihm läuft das Maus und das Touch Event in einem!  
Zudem läuft es auf allen wichtigen Browsern!!! :))))

Siehe im Code wie es gebraucht wird:

```JavaScript
canvas1.addEventListener('pointerup', handlerPointerup);
canvas1.addEventListener('pointerdown', handlerPointerdown);
canvas1.addEventListener('pointermove', handlerPointermove);

//pointerup => mouseup
//pointerdown => mousedown
//pointermove => mousemove
```

## Sehr Wichtig!

CSS Eigenschaft für Canvas auf:  
```CSS
/*Damit Canvas nicht Scrollt!*/
touch-action: none;
```


# [Vorschau](https://htmlpreview.github.io/?https://github.com/sauternic/Canvas_Demo_PointerEvent/blob/master/canvas_Zeichnen_Maus_und_Touch.html)
### läuft auf:
- IE
- Edge
- Chrom
- Firefox
- Opera
