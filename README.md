# Language Change Limiter

## Description
This is a tool that helps restrict language changes between two languages in Windows (currently English and Greek) that are installed in your PC.
This is helpful if you have multiple languages installed in your PC, but you primarily use only two most of the time and thus you can change fast with Alt+Shift when needed between the two.
For the rest languages you would switch manually by selected the dedicated language, without Alt+Shift. You have to disable Alt+Shift combination from Windows settings and allow this app to handle it.

## Requirements
- VS 2022 Community Edition
	- In Project -> right click -> Properties -> Configuration Properties -> Linker -> System -> Windows (/SUBSYSTEM:WINDOWS)
	- In Project -> right click -> Properties -> Configuration Properties -> Linker -> Input -> Comctl32.lib;%(AdditionalDependencies)
- Run output exe (from x64 folder) as Administrator.
- Disable in Windows -> Settings -> Time & Language -> Typing -> Advanced Typing -> Access Control Keys -> Change sequence -> Disable ALT+SHIFT.

## TODO list
- Make languages configurable from Settings
- Setting for Start automatically
- Settings Portable
- Icon change
- Support more than 2 languages
- Investigate Administrator permissions if needed
- Translate to Greek and other languages

