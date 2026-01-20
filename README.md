# 使用conda配置cs231n环境

此文档作为 [@weijianxian](https://github.com/weijianxian/cs231n-25) 的补充，原文只提供了使用python的uv虚拟环境配置，但是conda作为配置工具比python原生更为优秀，因此在此补充使用conda配置cs231n环境。

1. 首先我们去官网下载安装conda，[官网地址](https://www.anaconda.com/docs/getting-started/main)
2. 如果有需要，使用以下命令更新conda
   ```
   conda update conda
   ```
3. 之后我们便可以使用以下命令创建一个名为cs231n的虚拟环境
   ```
   conda create -n cs231n -f requirements.txt
   ```
4. 使用以下命令激活虚拟环境
   ```
   conda activate cs231n
   ```
5. 使用以下命令退出虚拟环境
   ```
   conda deactivate
   ```

PS：conda的虚拟环境是储存在你的conda安装目录下的envs文件夹中的，因此我们只需要在需要使用虚拟环境时激活即可，不需要考虑我们的虚拟环境文件存放问题。
