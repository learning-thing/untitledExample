Input is currently very limited, only a few keys are currently defined:
```json
{"mv_forward", KEY_W},  
{"mv_backward",KEY_S},  
{"mv_left",    KEY_A},  
{"mv_right",   KEY_D},  
{"mv_jump",    KEY_SPACE},  
{"mv_duck",    KEY_LEFT_CONTROL},  
{"ESCAPE",     KEY_ESCAPE},  
{"mv_extra1",  KEY_LEFT_SHIFT},  
{"mv_extra2",  KEY_LEFT_CONTROL}
```

the right side shows the internal names used by raylib, the left side is the name of they key used by 
```js
isKeyDown();
```
and
```js
isKeyPressed();
```


Aside from that, there are mouse/cursor related functions

```js
getMouseX();//Mouse X position
getMouseY();//Mouse Y position

mouseLeftClicked();//Mouse just left pressed
MouseLeftDown();//Mouse button down

getMouseDeltaX();//relative mouse movement between frames (X)
getMouseDeltaY();//relative mouse movement between frames (Y)

captureCursor();//Capture the cursor, hidden and locked into the game window
freeCursor();//release cursor
```


