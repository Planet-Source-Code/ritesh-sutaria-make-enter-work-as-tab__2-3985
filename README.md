<div align="center">

## Make ENTER work as TAB


</div>

### Description

this code make ENTER work as TAB

when the user press ENTER than it moves to next control then same as u press TAB and it goes to next control
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ritesh Sutaria](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ritesh-sutaria.md)
**Level**          |Advanced
**User Rating**    |4.0 (16 globes from 4 users)
**Compatibility**  |
**Category**       |[Controls/ Forms/ Graphics/ Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/controls-forms-graphics-menus__2-59.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ritesh-sutaria-make-enter-work-as-tab__2-3985/archive/master.zip)

### API Declarations

<INPUT TYPE="TEXT" onKeyDown="focusttonextcontrol()">


### Source Code

```
function focustonextcontrol()
{ if (event.keyCode)==13 event.keyCode=9;
}
call this function in anyobject's onKeyDown event
```

