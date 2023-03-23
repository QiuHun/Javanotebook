```java
Scanner sc = new Scanner(System.in);
int a = sc.nextInt();
switch(a){
    case 1:
        // a=1执行
        // break，结束switch语句，如果不结束将会执行case到底
    case 2:
        // a=2执行
    default:
        // 上述值都不满足时执行
}
sc.close();
```

判断条件不能是关系表达式、逻辑表达式或浮点类型