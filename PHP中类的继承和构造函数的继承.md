**PHP4.x 版本：**

PHP 4.x 的构造函数名与类名相同。

在子类里父类的构造函数不会自动执行。

要在子类里执行父类的构造函数，必须执行类似以下语句：

```php
$this->[父类的构造函数名()]
```

例如：

```php
<?php
class base1 {
   function base1() {
       echo 'this is base1 construct';
   }
}
 
class class1 extends base1 {
   function class1() {
       $this -> base1();
       echo 'this is class1 construct';
   }
}
$c1 = new class1;
```

**PHP5.x 版本：**

PHP5.0 以上版本对类的功能进行了很大的扩充。类的构造函数统一命名为\_\_construct\(\)。

在子类里父类的构造函数会不会执行，分两种情况：

1、如子类不定义构造函数 \_\_construct\(\)，则父类的构造函数默认会被继承下来，且会自动执行。

2、如子类定义了构造函数 \_\_construct\(\)，因为构造函数名也是\_\_construct\(\)，所以子类的构造函数实际上是覆盖\(override\)了父类的构造函数。这时执行的是该子类的构造函数。

这时如果要在子类里执行父类的构造函数，必须执行类似以下语句：

```php
parent::__construct();
```

例如：

```php
<?php
class base2 {
    function __construct() {
        echo 'this is base2 construct';
    }
 
    function __destruct() {}
}
 
class class2 extends base2 {
    function __construct() {
        parent::__construct();
        echo 'this is class2 construct';
    }
}
```

注意 parent::\_\_construct\(\); 语句不一定必须放在子类的构造函数中。放在子类的构造函数中仅仅保证了其在子类被实例化时自动执行。

**PHP4.0 和 5.0 类构造函数的兼容问题：**

在 PHP5.0 以上版本里，还兼容了 4.0 版本的构造函数的定义规则。如果同时定义了4.0的构造函数和 \_\_construct\(\)函数，则\_\_construct\(\) 函数优先。

为了使类代码同时兼容 PHP4.0 和 5.0，可以采取以下的方式：

```php
<?php
class class3 {
   function __construct() //for PHP5.0
   {
       echo 'this is class2 construct';
   }
 
   function class3() //for PHP4.0
   {
       $this -> __construct();
   }
}
 
$c3 = new class3;
```



