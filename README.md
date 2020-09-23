<div align="center">

## API call for Playing a sound


</div>

### Description

This API call is used to play a .wav file. Hope you enjoy the code. Peace!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Mike\-Ejeet 9t9](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/mike-ejeet-9t9.md)
**Level**          |Intermediate
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VB Script, ASP \(Active Server Pages\) 
**Category**       |[Windows API Call/ Explanation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-api-call-explanation__1-39.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/mike-ejeet-9t9-api-call-for-playing-a-sound__1-5041/archive/master.zip)

### API Declarations

This code is all API


### Source Code

```
To use this API paste the following code into a module:
Public Declare Function sndPlaySound Lib "winmm.dll" Alias "sndPlaySoundA" (ByVal lpszSoundName As String, ByVal uFlags As Long) As Long
Then to call the API type:
Variable = sndPlaySound (Location, 1)
So for example to play a .wav file located at C:\Sounds\sound.wav type:
Variable = sndPlaySound ("C:\Sounds\sound.wav, 1)
Thats it!
```

