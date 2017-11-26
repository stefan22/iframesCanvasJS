## canvas element

- provides web pages with a drawing surface..for drawing:    
  graphics, shapes, images, text, etc

- supported in all latest browsers: IE9+, Chrome3+, Safari3+, Firefox3+

- pages can have more than one canvas and overlap
- canvas contents are created on-the-fly using script
- once they're drawn, they're forgotten by the script engine.
- canvas is good for dynamic visual media, but contents are not part of the   
  page.
- for things that you want to manipulate later using js, you'll use svg


## canvas tag

- the canvas coordinate system starts at the upper left, with increasing
  values of ***X*** going left to right, and increasing values of ***Y*** from
  top to bottom
- canvas element start out invisible
  

 ``` 
           x
      y    ---------->
      |    _______________
      |   |(0,0)          |
      |   |               |  
      •   |  width,height |
          |_______________| 
         
 ```     
 
 - canvas declared w/word canvas -->  ***<canvas>***
 
 ex:
 
 ```
      <canvas id="canvasa1" width="400" height="300">
         Fall content if needed support for IE < 9 (not)
      </canvas>
 
 ```




## iframesJS &nbsp; <kbd>:trumpet:</kbd>
- loading separate html files into existing doc
- Other domain loading - nope - ***Same origin Policy** applies here as well.
- But it is possible with ***postMessaging interface*** cross-window messaging &nbsp; :rocket:

- iframe-to-iframe

<kbd>common iframe implementation</kbd>
![](images/commonIframe.png)

<br/>

<kbd>BOM</kbd>
<br/>
![](images/bom1.jpg)   



<kbd>ex:</kbd>

```
    <iframe id="ifrm" src="demo.html"></iframe>

```

<kbd>:checkered_flag:</kbd> &nbsp; iframe's src attr specifies ***Url of doc*** to be displayed in iframe
- using more css attrs than iframes attrs
- scrollbars will appear automatically if needed
- use js to set height to remove them

<kbd>:closed_umbrella:</kbd>
```
   iframe {
       border:1px solid #ccc;
       width:80%; height:120px;
   }

```
