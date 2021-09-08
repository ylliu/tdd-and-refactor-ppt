重构课程参考资料记录

01.code smells

迪米特法则定义了获取资源的方式，解决message Chain的问题，

纯数据类，出现纯数据类，一个考虑依恋情结，一个考虑把数据合并到其他类中

switch 用多太替代

过度设计

临时字段 

被拒绝的馈赠

non-localized plans 这个是什么意思

改一个地方需要改很多地方

把改动都放到一起

02.introduction refactoring

3个原则

面向接口而不是实现

组合优于继承

封装变化



被拒绝的馈赠需要再看下

https://zhuanlan.zhihu.com/p/98756702

![image-20210827112709977](C:\Users\youlong\AppData\Roaming\Typora\typora-user-images\image-20210827112709977.png)



重构的过程提到OO原则，然后再适当的导入设计模式，这就比较妙了

replace temp with query 

这样做有什么好处

double basePrice = _quantity * _itemPrice; 

double basePrice(){ 

 return _quantity * _itemPrice; 

}

03 

replace error code with exception code

05 extact interface 

这部分的重构还是没有太理解



