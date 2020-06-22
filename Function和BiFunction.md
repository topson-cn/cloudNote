## *<font face="微软雅黑" color=4D80BF>Function</font>*

function作为一个函数式接口，主要方法apply接收一个参数，返回一个值

```
@FunctionalInterface
public interface Function<T, R> {

    /**
     * Applies this function to the given argument.
     *
     * @param t the function argument
     * @return the function result
     */
    R apply(T t);
}
```



