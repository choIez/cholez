# 为什么学习算法？

其实在工作中，几乎没有用到什么算法，为什么还是有很多企业在前端招聘中要求会算法呢？前端到底要不要学习算法呢？也许是作为面试的筛选条件，也许是我还没有接触到需要算法的场景。

经过半个月的学习，算法也没有想象中的那么难，也不像有些人说的那样 “算法对前端没用”。还是有一些收获的，最大的感悟就是，算法好像就是在阻止我们使用一些
**很好用** 的 API，而我们需要使用最基础的程序结构去实现与这些 API 一样的效果，并且要让程序的计算次数更少。

而且数据结构与算法在前端的应用并不少，只是我们平常容易忽略。我们经常使用的框架，例如 Vue、React，或者一些第三方库，都有很多的应用场景。

所以，长远来看，前端还是应该学习算法的，至少对我来说是有这个必要的。

## 数据结构与算法在前端的应用

- **队列**：JS 任务队列，取消重复请求是用队列存储最近的请求。

- **栈**：JS 执行上下文栈、Nodejs 中间件（洋葱模型）。

- **树**：DOM 树、AST 树、Vue 和 React 的 `Virtual DOM` 树。

- **哈希表**：快速查找和数据去重，但是前端基本都用数组，可能在操作数据库的场景更多一点。

- `Virtual DOM` 的更新使用了 **diff 算法**，`KeepAlive` 使用了 **LRU 算法**。

- Vue3 使用**最长递增子序列**对 diff 算法进行了优化。

当然，这些只是冰山一角，还有更多的场景需要我去发现与探索。
