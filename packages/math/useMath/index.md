---
category: '@Math'
---

# useMath

Use Math reactively

## Usage

```ts
import { round, useFloor } from '@vueuse/math'

const value = ref(45.95)
const rounded = round(value)
// rounded.value is 46
const floored = useFloor(value)
// floored.value is 45
```
