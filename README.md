# showSmooth
class thats make simple onslide effect
Usage:
1. js document must be type:"module"
2. add files to site.
3. Import class with code:
 -```import Show from "./showOnScroll.js";```
    
4. where Show is class name;
5. constent is array/nodelist od elements that you want animate
6. second parametr is boolean. if true its delete first element of given tab/nodelist
  !important:
    -in all elements you must add "opacity: 0".
    -you must add css file in app you site.
7. invoke class
    -```new Show(content, true);```
