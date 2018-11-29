解决wps for linux 启动缺少字体问题。
目前WPS for Linux公式显示需要相应的Symbol字体（比如symbol, windings, mt extra等）， 由于版权原因，WPS for Linux未对此类字体打包安装。

步骤：
下载字体并复制到字体路径下。

字体路径：
root@ubuntu:~#  cd /usr/share/fonts

安装字体：
root@ubuntu:/usr/share/fonts# mkfontscale
root@ubuntu:/usr/share/fonts# mkfontdir
root@ubuntu:/usr/share/fonts# fc-cache

重启wps即可。
