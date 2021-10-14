---
group:
  title: 反馈
title: GlobalToast 全局吐司
desc: '`GlobalToast` 是一个挂载在 FullView 上伴有淡入淡出动画效果的全局提示。'
demo: /feedback/global-toast
---

## 代码演示

### 基础使用

```jsx
import { GlobalToast } from 'tuya-panel-kit'

GlobalToast.show({
  text: '提示性文案建议最多展示十六个字符',
  showIcon: false,
  contentStyle: {},
  onFinish: () => {
    console.log('Toast结束');
    GlobalToast.hide();
  },
});
```

### 加载使用

```jsx
import { GlobalToast } from 'tuya-panel-kit'

GlobalToast.show({
  text: '设置成功',
  onFinish: () => {
    console.log('Toast结束');
    GlobalToast.hide();
  },
});
```

## API

<API name="GlobalToastProps" />
