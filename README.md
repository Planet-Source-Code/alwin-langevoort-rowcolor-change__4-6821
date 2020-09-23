<div align="center">

## RowColor Change


</div>

### Description

If you need a fast and simple cowcolor-changer, this is the shortest you'll ever find!

For advanced users: put it in your stylesheet..

(I could use some ratings...)
 
### More Info
 
Just put this in a Do While above the recordset you need; works fine! just one line of code :o)


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Alwin Langevoort](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/alwin-langevoort.md)
**Level**          |Beginner
**User Rating**    |3.4 (17 globes from 5 users)
**Compatibility**  |ASP \(Active Server Pages\), VbScript \(browser/client side\)

**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__4-33.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/alwin-langevoort-rowcolor-change__4-6821/archive/master.zip)

### API Declarations

nah


### Source Code

```
<%If rc="" Or rc="#FFFFFF" Then rc="#CECECE" Else rc="#FFFFFF"%>
_
<td bgcolor="<% =rc %>">
```

