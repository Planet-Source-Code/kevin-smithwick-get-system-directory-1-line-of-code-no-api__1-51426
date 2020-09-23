<div align="center">

## Get System Directory \-\- 1 Line of Code No API


</div>

### Description

Get the system directory with 1 line of code and no API.
 
### More Info
 
I've tested this on Windows 9x/2000/NT/XP, but I cannot say it will work on ME.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Kevin Smithwick](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/kevin-smithwick.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Files/ File Controls/ Input/ Output](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/files-file-controls-input-output__1-3.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/kevin-smithwick-get-system-directory-1-line-of-code-no-api__1-51426/archive/master.zip)





### Source Code

msgbox Environ$("windir") & IIf(Len(Environ$("OS")), "\SYSTEM32", "\SYSTEM")

