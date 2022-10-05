# bonjour ici prendront place les essais de programmes microbit via python

## test 1:

```python
from microbit import *
while True:
   display.show(Image.ANGRY)
```

## test 2: la fonction ET

```py
from microbit import *

while True :
   if button_b.is_pressed() and button_a.is_pressed():
       display.show(Image.HAPPY)
   else:
       display.show(Image.SAD)
```

## test 3: fonction NON

```py
from microbit import *

while True:
    if not button_a.is_pressed():
        display.show(Image.ANGRY)
    else:
        display.show(Image.BUTTERFLY)
```

## test 4: la fonction OU

```py
from microbit import *

while True :
   if button_a.is_pressed() or button_b.is_pressed():
       display.scroll("NEVER GONA GIVE YOU UP")
```
