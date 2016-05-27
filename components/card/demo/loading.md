---
order: 5
title:
  zh-CN: 预加载的卡片
  en-US: Preloaded card
---

## zh-CN

数据读入前会有文本块样式。

## en-US

Show gray blocks for text until the data has been fetched.

````jsx
import { Card } from 'antd';

ReactDOM.render(
  <Card loading title="Card title" style={{ width: '34%' }}>
    Whatever content
  </Card>
, mountNode);
````
