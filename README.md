实现了一个类似“硬盘文件搜索软件——Everything”功能的程序。
程序是字符界面的，因为仅仅是为了学习。
程序实现了如下功能：
* 能够在很短的时间内扫描你指定分区上的所有文件并把文件信息存储在内存数据库中。
* 根据文件名搜索文件，速度很快。
* 可以监视一个已经扫描过的分区，该分区上所有文件的创建、删除、改名操作都可以被瞬间感知并更新到内存数据库。

程序没有的功能：
* 程序每次打开都要重新扫描磁盘，因为程序是用来演示的，程序关闭后没有保存上次扫描后的结果。
* 尚未测试过对文件夹的监视
* 和Everything一样，本程序不能搜索文件的内容
