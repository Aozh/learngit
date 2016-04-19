##git上传过程中问题
在本地仓库提交过程中出现**nothing added to commit but untracked file**未监视问题，说明没有提交成功，一定要init，然后重新add文件，要在正确的仓库下add才能提交成功。
或者遇到`src refspec master does not match any`问题，说明本地版本库为空，空目录不能提交，即add和commit没成功。参考`http://www.tuicool.com/articles/QFFZze`
提交文件简易命令过程参考http://blog.csdn.net/qyf_5445/article/details/8737913
遇到问题failed to push some refs to git
主要原因从别的本地库上传到git库中，比如缺少了readme.txt文件，解决方法git pull --rebase origin master合并代码，使git库中的文件复制到上传文件的本地库中。参考
http://jingyan.baidu.com/article/f3e34a12a25bc8f5ea65354a.html?st=2&net_type=&bd_page_type=1&os=0&rst=&word=chegji@gmail.com