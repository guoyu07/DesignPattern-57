*定义：
为子系统中的一组接口提供一个一致的界面.


*角色：
1)IFacade 抽象外观类
2)ConcreateFacade 具体外观类（可以针对客户端的不同，定义多个外观类）


*
外观模式的关键在于：隐藏了各个元件之间的合作行为，对外提供一个外观类。


*
1.降低系统间耦合度
2.Facade模式隐藏了各个元件之间的合作行为，以及元件本身的操作与设定细节，固而必失去了一些直接操作元件的方便性
3.典型应用：数据库JDBC的应用