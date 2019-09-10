# 问题
   set(CMAKE_CXX_COMPILER g++) 显示找不到g++
# 解决
   set(CMAKE_CXX_COMPILER /usr/bin/g++) 会导致循环cmake
   
   set(CMAKE_CXX_COMPILER /usr/bin/c++) 解决问题
# 原因
   懵逼
