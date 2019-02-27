# ubuntu安装显卡驱动的方法
1. ctrl+alt+T 打开终端
2. sudo apt-get purge nvidia* 删除旧的驱动

  //

3. 下载 cuda 版本
   (cuda 安装 sudo qpt-get install cuda)
4. nvidia-smi 查看驱动是否安装成功
5. ls 显示目录、文件
6. cd 到 cuda 文件
7. ls 显示目录、文件
8. sudo ./cuda_... 安装驱动
9. nvidia-smi 查看是否安装成功
10. restart 重启电脑
