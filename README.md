# Windows Command-Line Server Manager
A GUI for managing (primarily) Java-based games servers on Windows.

![](https://github.com/stuvik/WindowJavaServerGUI/blob/master/MC_Wills_JavaGameManager2.PNG)

I have developed this application to help manage the running of my personal Minecraft (Java edition) and Rising World servers which utilise Java to run.

This application allows you to run multiple different servers at the same time. It is still very early development. You can also run other command-line applications with customisable switches.

I have developed this GUI in Embarcadero Delphi Community Edition 10.3 with the following dependencies:
* VCL MDI project - sorry, I'll consider an FMX version soon to replace it (I'm after a proof of concept first)
* TDosCommand component freely available via the internal GetIt Package Manager (Note: This is a Windows-only component)
* NexusDB Free Embedded - a nice database engine I have used for some time on other projects.
