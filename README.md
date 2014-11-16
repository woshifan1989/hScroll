##What is hScroll?
A simple `horizontal scroll` plugin

##What are the advantages of using hScroll
This is a lightweight plugin, it will automatically produce a horizontal scroll bar to replace the default browser scroll bar. Compared with the common custom horizontal scroll bar, it can be displayed anywhere on the screen all the time  if you want, so that we can more easily control the container contents.

##Rely
**jQuery**

##API and param
* **loadHScroll**：create hScroll

    * 1.object(must):
    
        ```javascript
        {
            "idName": "idScroll",  //id name
            "css": {               //hScroll css
                "height": 7,
                "background-color":"#000",
                "position": "fixed",
                "z-index": 999,
                "opacity": 0.2,
                "filter": "alpha(opacity=20)",
                "border-radius": "2px",
                "cursor": "move"
            },
            "lock": false,         //default is false，no lock
            "toBottom": 0,
            "moveFun": function () {},    //move callback
            "loadedFun": function () {}   //loaded callback
        }
        ```
    
    * 2.number(optional)：hScroll offsetLeft

* **removeHScroll**：remove hScroll

    if you don't set parameters or parameters is wrong, it will delete all hScroll that are created by hScroll.
    
    * object（optional）：
        ```javascript
        {
            "idName": "idScroll",  //id name
        }
        ```

* **resizeHScroll**：resize hScroll offset position

    if you don't set parameters or parameters is wrong, it will resize all hScroll that are created by hScroll.
    
    * object（optional）：
        ```javascript
        {
            "idName": "idScroll",  //id name
        }
        ```

* **resetHScroll**：reCreate hScroll

    * 1.object(must):
    
        ```javascript
        {
            "idName": "idScroll",  //id name
            "css": {               //hScroll css
                "height": 7,
                "background-color":"#000",
                "position": "fixed",
                "z-index": 999,
                "opacity": 0.2,
                "filter": "alpha(opacity=20)",
                "border-radius": "2px",
                "cursor": "move"
            },
            "lock": false,         //default is false，no lock
            "toBottom": 0,
            "moveFun": function () {},    //move callback
            "loadedFun": function () {}   //loaded callback
        }
        ```
    
    * 2.number(optional)：hScroll offsetLeft

##Compatibility
**IE7+**、**ff**、**chrome**
