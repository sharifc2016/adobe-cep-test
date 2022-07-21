# adobe-cep-test

### Extension Folders
CEP supports 3 types of extension folders.

Product extension folder. Here is a suggestion, but each point product can decide where this folder should be. Third party extension can't be installed at this location.

${PP}/CEP/extensions (PPs may use different folder.)

#### System extension folder

```
Win(x86): C:\Program Files\Common Files\Adobe\CEP\extensions
Win(x64): C:\Program Files (x86)\Common Files\Adobe\CEP\extensions, and C:\Program Files\Common Files\Adobe\CEP\extensions (since CEP 6.1)
Mac: /Library/Application Support/Adobe/CEP/extensions

```

#### Per-user extension folder

```
Win: C:\Users\<USERNAME>\AppData\Roaming\Adobe\CEP/extensions
Mac: ~/Library/Application Support/Adobe/CEP/extensions

```

### The LogLevel key can be updated at the following location (The application should be restarted for the log level changes to take effect):

For windows ( From run cmd)

    Win: regedit > HKEY_CURRENT_USER/Software/Adobe/CSXS.9
    Mac: /Users/<USERNAME>/Library/Preferences/com.adobe.CSXS.9.plist

### Add Debug:
    Windows: Open regedit > HKEY_CURRENT_USER/Software/Adobe/CSXS.9, then add a new entry PlayerDebugMode of type “string” with the value of “1”.
    Mac: In the Terminal, type: defaults write com.adobe.CSXS.9 PlayerDebugMode 1


 ## Set Debug mode
 https://github.com/Adobe-CEP/Getting-Started-guides/blob/master/Client-side%20Debugging/readme.md#set-the-debug-mode
 
 ## Resources
 https://github.com/Adobe-CEP/Getting-Started-guides
 
