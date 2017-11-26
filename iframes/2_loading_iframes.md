### loading iframes

- Loading new documents can also be done using ***target*** attr

ex:
this link loads a page called page.html into an iframe with name of ***ifrm***
(and no js required... well not really)

```
    <a href="page.html" target="ifrm">Link</a>               

```



### 3 ways to change Url in Iframe (load a doc in iframeObj)

1- ***getElementById*** to reference iframe elem and new ***Url*** to ***src*** property

ex:

```
     var el = document.getElementById('ifrm');
     el.src = url; // assign url to src property      
```


2- ***frames array*** used to obtain a ***reference*** to iframe window, assigning ***Url*** to its ***location*** property

ex:

```
     window.frames['ifrm'].location = url;
```


3- ***location.replace*** method to avoid having the new Url added to the ***browser history***

```
     window.frames['ifrm'].location.replace(url);
```


### notes
If you want a link in the ***iframed*** doc to load a Url in main window, then ***include*** a ***target*** attr set to ***_parent***

```
    <a href="page.html" target="_parent">link</a>
```


### loading doc from other domains into iframes :( same old rules apply :(
+ ***Same Origin Policy***





































