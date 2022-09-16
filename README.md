# GameWidgets

**Check PyPi for download**

*Files not included in Repositry*

Welcome To the github Repositry!

**Install**

* Mac

  ```pip3 install GameWidgets```
  
* Windows

  ```pip install GameWidgets```

**Specs**

* 42 Files
* ~18 Kilobytes

**Files**

* Btn
* Clock
* Colors
* Cursor
* Sound
* Animatrix
* Draw (in progress)
* Sprite (In progress)
* Tile (In progress)
* ScreenCommands
* Joystick (In progress)
* Hat (In progress)
* R1_R2 (In progress)

**Functions and their parameters**

*Btn*

Normal_Btn:
  - __init__(screen,fgcolor,xy,font,size,text,Outline,Thickness)    **Note: do not write .ttf**
  - Draw()
  - Detect(event,mousepos)

Active_Btn:
  - __init__(screen,Colors,text,**kwarg)
  - Draw()
  - Detect(event,mousepos)

*Clock*

Clock:
  - __init__(FPS)
  - Set_Up_Clock()
  - Set_FPS()
  - Set_Delay(TIME,milli)

*Colors*
  - None.      **Note: No functions due to 155 RGB Codes**

*Cursor*

Rect_Cursor:
  - __init__(screen,Color,**kwarg)
  - Draw()

*Sound*

Sound:
  - __init__(Sound_File)
  - Play

*ScreenCommands*

Screen
  - __init__(**kwarg)
  - Return()
  - Register_Master(screen)
  - Set_Icon()
  - Fill()
  - Return_HW(Type)

*Animatrix*

Animation
  - __init__(screen,Location,Pictures,S_Per_Frame,FSize)
  - Play
  - Update()
  - Draw()

**Test File and others are not shown due to imperfections**

More info:

https://GameWidgets-Website.superguy123456.repl.co
