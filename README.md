# adobe-cep-test

### Load Directory:
    Windows: C:\Users\<USERNAME>\AppData\Local\Temp\cep_cache\
    Mac: /Users/<USERNAME>/Library/Caches/CSXS/cep_cache/


### The LogLevel key can be updated at the following location (The application should be restarted for the log level changes to take effect):

For windows ( From run cmd)

    Win: regedit > HKEY_CURRENT_USER/Software/Adobe/CSXS.9
    Mac: /Users/<USERNAME>/Library/Preferences/com.adobe.CSXS.9.plist

### Add Debug:
    Windows: Open regedit > HKEY_CURRENT_USER/Software/Adobe/CSXS.8, then add a new entry PlayerDebugMode of type “string” with the value of “1”.
    Mac: In the Terminal, type: defaults write com.adobe.CSXS.8 PlayerDebugMode 1


 ## Set Debug mode
 https://github.com/Adobe-CEP/Getting-Started-guides/blob/master/Client-side%20Debugging/readme.md#set-the-debug-mode
 
 ## Resources
 https://github.com/Adobe-CEP/Getting-Started-guides
 
