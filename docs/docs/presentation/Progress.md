---
group:
  title: 展示
title: Progress 进度条
desc: Progress 是一个常用的组件，可以手势控制当前进度，也可仅作展示作用。
demo: /presentation/progress
---

## 代码演示

### 基础形式

```jsx
import { Progress } from 'tuya-panel-kit'

<Progress
  foreColor={{
    '0%': '#1381FB',
    '100%': '#00C36C',
  }}
  style={{ width: 100, height: 100 }}
  needMaxCircle={true}
  startColor="#1381FB"
  thumbRadius={4}
  value={50}
  startDegree={135}
  andDegree={270}
/>
```

### 间距形式

```jsx
import { Progress } from 'tuya-panel-kit'

<Progress.Space strokeWidth={2} scaleNumber={70} style={{ width: 100, height: 100 }} />
```

### 双边拖动形式

```jsx
import { Progress } from 'tuya-panel-kit'

<Progress.Double
  foreColor={{
    '0%': '#1381FB',
    '100%': '#00C36C',
  }}
  startDegree={170}
  style={{ width: 100, height: 100 }}
/>
```

### 组合形式

```jsx
import { Progress } from 'tuya-panel-kit'

<Progress.Compose style={{ width: 100, height: 100 }} />
```

## API

### Progress

继承自 [ViewProps](https://reactnative.dev/docs/view#props)

<API name="ProgressProps"></API>

### Progress.Space

<API name="SpaceProps"></API>

### Progress.Double

<API name="DoubleProps"></API>

### Progress.Compose

<API name="ComposeProps"></API>
