# WPF on Linux command
Build and run WPF apps using wine in one command (only tested on [WPF Samples](https://github.com/microsoft/WPF-Samples "WPF Samples") in Gentoo Linux)

## Instructions:
  1. Install [Wine](https://www.winehq.org/ "Wine")
  2. Install the [64bit Windows version of .NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/sdk-10.0.100-preview.6-windows-x64-installer "64bit Windows version of .NET SDK")
  3. Run:
  ```git clone https://github.com/qseftqseft/WPF-on-Linux-command.git && cd WPF-on-Linux-command/ && chmod +x dotnetbuild && sudo ./dotnetbuild```
  4. Run ```dotnetbuild``` in your project directory (where the .csproj file is located)
  5. hope
