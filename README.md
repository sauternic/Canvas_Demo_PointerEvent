# Canvas Demo PointerEvent

## Einfaches Zeichnen Programm

**Das Pointer Event ist Genial! :)**

Mit ihm läuft das Maus und das Touch Event in einem!  
Zudem läuft es auf allen wichtigen Browsern!!! :))))

# [Show](https://sauternic.github.io/Canvas_Demo_PointerEvent/)

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

### läuft auf:
- IE
- Edge
- Chrom
- Firefox
- Opera

Ps:  
Siehe auch mein Aufzeichnungs-Programm: [link](https://github.com/sauternic/Canvas_JavaScript_Zeichnen_Aufzeichnen_Animation)
