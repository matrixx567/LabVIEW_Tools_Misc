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
- Find non-project-files (based on https://forums.ni.com/t5/Community-Documents/Feature-Find-Non-Project-Files/ta-p/4347088)

## Configuration 

The existing tools can be configured within `LabVIEW.ini`:

Configuration of command line, VSCode and Sourcetree

```ini
MNProjects.Misc.Cmd="cmd.exe"
MNProjects.Misc.Cmd="cmd.exe /k %CMDER_ROOT%\vendor\init.bat"

MNProjects.Misc.Code="c:\Program Files\Microsoft VS Code\code.exe"

MNProjects.Misc.Sourcetree="Sourcetree.exe"

;Exclude folders for Delete empty folders and Find non-project files
MNProjects.Misc.FindNonProjectFiles.FoldersToExclude=".git;.svn;build;builds"
```


## Tips

https://labviewwiki.org/wiki/How_to_do_Menu_Launch_VIs
