#### react源码分析

#### 一、核心API
  1. createElement
  2. createContext
  3. JSX=>JS
      > 在线测试：https://www.babeljs.cn/repl
  4. ConcurrentMode
  5. Ref
  6. Component
  7. Supense
  8. Hooks

#### 二、React中的更新创建的几个API
  1. ReactDom.render
  2. Fiber
  3. UpdateQueue
  4. FiberRoot
  5. Update
  6. expirationTime

#### 三、Fiber Scheduler(创建完更新后的调度)
  1. scheduleWork
  2. batchedUpdates
  3. performWork
  4. performUnitOfWork
  5. requestWork
  6. react scheduler
  7. renderRoot

#### 四、开始更新
  1. beginWork以及优化
  2. 各类组件的更新过程
  3. 调和子节点的过程

#### 五、完成各个节点的更新
  1. completeUnitOfWork
  2. completeWork
  3. unwindWork
  4. 虚拟DOM对比
  5. 错误捕获处理
  6. 完成整棵树的更新

#### 六、提交更新（真正的UI更新过程）
  1. commitRoot整体流程
  2. 提交快照
  3. 提交DOM更新
  4. 提交所有生命周期
  5. 开发时的帮助方法
  6. 提交DOM插入
  7. 提交DOM删除

#### 七、各种功能的实现过程
  1. context的实现过程
  2. ref的实现过程
  3. hydrate的实现过程
  4. React的事件体系

#### 八、Suspense
  1. 更新优先级的概念
  2. Suspense组件更新
  3. retry重新尝试渲染
  4. 更新挂起的概念
  5. timeout处理
  6. lazy组件更新
#### Hooks
  1. 核心原理
  2. useEffect
  3. 其他Hooks API
  4. useState
  5. useContext


