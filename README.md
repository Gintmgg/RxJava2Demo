> RxJava 1.x 到 RxJava 2.x 的无缝对接  
无需学习 RxJava 1.x, 直接学习 RxJava 2.x  
完备齐全的操作符示例  
支持与 Retrofit 交互处理示例  
Activity 基类封装处理 

### 文章链接：
[这可能是最好的 RxJava 2.x 入门教程（完结版）](http://www.jianshu.com/p/0cd258eecf60)<br>
[这可能是最好的 RxJava 2.x 入门教程（一）](http://www.jianshu.com/p/a93c79e9f689)<br>
[这可能是最好的 RxJava 2.x 入门教程（二）](http://www.jianshu.com/p/b39afa92807e)<br>
[这可能是最好的 RxJava 2.x 入门教程（三）](http://www.jianshu.com/p/e9c79eacc8e3)<br>
[这可能是最好的 RxJava 2.x 入门教程（四）](http://www.jianshu.com/p/c08bfc58f4b6)<br>
[这可能是最好的 RxJava 2.x 入门教程（五）](http://www.jianshu.com/p/81fac37430dd)<br>


### RxJava 1.x 到 RxJava 2.x 变化一览

RxJava 1.x -> RxJava 2.x

* `onCompleted` -> `onComplete` - without the trailing d
* `Func1` -> `Function`
* `Func2` -> `BiFunction`
* `CompositeSubscription` -> `CompositeDisposable`
* `limit` operator has been removed - Use `take` in RxJava2
* and much more.

### 一些操作符的解释

* `Map` -> transform the items emitted by an Observable by applying a function to each item
* `Zip` -> combine the emissions of multiple Observables together via a specified function and emit single items for each combination based on the results of this function
* `Filter` -> emit only those items from an Observable that pass a predicate test
* `FlatMap` -> transform the items emitted by an Observable into Observables, then flatten the emissions from those into a single Observable
* `Take` -> emit only the first n items emitted by an Observable
* `Reduce` -> apply a function to each item emitted by an Observable, sequentially, and emit the final value
* `Skip` -> suppress the first n items emitted by an Observable
* `Buffer` -> periodically gather items emitted by an Observable into bundles and emit these bundles rather than emitting the items one at a time
* `Concat` -> emit the emissions from two or more Observables without interleaving them
* `Replay` -> ensure that all observers see the same sequence of emitted items, even if they subscribe after the Observable has begun emitting items
* `Merge` -> combine multiple Observables into one by merging their emissions

该demo来源于http://www.jianshu.com/p/0cd258eecf60，仅供学习，尊重原作者劳动成果



