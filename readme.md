# try-gitter-chatBox
same as:

(1) all in js(success in Codepen) :    https://codepen.io/kiecoo/pen/PQZdOO

(2) separate into html &js (success in Codepen): https://codepen.io/kiecoo/pen/YaqdJv

----
# difference between 2 ways

have tried 2 ways to let chatBox to success & both of them failed


don't do this one <1. repo of [makeGitterChatbox](https://github.com/kiecoo/makeGitterChatbox/blob/master/index.html)>   :[output](https://kiecoo.github.io/makeGitterChatbox/) is all blank


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
