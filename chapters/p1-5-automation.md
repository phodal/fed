# 自动化提高效率

## 自动化测试加快上线流程

### 测试

测试页面的输出结果，保证元素的准确性~

stub: 结果，返回预期的结果。

mock: 行为，预期方法被调用。

### ui 测试

React Test Renderer

```
<Modal
  animationType="fade"
  hardwareAccelerated={false}
  onRequestClose={[Function]}
  transparent={true}
  visible={false}
>
  <View>
    <View
      style={
        Object {
          "alignItems": "center",
          "backgroundColor": "rgba(0,0,0,.1)",
          "height": 1334,
          "justifyContent": "center",
        }
      }
    >
  ...    
```    

### 截屏测试，

对于那些 UI 改动较小的系统来说，这

而我们知道页面截图尽管可以作为版本管理的一部分，但是一个不可比对的结果

而诸如，react-test-render， Virtual Dom 测试

那么，对于普通的 HTML 结构的

![PhantomCSS](images/PhantomCSS.png)

## 自动构建

在之前的构建系统一节里，我们讲了 xx。剩下要做的就是生成打包好的源码

Gulp、Grunt

## 自动化部署

只需要一些 持续集成 的基础，如 Jenkins

### 持续集成

