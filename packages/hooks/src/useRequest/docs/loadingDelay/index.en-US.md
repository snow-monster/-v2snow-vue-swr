---
map:
  # 映射到docs的路径
  path: /useRequest/loadingDelay/
---

# Loading Delay

By setting `options.loadingDelay`, you can delay the time when `loading` turns to `true`, effectively prevent UI flashing.

## Code demonstration

### Basic usage

<demo src="./demo/demo.vue"
  language="vue"
  title=""
  desc="effectively prevent UI flashing"> </demo>

## API

| Property | Description | Type | Default |
| --- | --- | --- | --- |
| loadingDelay | Set the delay time for `loading` to become `true` | `number` \| `Ref<number>` | `0` |

## Remark

`options.loadingDelay` supports dynamic changes.
