# ORB-SLAM2
## 20240118
1. 修改原版的一些小问题->成功编译
2. orb2需要的是pangonlin-0.5
   · 源码安装
   2. mkdir install
   3. mkdir build
   4. cd build
   5. cmake -DCMAKE_INSTALL_PREFIX=../install # 相对路径不知道可不可以
   6. make -j4
   7. make install # 在install文件夹可以看到安装文件

