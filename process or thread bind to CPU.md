# linux绑定进程到某个CPU上
taskset -p 进程号 -c 0,1

# java 线程CPU亲和性的一个实现：实现了将线程绑定到CPU上
https://github.com/OpenHFT/Java-Thread-Affinity

# java线程上下文切换带来的系统开销原因分析
http://ifeve.com/java-context-switch/
