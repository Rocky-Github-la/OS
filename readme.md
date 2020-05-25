﻿在正文定稿后补充的注意事项


  从光盘将文件直接复制到硬盘的话，所有的文件都会带上“只读”属性，
笔者完全忘记这么一码事了，因此在正文中没有提醒大家注意这一点。

  如果文件带着只读属性，就无法对该文件进行编辑和覆盖操作。也就是说，
没办法对程序代码进行修改了。

  要去掉只读属性，需要将文件从光盘复制到硬盘之后，打开文件的属性对话框，
将“只读”一栏的勾去掉，然后点击“确定”。

  在Windows2000及以上版本中，去掉只读属性点击确定按钮之后，系统会询问
这一更改是仅应用于当前文件夹还是应用于当前文件夹内包括子文件夹中的所有文件。
使用这一功能，就可以将整个文件夹，例如harib00a中所有的文件一次性去掉只读属性。
Windows中还有很多方便的功能，由于时间问题，笔者这里就不一一讲解了，大家自行研究哈。



  在tolset中包含的QEMU貌似在Windows2000以上版本的系统中无法工作，抱歉。

  后来笔者寻找了一下更古老的QEMU版本，发现了一个可以在Windows95下运行的版本。
想使用这个老版本的话，可以将tolset/z_tools/中的qemu文件夹改名为qemu_nt，然后
再将qemu_9x改名为qemu即可。

  这个老版本的qemu虽然貌似可以在Windows2000以上版本系统中运行，不过一部分
操作方法和正文中的讲解有区别，例如将鼠标从QEMU释放的操作，不是Ctrl+Alt，
而是变成了Shift+Ctrl。

  另外，在某些环境中，这个老版本的QEMU貌似会发生颜色不正确等异常情况。不过
这也比完全不能运行要好多了，大家请根据情况使用吧。

注：作为一个开源项目，QEMU至今为止一直在持续更新和发布新版本，大家可以从 [http://qemu.org](http://qemu.org) 这个网站获得并尝试最新的Windows编译版本。


