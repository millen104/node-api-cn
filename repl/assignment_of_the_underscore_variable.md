
默认的解释器会把下划线 `_` 解释为最近一次执行的表达式。

```js
> [ 'a', 'b', 'c' ]
[ 'a', 'b', 'c' ]
> _.length
3
> _ += 1
4
```

显式设置下划线 `_` 为某个值会禁用上述行为。

