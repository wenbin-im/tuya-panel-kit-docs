---
group:
  title: Basic
title: TYText
desc: 'In **React Native**, the default props of the `Text` component are inconsistent on Android and IOS.<br/>`TYText` has a layer of encapsulation on the `Text` component to ensure that the IOS and Android are consistent.'
demo: /basic/tytext
---

## Code demo

### Basic style

```jsx
import { TYText } from 'tuya-panel-kit'

<TYText color="red" text="I am Tuya'er" weight="bold" size={24} />
```

### Use with size and type

```jsx
import { TYText } from 'tuya-panel-kit'

<View>
  <TYText size="small" type="paragraph" text="Tuya" />
  <TYText
    size="small"
    type="title"
    text="Tuya"
    style={{ marginHorizontal: 20 }}
  />
  <TYText size="small" type="heading" text="Tuya" />
</View>
```

```jsx
import { TYText } from 'tuya-panel-kit'

<View>
  <TYText size="normal" type="paragraph" text="Tuya" />
  <TYText
    size="normal"
    type="title"
    text="Tuya"
    style={{ marginHorizontal: 20 }}
  />
  <TYText size="normal" type="heading" text="Tuya" />
</View>
```

```jsx
import { TYText } from 'tuya-panel-kit'

<View>
  <TYText size="large" type="paragraph" text="Tuya" />
  <TYText
    size="large"
    type="title"
    text="Tuya"
    style={{ marginHorizontal: 20 }}
  />
  <TYText size="large" type="heading" text="Tuya" />
</View>
```

## API

extends [TextProps](https://reactnative.dev/docs/text#props)

<API name="TYTextProps"></API>
