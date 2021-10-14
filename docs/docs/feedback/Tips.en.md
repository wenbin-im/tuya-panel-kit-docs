---
group:
  title: Feedback
title: Tips
desc: Tips is a bubble box component.
demo: /feedback/tips
---

## Code demo

### Bubble - top left

```jsx
import { Tips } from 'tuya-panel-kit'

const [state, setState] = React.useState({
  topLeft: false,
  topCenter: false,
  topRight: false,
  bottomLeft: false,
  bottomCenter: false,
  bottomRight: false,
});
const bigTips = {
  width: 110,
  height: 64,
  borderRadius: 16,
};

<Tips
  show={state.topLeft}
  contentStyle={bigTips}
  bgColor="#333333"
  cornerPosition="topLeft"
/>
```

### Bubble - top center

```jsx
import { Tips } from 'tuya-panel-kit'

const [state, setState] = React.useState({
  topCenter: false,
});
const bigTips = {
  width: 110,
  height: 64,
  borderRadius: 16,
};

<Tips
  show={state.topCenter}
  contentStyle={bigTips}
  bgColor="#333333"
  cornerPosition="topCenter"
/>
```

### Bubble - top right

```jsx
import { Tips } from 'tuya-panel-kit'

const [state, setState] = React.useState({
  topRight: false,
});
const bigTips = {
  width: 110,
  height: 64,
  borderRadius: 16,
};

<Tips
  show={state.topRight}
  contentStyle={bigTips}
  bgColor="#333333"
  cornerPosition="topRight"
/>
```

### Bubble -bottom left

```jsx
import { Tips } from 'tuya-panel-kit'

const [state, setState] = React.useState({
  bottomLeft: false,
});
const bigTips = {
  width: 110,
  height: 64,
  borderRadius: 16,
};

<Tips
  show={state.bottomLeft}
  contentStyle={bigTips}
  bgColor="#333333"
  cornerPosition="bottomLeft"
/>
```

### Bubble -bottom center

```jsx
import { Tips } from 'tuya-panel-kit'

const [state, setState] = React.useState({
  bottomCenter: false,
});
const bigTips = {
  width: 110,
  height: 64,
  borderRadius: 16,
};

<Tips
  show={state.bottomCenter}
  contentStyle={bigTips}
  bgColor="#333333"
  cornerPosition="bottomCenter"
/>
```

### Bubble -bottom right

```jsx
import { Tips } from 'tuya-panel-kit'

const [state, setState] = React.useState({
  bottomRight: false,
});
const bigTips = {
  width: 110,
  height: 64,
  borderRadius: 16,
};

<Tips
  show={state.bottomRight}
  contentStyle={bigTips}
  bgColor="#333333"
  cornerPosition="bottomRight"
/>
```

## API

<API name="TipsProps" />
