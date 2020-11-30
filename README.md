# Macro
rs3 Macro
This is an ahk runescape 3 brid macro 
#NoEnv  
#keyHistory 0
#IfWinActive, RuneScape
SendMode Input

Random, myVar, 45, 60

; This is a ahk macro designed to switch for you in runescape 3

; F1::, F2::, F3::, F4::, are all hotkeys in the script if you want to change them just edit the script
; and save and restart it. Example: 1:: save script and restart then 1 would be a hotkey.

; If you want to change the keys stored inside the hotkeys make sure you keep it between{}
; Example Send {j down}
;         sleep
;         Send {j up}

; Random, myVar, 45, 60 is a random delay added for anti script detection

F1::

Send {1 down}{2 down}{3 down}{4 down}{5 down}{6 down}
Sleep, %myVar%
Send {1 up}{2 up}{3 up}{4 up}{5 up}{6 up}
return

F2::

Send {q down}{w down}{e down}{r down}{t down}{y down}
Sleep, %myVar%
Send {q up}{w up}{e up}{r up}{t up}{y up}
return

F3::

Send {a down}{s down}{d down}{f down}{g down}{h down}
Sleep, %myVar%
Send {a up}{s up}{d up}{f up}{g up}{h up}
return

F4::

Send {j down}{k down}{s down}{d down}{f down}{g down}{h down}
Sleep, %myVar%
Send {j up}{k up}{s up}{d up}{f up}{g up}{h up}
return
