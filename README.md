###这是什么？
laravel有些核心类库无法满足需求，未提供扩展接口，无法通过事件形式进行的情况下只能通过服务扩展的方式实现。

类库的主要原则是：不破坏原有功能，主要使用类继承来扩展。

按照laravel的目录结构，很容易在src中找到对应的组件目录，每个组件都有README。

安装方法：

进入laravel根目录，执行composer命令：

    composer require keepeye/laravel:0.*