# 使用conda配置cs231n环境

此文档作为 [@weijianxian](https://github.com/weijianxian/cs231n-25) 的补充，原文只提供了使用python的uv和venv的虚拟环境配置，但是conda依然是一个主流配置工具，因此在此补充使用conda配置cs231n环境。

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

另外，仓库中的 requirements.txt 文件我无法保证包含所有需要的库，在a3中官方为你提供了一个requirements.txt文件，但是仍然不清楚是否可以兼容a1和a2，并且cs231n纯粹只考虑了Linux环境，我仍然无法保证a3给的环境文件可以在windows环境下运行，所以请关注[@weijianxian](https://github.com/weijianxian/cs231n-25)的仓库更新，想用conda只需要了解上述命令即可。
