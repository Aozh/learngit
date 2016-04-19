##git上传过程中问题
在本地仓库提交过程中出现**nothing added to commit but untracked file**未监视问题，说明没有提交成功，一定要init，然后重新add文件，要在正确的仓库下add才能提交成功。
或者遇到`src refspec master does not match any`问题，说明本地版本库为空，空目录不能提交，即add和commit没成功。参考`http://www.tuicool.com/articles/QFFZze`
提交文件简易命令过程参考http://blog.csdn.net/qyf_5445/article/details/8737913