# zlib.install

Windows one-line installer for zlib library.

# Usage

Open your command prompt as Administrator and enter

```
powershell -Command "(New-Object Net.WebClient).DownloadFile('https://raw.githubusercontent.com/horta/zlib.install/master/install.bat', 'install_zlib.bat')"; ./install_zlib.bat; del install_zlib.bat
```

# Requirements

- Install Visual Studio with C++. Make sure to select Desktop Development with C++ while doing so.
- Make sure you have CMake: https://cmake.org/download/
- Make sure you have PowerShell: https://duckduckgo.com/?q=install+powershell+on+windows

The video https://www.youtube.com/watch?v=IsAoIqnNia4 presents a step-by-step tutorial
on how to install Visual Studio with support for C++.
