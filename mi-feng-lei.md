用来表示受限的类继承结构：当一个值为有限集中的类型，而不能有其他类型时。用关键字**sealed**声明

* 密封类自身是抽象的
* 构造函数都是**private**
* 直接子类必须同密封类在同一文件内
* 子类的继承者（间接子类）可以在任意位置

密封类主要用于**when**表达式


