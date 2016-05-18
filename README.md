![](https://github.com/Oceanware/Mole2015/blob/master/molelogo.png)

# Mole2015
Mole is a debugger visualizer that runs in Visual Studio while you are debugging .NET applications. Mole makes debugging easier because it provides a comprehensive view into all of your application’s visual and data objects.

Mole enables developers to view, edit, search, compare, and drill into object properties and fields.

## Installation Instructions

Close Visual Studio 2015.

Download the zip file using the Download button.

In Windows Explorer, right-click the downloaded zip file, click the "unblock" check box, and then click "apply" and then "close" buttons.

Unzip the zip file.

Copy the two files, `Mole.Visualizer.VS2015.dll` and `Mole.Visualizer.VS2015.dll.config` to your `Documents\Visual Studio 2015\Visualizers` folder.

Start Visual Studio 2015 and enjoy happy debugging.

## ASP.NET Developers Please Read This

When using Mole with ASP.NET projects that utilize IIS as the web server, as opposed to the Visual Studio's built in web server, you MUST give the account that the web site is running under, Read and Read & Execute permissions to the \Visualizers directory.

If you do not do this, you will get an exception when attempting to load the visualizer in a debugging session. You would get this exception for any visualizer and not just Mole. This is because the ASPNET account has very few permissions on your computer. Adding these permissions prevents this exception.

## Documentation and Training Videos
[https://oceanware.wordpress.com/mole-visual-studio-debugger-visualizer/](https://oceanware.wordpress.com/mole-visual-studio-debugger-visualizer/ "Mole Documentation and Training Videos")
