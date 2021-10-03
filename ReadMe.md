#### 使用说明

##### 功能：

* JSON格式化、压缩；
* jsonpath生成（只用于生成出单一元素的jsonpath，用以辅助实现更复杂的提取，或对于新手起到帮助）；
* jsonpath提取，与上面是一个逆过程，在输入框中修改jsonpath，实时预览提取结果。

##### 页面布局：

​	左侧是原始JSON输入框，右侧上方是jsonpath输入框，下方是渲染出的JSON树。

##### 用法：

1. 点击JSON树中的某个元素，上方输入框中实时显示出对应该元素的jsonpath；

2. 如果在输入框中修改内容，则变成提取模式，下面显示的时提取出的结果，此时若需要返回到原始的JSON树，

   可以点击JSON树右上角reset按钮（鼠标悬浮时显示），回到开始内容

  ![image](https://user-images.githubusercontent.com/63774114/135744033-e68d80b3-411d-43f5-9fd3-2629ef1f59de.png)

3. 上图中的向下箭头用于一键展开JSON树，再次点击返回原先状态

**quicker动作版：** https://getquicker.net/Sharedaction?code=3700cad8-0da6-4e36-192c-08d95b8499a1&fromMyShare=true

