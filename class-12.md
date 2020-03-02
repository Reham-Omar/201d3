# Read 12

* I read about :
* The < canvas> element which is looks like the < img> element .
* The grid which is the coordinate space
* Drawing rectangle with canvas using :
1- fillRect(x, y, width, height)
2- strokeRect(x, y, width, height)
3- clearRect(x, y, width, height)

* Drawing path with canvas steps :

1- create the path.
2- use drawing commands to draw into the path.
Once the path has been created
3- stroke or fill the path to render it.

* Draw arcs or circles, we use the arc() or arcTo() methods.

## colors :

* To apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.
* Draw semi-transparent shapes by *globalAlpha = transparencyValue* *the value of the **transparency** is between 0-1*
* several properties which allow us to style lines like :

- lineWidth = value
- lineCap = type
- lineJoin = type
- miterLimit = value
- getLineDash()

**two methods to render text in canvas :**
1- fillText(text, x, y [, maxWidth])
2- strokeText(text, x, y [, maxWidth])

*  measure a text and get its width using : **measureText()**
