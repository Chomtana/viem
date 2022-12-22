# setBlockTimestampInterval

Similar to [`increaseTime`](/TODO), but sets a block timestamp `interval`. The timestamp of the next block will be computed as `lastBlock_timestamp` + `interval`.

## Import 

```ts
import { setBlockTimestampInterval } from 'viem'
```

## Usage

```ts
import { setBlockTimestampInterval } from 'viem'
import { testClient } from '.'
 
await setBlockTimestampInterval(testClient, { // [!code focus:4]
  interval: 5
})
```

## Configuration

### interval

- **Type:** `number`

```ts
await setBlockTimestampInterval(testClient, {
  interval: 1 // [!code focus]
})
```