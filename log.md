### 测试1
1. 新建dev分之
2. 新建test-rebase分之
3. 修改test-rebase分之的内容
4. push test-rebase
5. merge test-rebase 至 dev
  
结果: test-rebase和dev分之都只有一次提交记录

### 测试2
1. 在dev分之修改a.js
2. 在test-rebase分之修改b.js
3. merge test-rebase 至 dev