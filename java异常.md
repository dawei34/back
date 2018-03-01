##### 空指针
1. equals相关
```
String s = null;
System.out.println(s.equals("ABCD"));   //Exception in thread "main" java.lang.NullPointerException

String s = null;
System.out.println(s.equals("ABCD"));    //false
```
