浙江工业大学操作系统大型实验————模拟Unix文件系统
Zhejiang University of Technology, Simple Unix File System
-----------------------------------------------------------
实现功能
01.Exit system....................................(exit)
02.Show help information..........................(help)
03.Show current directory..........................(pwd)
04.File list of current directory...................(ls)
05.Enter the specified directory..........(cd + dirname)
06.Return last directory.........................(cd ..)
07.Create a new directory..............(mkdir + dirname)
08.Delete the directory................(rmdir + dirname)
09.Create a new file....................(create + fname)
10.Open a file............................(open + fname)
11.Read the file...................................(cat)
12.Write the file....................(write + <content>)
13.Copy a file..............................(cp + fname)
14.Delete a file............................(rm + fname)
15.System information view........................(info)
16.Close the current user.......................(logout)
17.Change the current user...............(su + username)
18.Change the mode of a file.............(chmod + fname)
19.Change the user of a file.............(chown + fname)
20.Change the group of a file............(chgrp + fname)
21.Rename a file............................(mv + fname)
22.link.....................................(ln + fname)
23.Change password..............................(passwd)
24.User Management Menu..........................(Muser)
注：该代码中cat指令与write指令与要求中有所不同，需要先对文件执行open指令后才可以读写。
