# unity-master-server
A working version of the Unity MasterServer

Changes
--
- Fixed various syntax errors
- Upgraded Visual Studio project to VS 2015
- Extended the service file functionality a bit

Usage
-- 

You can run the MasterServer without any arguments, this will use the first ethernet adapter as the main listen address.
```
./MasterServer
```

Accepted parameters are:
```
        -p      Listen port (1-65535), the default port is 23466
        -d      Daemon mode, run in the background
        -l      Use given log file
        -e      Debug level (0=OnlyErrors, 1=Warnings, 2=Informational(default), 2=FullDebug)
        -c      Connection count
        -s      Statistics print delay (minutes)
```
