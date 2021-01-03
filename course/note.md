命令式编码 每一步都需要阐明 少做任何一步都无法实现

声明式编码 不用把每一步都写出来  



# 虚拟dom

虚拟dom 前后两次数据更新，会进行虚拟dom的比较，只会增加新生成的虚拟dom，原本的真实dom直接用

jsx是原始js创建虚拟的语法糖

虚拟dom是object类型的对象 一般对象

虚拟dom 比较轻 身上属性少

真是dom 比较重

因为虚拟dom是react内部在用，无需真实dom上那么多属性

 # xml

xml早期用于存储和传输数据



# jsx

虚拟dom只允许有一个根标签



# 何为js表达式

一个表达式会产生一个值 可以放在任何一个需要值的地方

 # 函数式组件

this是undefined 因为是babel编译后开启了严格模式

首字母必须大写

执行了ReactDOM.render(<Demo/>,document.getElementById('test')) 发生了什么

react解析组件标签，找到了Demo表情去

发现组件是函数定义的，随后调用该函数，返回虚拟dom转换为真实dom 随后呈现



# 简单组件和复杂组件

简单组件是无state的 复杂组件有state

# 组件实例的三大核心属性

仅限于用类的组件（新版中可以用hooks使得函数定义的组件也有这三大属性）

