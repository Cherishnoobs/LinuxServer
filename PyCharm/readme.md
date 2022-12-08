# PyCharm Remote 配置



1. 使用ssh工具登录远程服务器

   ```shell
   ssh -p 2022 CrossAI@210.30.97.170
   ```

   ![image-20221208154304224](imgs/01.png)

2. 创建虚拟环境

   ```shell
   conda create -n name python=3.7
   ```

3. 点右下角，添加解释器

   ![image-20221208155120282](imgs/02.png)

4. 连接服务器

   <img src="imgs/03.png" alt="image-20221208155252777" style="zoom:50%;" />

   <img src="imgs/04.png" alt="image-20221208155405990" style="zoom:50%;" />

   <img src="imgs/05.png" alt="image-20221208155428535" style="zoom:50%;" />

   <img src="imgs/06.png" alt="image-20221208160001651" style="zoom:50%;" />

   <img src="imgs/07.png" alt="image-20221208160813638" style="zoom:50%;" />

5. sftp上传/下载文件，可以开启自动上传，也可以使用上边选项手动上传。

   ![image-20221208161505854](imgs/08.png)

   

   打开远程文件夹可以看到文件已上传。

   

   ![image-20221208161704936](imgs/09.png)

6. 可以在这里设置我们的运行参数

   <img src="imgs/10.png" alt="image-20221208161850334" style="zoom:50%;" />

   <img src="imgs/11.png" alt="image-20221208161952873" style="zoom:50%;" />

   <img src="imgs/12.png" alt="image-20221208162605093" style="zoom:50%;" />

   <img src="imgs/13.png" alt="image-20221208162722736" style="zoom:50%;" />

7. 可以打断点进行调试了

8. 终端连接到远程

   <img src="imgs/14.png" alt="image-20221208162858310" style="zoom:50%;" />

   <img src="imgs/15.png" alt="image-20221208162953115" style="zoom:50%;" />