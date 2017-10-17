# OOP

面向对象编程（OOP\)是我们编程的一项基本技能，PHP5对OOP提供了良好的支持。如何使用OOP的思想来进行PHP的高级编程，对于提高PHP编程能力和规划好Web开发构架都是非常有意义的。下面我们就通过实例来说明使用PHP的OOP进行编程的实际意义和应用方法。

我们通常在做一个有数据库后台的网站的时候，都会考虑到程序需要适用于不同的应用环境。和其他编程语言有所不同的是，在PHP中，操作数据库的是一系列的具体功能函数（如果你不使用ODBC接口的话）。这样做虽然效率很高，但是封装却不够。如果有一个统一的数据库接口，那么我们就可以不对程序做任何修改而适用于多种数据库，从而使程序的移植性和跨平台能力都大大提高。

[01.什么是面向对象？](https://github.com/yafangmaster/OOP/blob/master/01.什么是面向对象？.md)

[02.什么是类，什么是对象，类和对象之间的关系](https://github.com/yafangmaster/OOP/blob/master/02.%E4%BB%80%E4%B9%88%E6%98%AF%E7%B1%BB%EF%BC%8C%E4%BB%80%E4%B9%88%E6%98%AF%E5%AF%B9%E8%B1%A1%EF%BC%8C%E7%B1%BB%E5%92%8C%E5%AF%B9%E8%B1%A1%E4%B9%8B%E9%97%B4%E7%9A%84%E5%85%B3%E7%B3%BB.md)

[03.什么是面向对象编程呢？](https://github.com/yafangmaster/OOP/blob/master/03.%E4%BB%80%E4%B9%88%E6%98%AF%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E7%BC%96%E7%A8%8B%E5%91%A2%EF%BC%9F.md)

[04.如何抽象出一个类？](https://github.com/yafangmaster/OOP/blob/master/04.%E5%A6%82%E4%BD%95%E6%8A%BD%E8%B1%A1%E5%87%BA%E4%B8%80%E4%B8%AA%E7%B1%BB%EF%BC%9F.md)

[05.如何实例化对象？](https://github.com/yafangmaster/OOP/blob/master/05.%E5%A6%82%E4%BD%95%E5%AE%9E%E4%BE%8B%E5%8C%96%E5%AF%B9%E8%B1%A1%EF%BC%9F.md)

[06.如何去使用对象中的成员](https://github.com/yafangmaster/OOP/blob/master/06.%E5%A6%82%E4%BD%95%E5%8E%BB%E4%BD%BF%E7%94%A8%E5%AF%B9%E8%B1%A1%E4%B8%AD%E7%9A%84%E6%88%90%E5%91%98.md)

[07.特殊的引用”$this“的使用](https://github.com/yafangmaster/OOP/blob/master/07.%E7%89%B9%E6%AE%8A%E7%9A%84%E5%BC%95%E7%94%A8%E2%80%9D%24this%E2%80%9C%E7%9A%84%E4%BD%BF%E7%94%A8.md)

[08.构造方法\_\_construct\(\)与析构方法\_\_destruct\(\)](https://github.com/yafangmaster/OOP/blob/master/08.%E6%9E%84%E9%80%A0%E6%96%B9%E6%B3%95__construct%28%29%E4%B8%8E%E6%9E%90%E6%9E%84%E6%96%B9%E6%B3%95__destruct%28%29.md)

[09.封装性（var与public，protected，private的关系）](https://github.com/yafangmaster/OOP/blob/master/09.%E5%B0%81%E8%A3%85%E6%80%A7%EF%BC%88var%E4%B8%8Epublic%EF%BC%8Cprotected%EF%BC%8Cprivate%E7%9A%84%E5%85%B3%E7%B3%BB%EF%BC%89.md)

[10.\_\_set\(\)，\_\_get\(\)，\_\_isset\(\)，\_\_unset\(\)四个方法的应用](https://github.com/yafangmaster/OOP/blob/master/10.__set%28%29%EF%BC%8C__get%28%29%EF%BC%8C__isset%28%29%EF%BC%8C__unset%28%29%E5%9B%9B%E4%B8%AA%E6%96%B9%E6%B3%95%E7%9A%84%E5%BA%94%E7%94%A8.md)

[11.类的继承](https://github.com/yafangmaster/OOP/blob/master/11.%E7%B1%BB%E7%9A%84%E7%BB%A7%E6%89%BF.md)

[12.重载新的方法（parent::）](https://github.com/yafangmaster/OOP/blob/master/12.%E9%87%8D%E8%BD%BD%E6%96%B0%E7%9A%84%E6%96%B9%E6%B3%95%EF%BC%88parent::%EF%BC%89.md)

[13.访问类型（public，protected，private）](https://github.com/yafangmaster/OOP/blob/master/13.%E8%AE%BF%E9%97%AE%E7%B1%BB%E5%9E%8B%EF%BC%88public%EF%BC%8Cprotected%EF%BC%8Cprivate%EF%BC%89.md)

[14.final关键字的应用](https://github.com/yafangmaster/OOP/blob/master/14.final%E5%85%B3%E9%94%AE%E5%AD%97%E7%9A%84%E5%BA%94%E7%94%A8.md)

[15.static和const关键字的使用（self::）](https://github.com/yafangmaster/OOP/blob/master/15.static%E5%92%8Cconst%E5%85%B3%E9%94%AE%E5%AD%97%E7%9A%84%E4%BD%BF%E7%94%A8%EF%BC%88self::%EF%BC%89.md)

[16.\_\_toString\(\)方法](https://github.com/yafangmaster/OOP/blob/master/16.__toString%28%29%E6%96%B9%E6%B3%95.md)

[17.克隆对象\_\_clone\(\)方法](https://github.com/yafangmaster/OOP/blob/master/17.%E5%85%8B%E9%9A%86%E5%AF%B9%E8%B1%A1__clone%28%29%E6%96%B9%E6%B3%95.md)

[18.\_\_call\(\)处理调用错误](https://github.com/yafangmaster/OOP/blob/master/18.__call%28%29%E5%A4%84%E7%90%86%E8%B0%83%E7%94%A8%E9%94%99%E8%AF%AF.md)

[19.抽象方法和抽象类（abstract）](https://github.com/yafangmaster/OOP/blob/master/19.%E6%8A%BD%E8%B1%A1%E6%96%B9%E6%B3%95%E5%92%8C%E6%8A%BD%E8%B1%A1%E7%B1%BB%EF%BC%88abstract%EF%BC%89.md)

[20.PHP5接口技术\(interface\)](https://github.com/yafangmaster/OOP/blob/master/20.PHP5%E6%8E%A5%E5%8F%A3%E6%8A%80%E6%9C%AF%28interface%29.md)

[21.多态的应用](https://github.com/yafangmaster/OOP/blob/master/21.%E5%A4%9A%E6%80%81%E7%9A%84%E5%BA%94%E7%94%A8.md)

[22.把对象串行化serialize\(\)方法，\_\_sleep\(\)方法，\_\_wakeup\(\)方法](https://github.com/yafangmaster/OOP/blob/master/22.%E6%8A%8A%E5%AF%B9%E8%B1%A1%E4%B8%B2%E8%A1%8C%E5%8C%96serialize%28%29%E6%96%B9%E6%B3%95%EF%BC%8C__sleep%28%29%E6%96%B9%E6%B3%95%EF%BC%8C__wakeup%28%29%E6%96%B9%E6%B3%95.md)

[23.自动加载类 \_\_autoload\(\)函数](https://github.com/yafangmaster/OOP/blob/master/23.%E8%87%AA%E5%8A%A8%E5%8A%A0%E8%BD%BD%E7%B1%BB%20__autoload%28%29%E5%87%BD%E6%95%B0.md)

