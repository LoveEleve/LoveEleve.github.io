<div class="home-mug">
<a href="https://github.com/LoveEleve" target="_blank" rel="noopener" class="home-gh-link" title="GitHub">
<svg viewBox="0 0 24 24" width="18" height="18"><path fill="currentColor" d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg>
</a>
</div>

# Join_Sen's Blog

> 深入源码，探究原理，分享后端技术干货
>
> 这里主要记录并发编程、分布式系统、JVM 等后端技术深度解析

## 并发编程学习之路

**Java 内存模型**

* [Java 内存模型浅析](concurrent/Java内存模型浅析/Java内存模型浅析) — 深入理解 JMM 内存模型与 happens-before 规则

**Java 线程原理**

* [Java 线程原理](concurrent/java线程原理/java线程原理) — 深入解析 Java 线程的底层实现机制

**高并发容器**

* [高并发容器](concurrent/高并发容器/高并发容器) — 深入解析 ConcurrentHashMap、CopyOnWrite 等线程安全容器

**Synchronized**

* [Synchronized 浅析（1）](concurrent/synchronized/Synchronized浅析-1/Synchronized浅析-1) — 管程、synchronized 与对象监视器
* [Synchronized 浅析（2）](concurrent/synchronized/Synchronized浅析-2/Synchronized浅析-2) — wait/notify 与等待队列
* [Synchronized 浅析（3）](concurrent/synchronized/Synchronized浅析-3/Synchronized浅析-3) — park/unpark 与 JVM Parker

**线程池**

* [线程池（1）](concurrent/线程池相关/线程池-1/线程池-1) — ThreadPoolExecutor 设计与实现
* [线程池（2）](concurrent/线程池相关/线程池-2/线程池-2) — Executors 工厂线程池特性
* [线程池（3）](concurrent/线程池相关/线程池-3/线程池-3) — Runnable/Callable/FutureTask
* [阻塞队列](concurrent/线程池相关/阻塞队列/阻塞队列) — 各种阻塞队列的实现原理
* [CompletableFuture](concurrent/线程池相关/CompletableFuture/CompletableFuture) — 异步编程详解
* [CompletionService](concurrent/线程池相关/CompletionService/CompletionService) — 批量异步任务
* [ForkJoinPool](concurrent/线程池相关/ForkJoinPool/ForkJoinPool) — 工作窃取与 Fork/Join

**AQS**

* [并发前置思考](concurrent/AQS/关于并发的前置思考/关于并发的前置思考) — 并发基础概念
* [管程的概念](concurrent/AQS/管程的概念) — Monitor 机制
* [AQS 设计理念](concurrent/AQS/AQS设计理念/AQS设计理念) — AbstractQueuedSynchronizer 设计
* [AQS 源码解析](concurrent/AQS/AQS源码解析/AQS源码解析) — 深入 AQS 实现

**线程本地变量**

* [ThreadLocal（1）](concurrent/线程本地变量/线程本地变量-1/线程本地变量-1) — 核心原理与线程隔离
* [ThreadLocal（2）](concurrent/线程本地变量/线程本地变量-2/线程本地变量-2) — InheritableThreadLocal
* [ThreadLocal（3）](concurrent/线程本地变量/线程本地变量-3/线程本地变量-3) — Netty FastThreadLocal

**同步器**

* [JUC 同步器](concurrent/同步器/同步器) — Semaphore/CountDownLatch/CyclicBarrier

**管程实现**

* [管程实现](concurrent/管程实现/管程实现) — ReentrantLock/ReadWriteLock/StampedLock

**条件变量**

* [条件变量](concurrent/条件变量/条件变量) — Condition 与生产者消费者

**Atomic Package**

* [atomic package](concurrent/atomic%20package/atomic%20package) — LongAdder/AtomicStampedReference 无锁编程
