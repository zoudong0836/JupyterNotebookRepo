# [GIT中文乱码解决方案](https://www.cnblogs.com/30go/p/8643459.html)


解决方案：

在bash提示符下输入： 
```sh
git config --global core.quotepath false
```

core.quotepath设为false的话，就不会对0x80以上的字符进行quote。中文显示正常。 
