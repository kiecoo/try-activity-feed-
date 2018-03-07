# try-gitter-chatBox
same as: https://codepen.io/kiecoo/pen/PQZdOO

----
# difference between 2 ways

have tried 2 ways to let chatBox to success & both of them failed


<1. repo of [makeGitterChatbox](https://github.com/kiecoo/makeGitterChatbox/blob/master/index.html)>   :[output](https://kiecoo.github.io/makeGitterChatbox/) is all blank


In html:

using
```
makeGitterChatbox(exampleProfile)
```


<2. repo of this one>            :[output](https://kiecoo.github.io/try-gitter-chatBox/) is all pink(just show background of body)


In html: 

using
```
var x = makeGitterChatbox(exampleProfile)
document.body.appendChild(x)

```
instead of 
```
makeGitterChatbox(exampleProfile)
```
