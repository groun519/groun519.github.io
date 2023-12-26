---
published: true
layout: archive
title:  "c++ 프로젝트 생성 오류"
categories:
  - ue_error
---

```
Running C:/Program Files/Epic Games/UE_5.3/Engine/Build/BatchFiles/Build.bat  -projectfiles -project="C:/Users/groun/Documents/Unreal Projects/P_Cube/P_Cube.uproject" -game -rocket -progress
Using bundled DotNet SDK version: 6.0.302
Running UnrealBuildTool: dotnet "..\..\Engine\Binaries\DotNET\UnrealBuildTool\UnrealBuildTool.dll" -projectfiles -project="C:/Users/groun/Documents/Unreal Projects/P_Cube/P_Cube.uproject" -game -rocket -progress
Log file: C:\Users\groun\AppData\Local\UnrealBuildTool\Log_GPF.txt

Some Platforms were skipped due to invalid SDK setup: IOS, Android, Linux, LinuxArm64.
See the log file for detailed information


Generating VisualStudio project files:
Discovering modules, targets and source code for project...
Visual Studio 2022 is installed, but is missing the C++ toolchain. Please verify that the "MSVC v143 - VS 2022 C++ x64/x86 build tools (Latest)" component is selected in the Visual Studio 2022 installation options.
Visual Studio 2022 x64 must be installed in order to build this target.
```

언리얼 5.3.2버전에서 c++프로젝트를 생성할 때 발생했다.
비주얼 스튜디오의 버전이 정상적이지 않아 발생하는 오류.

비주얼 스튜디오를 재설치하면 해결된다.
