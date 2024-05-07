# disk-windows

## C:\

```cmd
dir
```

```
 Volume in drive C is Windows-SSD
 Volume Serial Number is 1609-4783

 Directory of C:\

2023/08/31  19:47    <DIR>          $WINDOWS.~BT
2023/10/09  20:01            12,288 DumpStack.log
2023/08/31  23:49    <DIR>          ESD
2023/09/03  12:22    <DIR>          Microsoft
2023/08/05  04:02    <DIR>          MTSN
2024/04/05  02:48    <DIR>          PassNeo
2023/08/05  03:51    <DIR>          PerfLogs
2024/05/06  15:55    <DIR>          Program Files
2024/05/06  15:56    <DIR>          Program Files (x86)
2023/11/26  20:06    <DIR>          Users
2024/05/05  05:30    <DIR>          Windows
               1 File(s)         12,288 bytes
              10 Dir(s)  58,452,312,064 bytes free
```

- DumpStack.log

    $$
    12,288 bytes = \frac{12,288}{1024} KB = 12 KB
    $$

    是一个由Windows系统生成的日志文件，通常用于记录系统错误或崩溃时的堆栈信息。当系统出现问题时，这个文件可以帮助开发者或技术支持人员诊断问题。这个文件通常不会占用太多的磁盘空间，但如果它变得过大，可能需要进行清理。

- $WINDOWS.~BT

    是一个由Windows系统在进行系统升级或安装时创建的临时文件夹。它包含了升级或安装过程中需要的文件。

    在升级或安装完成后，这个文件夹通常会被系统自动删除。但在某些情况下，它可能会被保留下来，以便在出现问题时进行故障排查。

    请注意，手动删除这个文件夹可能会导致系统升级或恢复功能出现问题。如果你需要清理磁盘空间，建议使用Windows的磁盘清理工具，而不是直接删除这个文件夹。

## C:\Windows

Windows文件夹是Windows操作系统的主要安装目录，它包含了操作系统的所有核心文件和大部分系统程序。这个文件夹通常包括以下几个子文件夹：

- System32：包含了大部分的系统文件和驱动程序。
- SysWOW64：在64位Windows系统中，用于存放32位应用程序和驱动程序的文件。
- Temp：用于存放临时文件。
- WinSxS：存放系统组件和运行库，支持Windows的组件化服务。

请注意，不应该手动修改或删除这个文件夹中的文件，因为这可能会导致系统不稳定或无法启动。

## C:\Program Files 和 C:\Program Files (x86)

C:\Program Files是Windows系统中的一个重要文件夹，它通常用于存放64位的应用程序。当你安装一个应用程序时，安装程序通常会将应用程序的文件放在这个文件夹中。

另外，还有一个名为C:\Program Files (x86)的文件夹，它用于存放32位的应用程序。这是为了在64位的Windows系统中，能够同时支持运行32位和64位的应用程序。

请注意，这两个文件夹都是系统重要的部分，不应该手动删除或移动其中的文件，除非你清楚自己在做什么，否则可能会导致应用程序无法运行或系统不稳定。

## C:\ProgramData

## C:\Users
