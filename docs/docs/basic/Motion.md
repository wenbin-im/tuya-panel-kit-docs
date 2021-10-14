---
group:
  title: 通用
title: Motion 动效
desc: '`Motion` 是一个用于丰富组件动作的组件。'
demo: /basic/motion
---

## 代码演示

### 淡入淡出

```jsx
import { Motion } from 'tuya-panel-kit'

const [fadeShow, setFadeShow] = React.useState(false);

const contentStyles = {
  width: 375,
  height: 200,
  backgroundColor: '#fff',
};

<Motion.Fade
  style={{ position: 'absolute', bottom: 0 }}
  show={fadeShow}
  onHide={() => setFadeShow(false)}
>
  <View style={contentStyles} />
</Motion.Fade>
```

### 上拉下滑

```jsx
import { Motion } from 'tuya-panel-kit'

const [pullUpShow, setPullUpShow] = React.useState(false);

const contentStyles = {
  width: 375,
  height: 200,
  backgroundColor: '#fff',
};

<Motion.PullUp
  style={{ position: 'absolute', bottom: 0 }}
  dropHeight={200}
  show={pullUpShow}
  onHide={() => setPullUpShow(false)}
>
  <View style={[contentStyles, { bottom: 0 }]} />
</Motion.PullUp>
```

### 放大淡入/缩小淡出

```jsx
import { Motion } from 'tuya-panel-kit'

const [scaleFadeInShow, setScaleFadeInShow] = React.useState(false);

const contentStyles = {
  width: 375,
  height: 200,
  backgroundColor: '#fff',
};

<Motion.ScaleFadeIn
  style={{ position: 'absolute', bottom: 0 }}
  show={scaleFadeInShow}
  onHide={() => setScaleFadeInShow(false)}
>
  <View style={contentStyles} />
</Motion.ScaleFadeIn>
```

### 放大淡入/下滑淡出

```jsx
import { Motion } from 'tuya-panel-kit'

const [scalePullDownShow, setScalePullDownShow] = React.useState(false);

const contentStyles = {
  width: 375,
  height: 200,
  backgroundColor: '#fff',
};

<Motion.ScalePullDown
  show={scalePullDownShow}
  onHide={() => setScalePullDownShow(false)}
>
  <View style={contentStyles} />
</Motion.ScalePullDown>
```

### 下拉上推

```jsx
import { Motion } from 'tuya-panel-kit'

const [pushDownShow, setPushDownShow] = React.useState(false);
const contentStyles = {
  width: 375,
  height: 200,
  backgroundColor: '#fff',
};

<Motion.PushDown
  style={{ position: 'absolute', bottom: 0 }}
  show={pushDownShow}
  onHide={() => setPushDownShow(false)}
  dropHeight={100}
>
  <View style={contentStyles} />
</Motion.PushDown>
```

### 无操作放大淡入/缩小淡出

```jsx
import { Motion } from 'tuya-panel-kit'

const [toastShow, setToastShow] = React.useState(false);
const contentStyles = {
  width: 375,
  height: 200,
  backgroundColor: '#fff',
};

<Motion.Toast
  style={{ position: 'absolute', bottom: 50 }}
  show={toastShow}
  onHide={() => setToastShow(false)}
>
  <View style={contentStyles} />
</Motion.Toast>
```

## API

### Motion.Fade

<API name="MotionFadeProps"></API>

### Motion.PullUp

<API name="MotionPullUpProps"></API>

### Motion.ScaleFadeIn

<API name="MotionScaleFadeInProps"></API>

### Motion.ScalePullDown

<API name="MotionScalePullDownProps" ></API>

### Motion.PushDown

<API name="MotionPushDownProps" ></API>

### Motion.Toast

<API name="MotionToastProps"></API>
