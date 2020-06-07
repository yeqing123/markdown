# 链接

## 内嵌式链接Demo
- ### 链接仓库内的其他文件：[demo1](demo1.md)
- ### 链接文档内的其他部分：[代码块](demo2.md#代码块)

## 外部链接Demo
[百度](https://www.baidu.com)

## 引用链接Demo
- [百度百度][baidu]  
- [baidu]
- [demo1]
# 图片

## 外部图片Demo:
![baidu](https://www.baidu.com/img/PCtm_d9c8750bed0b3c7d089fa7d55720d6cf.png "百度图片")

## 项目内部图片Demo:
![Kung Fu panda](images/panda.jpg "功夫熊猫")

## 引用图片Demo
### 外部图片的引用式插入
- ![][baidu_logo]

### 内部图片的引用式插入
- ![kung fu panda][Kung Fu panda]
# 代码块

## 行内代码Demo
定义了一个javascript变量 `var a = 10`  并且调用了方法 `console.log(a)` 来显示该变量。

## 块式代码Demo
```javascript
var a = 10;
console.log(a);
```

### 块式代码的另一种写法(但是这种方法无法实现语法高亮)
    var a = 10;
    console.log(a);


## 引用
### 单层引用
> 只要功夫深，铁杵磨成针！！

### 多重引用
>>> 兴趣是最好的老师！！

<!-- 定义链接引用 -->
[baidu]:https://www.baidu.com
[demo1]:demo1.md

<!-- 定义图片引用 -->
[baidu_logo]: https://www.baidu.com/img/PCtm_d9c8750bed0b3c7d089fa7d55720d6cf.png "百度logo"
[Kung Fu panda]:images/panda.jpg "功夫熊猫"