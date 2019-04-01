## Redistributables

1. Install DirectX
2. Install XNA Framework 4.0 Redistribution
3. Install XNA Game Studio 4.0 Platform Tools
4. Install XNA Game Studio 4.0 Shared
5. Install XNA Game Studio 4.0.vsix

## Game Studio

Copy everything from

```
C:\Program Files (x86)\MSBuild\Microsoft\XNA Game Studio
```

to

```
C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\MSBuild\Microsoft\XNA Game Studio
```

## Build Framework

Place all .dll files located in Microsoft Build Framework folder inside the following directory:

```
C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\MSBuild\15.0\Bin
```

Open the Visual Studio developer command prompt by searching for `Developer command prompt for VS 2019` as administrator and execute the following codes:

```
cd C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\MSBuild\15.0\Bin
```

and

```
gacutil /i Microsoft.Build.Framework.dll
```

You're good to go!

### Links

Archive downloaded from [MXA CodePlex](https://archive.codeplex.com/?p=mxa)

XNA 4.0 for [VS 2017](https://gist.github.com/roy-t/2f089414078bf7218350e8c847951255)
