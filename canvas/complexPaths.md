## drawing complex paths

- a path is simply a set of points, connected by lines or curves and
  is either open or closed.
- the context only has one and ***only*** one path
- a closed path has an end point that is also the start point

- to begin a path, call the ***beginPath()*** method

- to add paths, use one or more drawing routines

- to stroke the current path, call ***stroke()***

- to fill it, call ***fill()***

- to close the current path, call ***closePath()***

### arcs

- arcs are curves that are portions of a circle(which is 360deg arc)
- you can use the ***arc function*** or the **arcTo function***

#### arcs functions/methods:

#### arc fn
- adds an ***arc** to the current path that starts at ***x***, ***y*** and has ***a*** radius of ***r***, with a starting angle of ***sA***, and an ending angle of ***eA***.            
  The ***aC*** argument is true, if the  arc is ***anti-clockwise***

ex:

``` 
      arc(x, y, r, sA, eA, aC)
```

#### arcTo fn
- adds an ***arc*** to the current path that starts at the current ***pen*** position, has the given control points, and a radius of ***r***.

ex:

```
      arcTo(x1,y1,x2,y2,r)

```

#### closePath()
- closes the current drawing path

















