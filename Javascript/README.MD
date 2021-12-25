## 数组的方法
  1.pop()
    **调用 arr.pop()方法会删除数组的最后一个元素，返回值就是删除的这个元素;**
```javaScript
    let arr = [1,2,3,4,5,6,7,8,9,0];
    let del = arr.pop()
    console.log(arr)  // => [1,2,3,4,5,6,7,8,9]
    console.log(del); // => 0
```
  2.push()
  **调用push()方法会向数组末尾追加一个或多个元素，返回更新后数组的长度**
```javaScript
    let arr = [1,2,3,4,5,6,7,8,9,0];
    let push = arr.push('eval')
    console.log(arr)  // => [1,2,3,4,5,6,7,8,9,0,'eval']
    console.log(push); // => 11
```
    
