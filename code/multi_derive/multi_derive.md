## 多继承结论

#### 基类不带虚函数
不生成虚函数表，数据成员即是整个类的内存空间

#### 基类带虚函数
生成虚函数表，虚函数表本质是一个指针(指针占内存大小与编译器相关)。通过比较两个.cpp文件可以得出他的的区别

![菱形继承的内存结构](../../resource/菱形继承内存结构.001.jpeg)