# language-change-limiter
VS 2022 Community Edition
In Project -> right click -> Properties -> Configuration Properties -> Linker -> System -> Windows (/SUBSYSTEM:WINDOWS)
In Project -> right click -> Properties -> Configuration Properties -> Linker -> Input -> Comctl32.lib;%(AdditionalDependencies)

Run output exe (from x64 folder) as Administrator.

Disable in Windows -> Settings -> Time & Language -> Typing -> Advanced Typing -> Access Control Keys -> Change sequence -> Disable ALT+SHIFT.
