# RunningProcs

VB6 process/module lister from TheScarms (`RunningProcs1`): lists running processes and their modules using ToolHelp32 on Win9x and PSAPI (`EnumProcesses` / `EnumProcessModules`) on NT. Open `RunningProcs1.vbp` under the nested VB Samples path in the VB6 IDE (distribute `psapi.dll` on NT).

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `RunningProcs1` (`RunningProcs1.vbp`) | VB6 | WinForms exe | Enumerate processes and loaded modules |
