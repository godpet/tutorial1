## Linux网络编程基础API

### 5.1 socket地址API

#### 代码清单5-1 判断机器字节序

#include <stdio.h>

void byteorder(){
  union{
    
