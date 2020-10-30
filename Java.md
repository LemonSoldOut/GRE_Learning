# Java 学习

**圣经：Algorithms + Data Structure = Program**

 ## Computer Basic Info:电脑基础知识
 ### 1. 软件
 * 	写好的代码可以通过打个jar包用EXE生成器的办法将jar包变成可运行的EXE程序（没有运行环境需要自己添加）
 * 	各种软件，QQ，Wechat等。
 * 	我想做贪吃蛇，五子棋啥的感觉看得人多点![img](file:///C:\Users\Cheng\AppData\Local\Temp\SGPicFaceTpBq\10792\00814979.png)
### 2. 硬件
 * 	摸得到的电脑零件
 * 	身为程序员不会修电脑真的不尴尬
### 3. 操作系统
* 三大操作系统OS Operating System：Mac, Win, Linux(基于收费Unix）
* Linux拥有各种开源版本：Kali，Manjaro， RedHat， Arch， Ubuntu 等等。
1. GUI 图形界面化 Graphical User Interface: 
* Win/Mac； 
* Linux两者都有。
 *		使用Eclipse， Idea等IDE来进行代码编写和运行
 *		鼠标操作
2. CLI 命令行界面 Command Line Interface: 
Linux运维
 * 键盘操作，没有图形界面，文件位置如树一般
   		 DOS/Terminal
      root/    

   C://

 * cd, ls, ifconfig, ip, ping www.baidu.com, touch, start, vi/vim, mkdir, clear/cls, exit, shutdown -s -t 0/reboot, sudo -i 等等

 * javac

 * gcc

 * makefile

 * python 等。

#### DOS/Terminal一些基本的常识和命令的使用

##### Win-DOS

1. 改变当前路径
2. 

##### Linux/Unix-Terminal

### 4. 语言（指令）

 * 0和1 

   ​	 2进制， 8进制，10进制， 16进制（互相转换）

 * 汇编

	要学习的小伙伴要失望了 这个我不熟 嘻嘻

 * 面向过程：C， Fortran， Pascal等

 * 面向对象： Java

 * C++两者都有

 * 插播一条广告：Python 天下第一好学。 一学就会，一用就爽。但是我选择Java（hia hia hia~)

## Java基本知识

### Java历史与发展

这里不做啥介绍了，没兴趣的也略过不看的，有兴趣自然会去搜索。

### Java特点：（Java核心技术XI）

1. 面向对象
2. 健壮性
3. 跨平台性
4. ...

### JavaSE/EE/ME的区别

1. JavaSE： Java Standard Edition（标准版）

   Java API：个人开发

2. JavaEE： Java Enterprise Edition（企业版）

   Servlet， Jsp：Web开发

3. JavaME： Java Micro Edition（小型版）

   减少API，加入移动端的支持

### JVM,JDK,JRE的了解与各自之间的关系

#### Java虚拟机（Java Virtual Machine，JVM）

* 虚拟机（Virtual Machine，VM）：装过双系统的应该懂。

  1. 不懂的就当做是把你电脑带来带去，不管是学校，家里，公司，有网就能做事情，而且是自己的电脑，一模一样的，不会出现不兼容的问题。
  2. 包括把你电脑给别人使用，和你操作方法一样肯定可以和你一样做相同的事情不会报错。

* 只要安装了JVM：一处编译处处运行的效果就体现出来了

#### Java开发工具包（Java Development Kit，JDK）

 * JDK选择：Java8（或叫Java1.8）稳定且够用了 

 * 之后的版本也就加入了一些新版本特性，可以自行取舍。

 * JDK = JRE + 开发工具包（javac编译运行， jar打包）

#### Java运行环境（Java Runtime Environment，JRE）

 * JRE = JVM + Java SE标准类库     System.out.println();

 * 

----
 ## 代码

简单到令人发指的教学正式开始。

 ### 1. HelloWorld

分析：

```java
 public class Demo {
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("Hello World!");		
	}
}
```