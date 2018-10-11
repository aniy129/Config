### 我的配置
## 我的配置
# Config
configruation files for java application

**这个是粗体**
*这个是斜体*
***这个是粗体加斜体***

```java
@Override
protected void onDestroy() {
    EventBus.getDefault().unregister(this);
    super.onDestroy();
}
``` 
|列名1|列名2|
|:---|:---|
|列1的内容1|列2的内容1|
|列1的内容2|列2的内容2|

[点击前往谷歌搜索](https://www.baidu.com/)



### 绘制流程图 Flowchart

```flow
st=>start: 用户登陆
op=>operation: 登陆操作
cond=>condition: 登陆成功 Yes or No?
e=>end: 进入后台

st->op->cond
cond(yes)->e
cond(no)->op
```

[========]
                    
### 绘制序列图 Sequence Diagram
                    
```seq
Andrew->China: Says Hello 
Note right of China: China thinks\nabout it 
China-->Andrew: How are you? 
Andrew->>China: I am good thanks!
```

### End
