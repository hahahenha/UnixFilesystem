浙江工业大学操作系统大型实验————模拟Unix文件系统
<p>Zhejiang University of Technology, Simple Unix File System</p>
<p>-----------------------------------------------------------</p>
<p>实现功能</p>
<p>01.Exit system....................................(exit)</p>
<p>02.Show help information..........................(help)</p>
<p>03.Show current directory..........................(pwd)</p>
<p>04.File list of current directory...................(ls)</p>
<p>05.Enter the specified directory..........(cd + dirname)</p>
<p>06.Return last directory.........................(cd ..)</p>
<p>07.Create a new directory..............(mkdir + dirname)</p>
<p>08.Delete the directory................(rmdir + dirname)</p>
<p>09.Create a new file....................(create + fname)</p>
<p>10.Open a file............................(open + fname)</p>
<p>11.Read the file...................................(cat)</p>
<p>12.Write the file.....................(write + contents)</p>
<p>13.Copy a file..............................(cp + fname)</p>
<p>14.Delete a file............................(rm + fname)</p>
<p>15.System information view........................(info)</p>
<p>16.Close the current user.......................(logout)</p>
<p>17.Change the current user...............(su + username)</p>
<p>18.Change the mode of a file.............(chmod + fname)</p>
<p>19.Change the user of a file.............(chown + fname)</p>
<p>20.Change the group of a file............(chgrp + fname)</p>
<p>21.Rename a file............................(mv + fname)</p>
<p>22.link.....................................(ln + fname)</p>
<p>23.Change password..............................(passwd)</p>
<p>24.User Management Menu..........................(Muser)</p>
<p>注：该代码中cat指令与write指令与要求中有所不同，需要先对文件执行open指令后才可以读写。</p>
