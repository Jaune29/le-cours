# bonjour ici prendront place les essais de programmes microbit via python

## test 1:

```python
from microbit import *
while True:
   display.show(Image.ANGRY)
```

## test 2:

```py
from microbit import *

while True :
   if button_b.is_pressed and button_a.is_pressed():
       display.show(Image.HAPPY)
   else:
       display.show(Image.SAD)
```
*note : le programme réagi seulement à l'appui du bouton en seconde place sur la ligne du programme*
