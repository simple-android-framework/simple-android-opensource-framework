# 编码规范

为了保持大家的代码一致性，进行一些代码格式的规范。

* 代码缩进使用4个空格，不是Tab键。
* 统一使用UTF-8编码，避免乱码问题。
* 类的命名规范： 如果是Android SDK提供的Android应用组成部分，那么类名应该是类的作用的英文全称或者缩写＋ Android SDK基类的名字。

例子： 
Activity类名字应该是 类似 MainActivity, NaviActivity （Navigation， 导航缩写Navi）, TextActivity, BookActivity

Service类名字缩写应该是类似 DownloadService,
每个类完成后应该有作者姓名和联系方式的注释，对自己的代码负责。如

```
/**
 * 类的介绍
 */
public class DataBack {
        // ...
}
``` 

* 变量命名
变量的命名均要能够代表它的意义，即命名的字解释性。看如下示例: 

public变量的以小写字母开头，例如: 
```
public String userName ;
```   
其他访问权限的变量的格式为 : m+能够代表变量意义的字母, 例如 : 
```
private String mUserName ;
```   

* 函数命名
函数的命名均要能够代表它的意义，即命名的字解释性。例如 : 

```
public void saveUserInfoToDB(User user) {
	// code 
}
```   
上面的函数一看基本上知道是保存用户信息到数据库中,即命名的字解释性。   

* 大括号的排列
在java中两个大括号的正确格式如下 :   

```
if ( condition ) {
	// code 
} else if ( condition ) {
	// 
}

```   
即两个括号并不对齐排列。

* 空格问题
在条件判断、操作数、操作符之间都要添加空格，使得语句更为清晰。例如 :   

```
int result = 10 + 23 - 100 / 4 ;

```    
错误的形式为 : 

```
int result=10+23-100/4 ;

```    

* 空行问题
在函数之间需要添加一个空行，例如: 

```

private void setUserName(String aName) {
	// 
}

private void setUserAge(int aAge) {
	// 
}
```

* 注释 
在类、函数、变量前面尽量加上相关的注释，当然如果你觉得你的命名具有足够的自解释性那可以免掉一些注释。但是建议在类的开头、重要的函数之前写一些介绍性、原理性注释。