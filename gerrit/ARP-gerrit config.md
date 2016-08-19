==**Steps to be mentioned during code review in arp**==
## 1.Create Account
- Check your user name and email by “git config –list” 
![](https://raw.githubusercontent.com/rahxphoon/youdao/master/gerrit/eses.png)
- I will collect all your data and create account for you;
## 2.Update your info and active e-mail
- Login http://zhairis4-w7/
- Register your gerrit account and Update your account info
![image](https://raw.githubusercontent.com/rahxphoon/youdao/master/gerrit/%E6%90%9C%E7%8B%97%E6%88%AA%E5%9B%BE20160811151640.png)
- Click the whole link to active e-mail
![image](https://raw.githubusercontent.com/rahxphoon/youdao/master/gerrit/%E6%90%9C%E7%8B%97%E6%88%AA%E5%9B%BE20160811152009.png)
## 3.Generate ssh key and upload to gerrit webpage
- If you have not generate ssh key, type in below command 
     >ssh-keygen -t dsa -b 1024

  It will appear in c:\users\yourdomain\\.ssh file
![image](https://raw.githubusercontent.com/rahxphoon/youdao/master/gerrit/%E6%90%9C%E7%8B%97%E6%88%AA%E5%9B%BE20160811152134.png)

- Open id_rsa.pub file and copy file content to gerrit SSH public Keys setting
![image](https://raw.githubusercontent.com/rahxphoon/youdao/master/gerrit/%E6%90%9C%E7%8B%97%E6%88%AA%E5%9B%BE20160811152159.png)
## 4.Clone project from:
>ssh://username@zhairis4-w7:29418/iris4_arp.git

After you commit file change and then in the push menu,always add refs/for prefix to push your code into gerrit server first
![image](https://raw.githubusercontent.com/rahxphoon/youdao/master/gerrit/%E6%90%9C%E7%8B%97%E6%88%AA%E5%9B%BE20160811164212.png)

Then code viewer login   [ gerrit web page](http://zhairis4-w7/) see the code to be reviewed

![image](https://raw.githubusercontent.com/rahxphoon/youdao/master/gerrit/%E6%90%9C%E7%8B%97%E6%88%AA%E5%9B%BE20160811164304.png)

click ID and see the change result, if it is OK for you ,just click review and add +2 or +1 to approve this update
![image](https://raw.githubusercontent.com/rahxphoon/youdao/master/gerrit/%E6%90%9C%E7%8B%97%E6%88%AA%E5%9B%BE20160811164552.png)
Compare results
![image](https://raw.githubusercontent.com/rahxphoon/youdao/master/gerrit/%E6%90%9C%E7%8B%97%E6%88%AA%E5%9B%BE20160811164537.png)

