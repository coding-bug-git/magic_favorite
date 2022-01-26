### Author :coding - bug
### 效果展示


![image.png](https://cdn.nlark.com/yuque/0/2022/png/21514340/1643204891803-5a35d465-52ab-4a26-ac0a-1506e9bbb832.png#clientId=u49b39c3f-e044-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=992&id=u15e49aaf&margin=%5Bobject%20Object%5D&name=image.png&originHeight=992&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=1432570&status=done&style=none&taskId=u9d8923ff-54b7-457b-99a2-f4c5f7b84aa&title=&width=1920)
### How To Use

1. 收藏任意网址到收藏栏
1. 编辑刚刚收藏的网址url
1. copy code to the url

**注意：代码复制一定要 复制 **`**javascript:**`**开头。  **
![image.png](https://cdn.nlark.com/yuque/0/2022/png/21514340/1643206149699-8a62e855-391b-4031-8993-6f961fafd61f.png#clientId=u8c64da07-5d2c-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=263&id=ubc77af20&margin=%5Bobject%20Object%5D&name=image.png&originHeight=263&originWidth=387&originalType=binary&ratio=1&rotation=0&showTitle=false&size=10162&status=done&style=none&taskId=ue64d0b5c-34a5-41c6-a79f-8e7369c90f2&title=&width=387)
​

### 原理
收藏栏通过 ：`javascript:`标签识别后续的js代码以执行
例：
```
javascript: alert('coding-bug');
```
​

### 注意事项

1. 尽量避免直接定义变量以免造成变量冲突
1. 尽量不要有以赋值字符串或返回值结束语句。
   1. 会造成页面伪刷新问题
3. 尽量不要使用 `+=`更新 `body`标签，可以使用append

​

