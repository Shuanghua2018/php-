# php常量

**常量为自动全局，不能改变其值。**

## 定义方法
  define('TEST', 'This is a test!');
  如果想让常量名大小写不敏感的话，define最后加上true，如下
  define('TEST', 'This is a test!', true);
  echo test;
  echo TEST;
  结果都是一样的。

## 查看所有定义的常量
  get_defined_contants();



