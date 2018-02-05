# <center>github网页版pull request操作步骤</center>

# 一、Issue的创建和标记
1.点击【issues】，进入issue tab页，在issues列表中查看你想要处理的issue。这个issue可以是contributer或者committer创建，类型有需求/BUG/协作。
![image](https://github.com/maohuaming/Picture/blob/master/%E5%9B%BE%E7%89%871.jpg?raw=true)

**<center>图1 issues tab页</center>**

2.在issues列表中点击你想要处理的issue标题，进入issue详情页。
![image](https://images-cdn.shimo.im/YGmg2fl0jKcJhwkB/image.image/png!thumbnail)
**<center>图2 issue列表</center>**
![image](https://images-cdn.shimo.im/F4VIxx1WQC0AKNzV/image.image/png!thumbnail)
**<center>图3 issue详情页</center>**

3.committer将issue标记为ICP，申请处理或者开发issue，在issue的comment中提交留言，申请格式如下：@committer 申请开发 Size：xx Deadline：yyyy-mm-dd
![image](https://images-cdn.shimo.im/7Bdr6qVB50ooebB9/image.image/png!thumbnail)
**<center>图4 committer打ICP标签</center>**
![image](https://images-cdn.shimo.im/RsTSXkPXMWsjDCuh/image.image/png!thumbnail)
**<center>图5 打ICP标签后issue列表显示</center>**
![image](https://images-cdn.shimo.im/7pSLHKnOkjYO5C5I/image.image/png!thumbnail)
**<center>图6 打ICP标签后issue详情页显示</center>**
![image](https://images-cdn.shimo.im/Q8SVBuPZ99cpQtKh/image.image/png!thumbnail)
**<center>图7 申请者申请开发</center>**

4.Committer同意开发，指定assignee，标记size lable，打In progress标签。
![image](https://images-cdn.shimo.im/PO4HwbKatzcR3SPQ/image.image/png!thumbnail)
**<center>图8 committer同意开发发</center>**
![image](https://images-cdn.shimo.im/BuNxB8PvvuwNS4VI/image.image/png!thumbnail)
**<center>图9 committer指定assignee</center>**
![image](https://images-cdn.shimo.im/ae1ZKYTPfH04OTEm/image.image/png!thumbnail)
**<center>图10 committer打size lable和In progress标签</center>**

# 二、pull request

1.开发者完成代码编写或者文档编写工作后，在repository上新建对应分支，对应的分支应该按照 类型/开发者-目的 命名。可取的类型包括：bugfix(修复BUG) feature(功能特性开发) doc(文档工作)。例如，ben7th 修正图表显示不正确的 bug，可以表示为：bugfix/ben7th-chart-error
2.新建分支（branch）分三种情况。
第一种：在分支列表创建分支。点击code tab页标签，点击【branch】在下拉列表中的文本框里输入需要创建分支的名称。
![image](https://images-cdn.shimo.im/YPXoflWBfnsDQvff/image.blob!thumbnail)
**<center>图11 分支列表创建分支</center>**

创建好分支后，开发者向对应分支上传文件或者在分支上新建文件继而编辑内容。
![image](https://images-cdn.shimo.im/CzgU4AuxOWkKSqnh/image.blob!thumbnail)
**<center>图12 选择分支上传文件</center>**
![image](https://images-cdn.shimo.im/9vDWkAyoZC4U3O7F/image.blob!thumbnail)
**<center>图13 上传文件页面</center>**
![image](https://images-cdn.shimo.im/Xp77YWf4Ri0TUaeb/image.blob!thumbnail)
**<center>图14 在分支上新建文件</center>**
![image](https://images-cdn.shimo.im/BJUFr03Y2tw7Bf5Y/image.blob!thumbnail)
**<center>图15 新建文件详情</center>**

文件上传成功后，点击pull request标签页，创建pull request。pull request 包含的 commit 需要按照以下方式命名：
bug 修改类：fix #<issue 编号> , <描述信息>
开发工作类：for #<issue 编号> , <描述信息>
![image](https://images-cdn.shimo.im/VLGXk10lx6AfASZL/image.blob!thumbnail)
**<center>图16 创建pull request</center>**
![image](https://images-cdn.shimo.im/FPbUZ1UIIsAWT9BR/image.blob!thumbnail)
**<center>图17 创建pull request 详情页</center>**
![image](https://images-cdn.shimo.im/tRo4dbGyvL4xIcqY/image.blob!thumbnail)
**<center>图18 pull request包含的commit命名方式</center>**
第二种：create new file 方式。在任意分支页面点击【create new file】。
![image](https://images-cdn.shimo.im/EX7g4LlwZQI98dEk/image.blob!thumbnail)
**<center>图19 create new file</center>**
进入new file详情页面，输入文件标题，编辑文件内容，点选“Create a new branch for this commit and start a pull request. ”选项，点击【propose new file】。
![image](https://images-cdn.shimo.im/L5plSXkuk5AIzZVQ/image.blob!thumbnail)
**<center>图20 创建文件同时创建新分支</center>**
进入open a pull request 页面。
![image](https://images-cdn.shimo.im/jHhwJCptnqo9cuwY/image.blob!thumbnail)
**<center>图21 开始创建pull request页面</center>**
点击【create pull request】，即可在pull request 标签页看到新建的pull request。
![image](https://images-cdn.shimo.im/X99vc6J5G94Rb1zm/image.blob!thumbnail)
**<center>图22 pull request 自动生成</center>**
第三种：upload file方式，该方式的步骤与create new file相同，点击【upload file】时，同时创建分支。
结束
3.Pull request创建成功后，committer指定assignee，在pull request上打上ICP标签，确定review人员。
4.Review结束后pull request的assignee 进行merge操作，contributer/committer关闭issue。
![image](https://images-cdn.shimo.im/aGXMOfiWEt81Zepc/image.blob!thumbnail)
**<center>图23 assignee进行merge操作</center>**
# 三、基础

1.启动浏览器，打开gitthub官网（https://github.com/），进入github主页。
![image](https://images-cdn.shimo.im/SPAV4Sao00c7eOzM/image.blob!thumbnail)
**<center>图24  github首页</center>**
如果没有账号就在页面注册，具体注册流程略过。如果有账号，则点击【sign in】进入登录页面。
![image](https://images-cdn.shimo.im/4rg2JHUsF8IZ2jQ4/image.blob!thumbnail)
**<center>图25 github登录页面</center>**

2.登录github后，进入首页，首页如下图所示：
![image](https://images-cdn.shimo.im/fYfUkmdSiH8HsWVF/image.blob!thumbnail)
**<center>图26 github登录后首页</center>**
3.在Your repositories 列表中选择相关的repository点击进入。如果没有repository，则参考github文档创建一个。
![image](https://images-cdn.shimo.im/IQr21Nn08UAFngt7/image.blob!thumbnail)
**<center>图27 选择repository</center>**
Repository页面如图29所示：
![image](https://images-cdn.shimo.im/tHHG4vld9MAUH0sc/image.blob!thumbnail)
**<center>图28 repository页面</center>**
4.进入repository后，点击code标签页，创建develop分支。具体步骤和方法可参见github文档。
![image](https://images-cdn.shimo.im/ZolxeGX8wPESfmXF/image.blob!thumbnail)
**<center>图29 code tab页</center>**
