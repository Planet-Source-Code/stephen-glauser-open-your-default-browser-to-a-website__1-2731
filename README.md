<div align="center">

## Open your Default Browser to a Website


</div>

### Description

This is a simple, yet very useful One Line code, that will open your (the user) Default Web Browser, and send you to a user specified URL.
 
### More Info
 
URL


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Stephen Glauser](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/stephen-glauser.md)
**Level**          |Unknown
**User Rating**    |4.2 (161 globes from 38 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Internet/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-html__1-34.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/stephen-glauser-open-your-default-browser-to-a-website__1-2731/archive/master.zip)





### Source Code

```
Sub OpenUrl(URL As String)
Rem Written by Stephen Glauser
Rem Last Update: August 1, 1999
Rem This will the users Default Web Browser
Rem and send them to the specified URL
Rem Call OpenUrl("http://www.microsoft.com")
Shell ("Explorer " & URL$), vbNormalNoFocus
End Sub
```

