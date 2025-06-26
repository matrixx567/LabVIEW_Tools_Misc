# LabVIEW_Tools_Misc

Different tools for easier LabView user experience:

e.g.:

- Open LabView programs folder in Windows Explorer
- Open vi.lib folder in Windows Explorer
- Open temp folder in Windows Explorer
- Open data folder in Windows Explorer

- Open project in Windows Explorer
- Open project with VsCode
- Open project with Sourcetree
- Open project in Terminal

- Delete empty folders
- Find non-project-files

## Configuration 

The existing tools can be configured within `LabVIEW.ini`:

Configuration of command line, VSCode and Sourcetree

```ini
MNProjects.Misc.Cmd="cmd.exe"
MNProjects.Misc.Cmd="cmd.exe /k %CMDER_ROOT%\vendor\init.bat"

MNProjects.Misc.Code="c:\Program Files\Microsoft VS Code\code.exe"

MNProjects.Misc.Sourcetree="Sourcetree.exe"

MNProjects.Misc.FindNonProjectFiles.FoldersToExclude=".git;.svn"
```

Exclude folders for Delete empty folders and Find non-project files

```ini
MNProjects.Misc.FindNonProjectFiles.FoldersToExclude=".git;.svn"
```



## LabView_VIAnalyzer
My Configuration for the VI Analyzer


### Sources 

https://forums.ni.com/t5/VI-Analyzer-Enthusiasts/Test-Launch-Actor-Called-in-Pre-Launch-Init/ta-p/3538224  
https://forums.ni.com/t5/VI-Analyzer-Enthusiasts/CheckLVLibUsage-llb/ta-p/3501372  


- [CaseSensitiveCaseStructure.llb](https://forums.ni.com/docs/DOC-29189)
- [CheckLVLibUsage.llb](https://forums.ni.com/docs/DOC-41432)
- [CheckWhitespaceInFPnames.llb](https://forums.ni.com/docs/DOC-29191)
- [Constant Documentation.llb](https://forums.ni.com/docs/DOC-35487)
- [Separated Compiled Code.llb](https://forums.ni.com/docs/DOC-29170) - Included in LV2020
- [Useless Close Reference.llb](https://forums.ni.com/t5/VI-Analyzer-Enthusiasts/Test-Useless-Close-Reference/ta-p/3743283)




## Shortcut Menu Plugins (Right-Click Menu)
- [Add Custom Bookmark](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Add-Bookmark-llb/ta-p/3613618)
- [Add to Class Data](https://github.com/TomsLabVIEWExtensions/Add-data-to-class/blob/master/Add%20to%20class.llb)
- [Add Value Change Event](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Add-Value-Change-Event-llb/ta-p/3908644)
- [Assign to Connector Pane](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Assign-to-Connector-Pane-llb/ta-p/4053922)
- [Change to bundle or unbundle](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Change-To-Bundle-Or-Unbundle-llb/tac-p/4045629)
- [Copy Delimited Data](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Copy-Delimited-Data-llb/ta-p/3538576)
- [Create IPES Border Node](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Create-IPES-Border-Node-llb/ta-p/3712355)
- [Expand Cluster Constant](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Expand-Cluster-Constant-llb/ta-p/3517818)
- [Find Events](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Find-Events-llb-for-ctrl-ind-FPTerm-local-var-ctrl-ref/ta-p/3518130)
- [Grow to N](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Grow-to-n-llb/ta-p/3523765)
- [Hide or Show FP Elements](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Hide-or-Show-FP-Controls-llb/ta-p/4045090)
- [Insert IPE in Any Wire](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Insert-IPE-in-Any-Wire-AZ-llb/ta-p/4012959)
- [Move up or Down Bundle Element](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Move-unbundle-item-llb/ta-p/4015889)
- [Multi-select change variable](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Multi-select-Change-Local-Direction/ta-p/3526840)
- [Open Message Handler](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Open-Message-Handler-llb/ta-p/3871400)
- [Set Current Event to Value Change](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Set-Current-Event-to-Value-Change-llb/ta-p/3538838)
- [Wire Multiple Items to Bundler](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Wire-Multiple-Items-to-Bundler-llb/ta-p/3517939)



## TODO

[Clear Array - Ctrl +C](https://forums.ni.com/t5/Quick-Drop-Enthusiasts/Quick-Drop-Keyboard-Shortcut-Clear-Array/gpm-p/3529314)
Use this quick drop and create a right click framework


## Useful resources


https://gitlab.com/felipe_public/dev-environment
https://code.hampel-soft.com/hse-labs/hse-scripting-tools.git
https://github.com/LabVIEW-Open-Source/ui-tools-controls-addon.git



### G-CLI Tools

https://sas-gcli-tools.gitlab.io/#third-party-cli-tools-for-other-common-commands

https://www.vipm.io/package/sas_workshops_lib_vip_installer_for_g_cli/
https://www.vipm.io/package/lvos_lib_caraya_cli_extension/
https://www.vipm.io/package/sas_workshops_lib_vipb_builder_for_g_cli/
https://www.vipm.io/package/sas_workshops_lib_clearlvcache_for_g_cli/
https://www.vipm.io/package/sas_workshops_lib_lunit_for_g_cli/
https://www.vipm.io/package/sas_workshops_lib_vitester_for_g_cli/
https://www.vipm.io/package/wiresmith_technology_lib_g_cli/
https://www.vipm.io/package/sas_workshops_lib_lvbuildspec_for_g_cli/
https://www.vipm.io/package/sas_workshops_lib_vipc_applier_for_g_cli/

https://github.com/ni/actor-framework


