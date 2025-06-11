# LabVIEW_Tools_Misc

Different tools for easier LabView user experience:

e.g.:

- Open LabView programs folder in Windows Explorer
- Open vi.lib folder in Windows Explorer
- Open project in Windows Explorer
- Open project with VsCode
- Open project with Sourcetree
- Open project in Terminal

## Configuration 

The existing tools can be configured within `LabVIEW.ini`:

```ini
MNProjects.Misc.Cmd="cmd.exe"
MNProjects.Misc.Cmd="cmd.exe /k %CMDER_ROOT%\vendor\init.bat"

MNProjects.Misc.Code="c:\Program Files\Microsoft VS Code\code.exe"

MNProjects.Misc.Sourcetree="Sourcetree.exe"
```