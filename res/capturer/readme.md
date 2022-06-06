# 地图图片自动抓取合成工具
本工具使用autoit脚本编写，专门抓取各种地图网页服务的图，所见即所得，只要支持鼠标拖动即可。
首先下载[MapCapturer.zip](MapCapturer.zip)并解压，解压后目录如图： 

![1](https://user-images.githubusercontent.com/4956469/172093174-5f895968-becc-4bb1-b1e5-5a50bdb54bae.png)

运行浏览器打开想要抓取图片的网页： 

![2](https://user-images.githubusercontent.com/4956469/172093179-32377090-6583-41dc-bd29-fba99fed2e54.jpg)

然后运行Capturer目录中的FSCapture.exe，找到它的设置页如图设置： 

![3](https://user-images.githubusercontent.com/4956469/172093183-534d4d2c-bcf9-4fd7-9406-c2b5bf51ef16.png)

再在FSCapture的主界面上设置成To File（Auto Save）如下图： 

![4](https://user-images.githubusercontent.com/4956469/172093187-b29120d4-cd12-42a9-b618-2f400527a992.png)

运行Capturer目录中的Capturer2.exe，选择要抓取的行列数和每次抓取的大小，第一次可以保持默认为了后面描述方便： 

![5](https://user-images.githubusercontent.com/4956469/172093190-ead783c7-aa5f-4206-868e-8e9747ebfcb6.png)

抓完后的图像会自动保存在Images目录中： 

![6](https://user-images.githubusercontent.com/4956469/172093192-11b6dc63-5f86-487e-9a93-02673b6aee79.png)

要合并成一张大图要打开LargeMontage_v1.08_bundle目录中的run.bat，出现ImageJ的界面： 

![7](https://user-images.githubusercontent.com/4956469/172093197-976bf50f-a716-4079-a08a-e7a812c4c91e.png)

然后选择菜单Plugins->LargeMontage，在弹出的对话框Specify base image file中选Images目录里的00000001.jpg，在Output file对话框中设置保存为montage.tif，如图： 

![8](https://user-images.githubusercontent.com/4956469/172093200-1cac7cd3-69cc-4c62-8770-e23d05eb6903.png)

然后在接下来弹出的设置选项里如下设置： 

![9](https://user-images.githubusercontent.com/4956469/172093204-89090261-5a3f-4468-a9f9-95153cd18abd.png)

点OK，等合并结束后关闭程序，这就是合并后的图像： 

![10](https://user-images.githubusercontent.com/4956469/172093208-ed3ab139-1eb5-40cd-95bd-f17847bc2fdd.jpg)

导入到[MicroCity](https://github.com/microcity/microcity.github.io/releases/latest)中进行进一步处理：

![屏幕截图 2022-06-06 122932](https://user-images.githubusercontent.com/4956469/172095135-087ff1fe-8034-4094-a426-012919a6d43c.png)

