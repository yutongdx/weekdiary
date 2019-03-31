# 周记
  苦逼的一周，因为牙痛，寝食难安，看不下书。
## 概况
  主要看了对象和类，还有部分继承的内容。周五晚初步接触了一下下线程和网络套接字的相关内容。
## 学习笔记
1. 重载
    在一个类里面，方法名字相同，而**参数不同**。返回类型**可以相同也可以不同**。
2. 构造器
    如果在类中有自定义的构造器，最好确保有**无参数**的构造器；在构造器中把this()放在第一行可以调用同一个类的另一个构造器。
3. 将类放入包中
``` java
package com.yutong.www.po;
```
相当于把user的类文件等按照以下路径存放：
    ├com/
     ├yutong/
         ├www
           ├po
             ├user.java
             ├user.class
其它文件夹中的类要用到时，在顶头加上：
```java
import com.yutong.www.po.*;
```
4. 继承
用static定义静态方法，可以在其它类中不需要通过对象就可以直接使用该方法，调用时用`User.test();`
```java
public class User {
	public static void test(){}
}
```
用final定义类或方法会使类不可被继承或方法不可被子类覆盖
```java
public final class User {
	public final void test(){}
}
```
5. 数据结构--栈
    数据后进先出，操作限于栈顶，顺序栈类似于数组，受限于要预设大小；链栈类似于链表，不需预设大小。

