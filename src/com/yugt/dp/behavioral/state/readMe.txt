*定义：
把依赖于状态的逻辑集中到一组类，每一个类代表一种不同的状态，避免if语句嵌套过深或过于复杂，转而依赖于多态性来调用不同的方法。
即：把状态与行为封装到一起，免去方法中判断状态选择行为的逻辑


*角色：
1)context 包含各种状态的主体
2)state 抽象的状态
3)concreteState 具体的某种状态


*
状态模式的关键在于：把各种状态与相应的行为绑定


*
1.对象的状态由各个属性的当前值构成
2.对象的状态可能是决定其行为的关键因素，依赖于状态的代码逻辑可能遍布于类的大量方法
3.每个状态封装对应的行为，所谓对应的行为就是，从此状态转出（或者说是指向其他状态）需要做的事情。
      即：只需要封装转出的，而不用封装转入的行为。
