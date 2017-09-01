Createstore接受三个参数
-------------------
> 第一个参数是reducer,reducer就是包含action和state的一个Function
> 第二个参数是preloadedState，任意类型，初始化state值，开发中还没有用到过这个方法
> 第三个参数是enhancer  Function类型，一些中间件都会在此处传递给store
Store是什么即常用方法
--------------------
> Store是通过createstore创建出来的一个对象，在创建过程中，我们是将reducer和middleware传递给sotre了，所以sotre是包含reducer的一个树形结构对象。
> 常用方法中有dispatch和subscribe方法，dispatch一个action，可以操控store的数据，变化后产生的结果，我们需要通过subscribe来监听
> 

 
