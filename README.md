# A-thread-pool-based-on-a-mutable-parameter-template-implementation
开发环境：vs2019开发，C++17标准；centos7编译so动态库
使用的技术点：
熟练基于C++ 11标准的面向对象编程、熟悉C++11多线程编程、C++17和C++20标准的内容、C++17的any类型和C++20的信号量semaphore、熟悉多线程理论等
主要内容：
1、基于可变参模板编程和引用折叠原理，实现线程池submitTask接口，支持任意任务函数和任意参数的传递
2、使用future类型定制submitTask提交任务的返回值
3、使用map和queue容器管理线程对象和任务
4、基于条件变量condition_variable和互斥锁mutex实现任务提交线程和任务执行线程间的通信机制
5、支持fixed和cached模式的线程池定制
