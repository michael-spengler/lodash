[![nest badge](https://nest.land/badge.svg)](https://nest.land/package/lodash)

# Lodash
In comparison to https://nest.land/package/deno-lodash the module at hand uses a fixed version for the lodash dependency. See lodash.ts file.

## Usage Example

```ts

import { ld } from 'https://x.nest.land/lodash@0.1.0/mod.ts';

let words = ['sky', 'wood', 'forest', 'falcon', 
    'pear', 'ocean', 'universe'];

let fel = ld.first(words);
let lel = ld.last(words);

console.log(`First element: ${fel}`);
console.log(`Last element: ${lel}`);

```

## Trigger Usage Example

```sh

deno run --allow-read --unstable --allow-env https://x.nest.land/lodash@0.1.0/usage-example.ts

```

## Trigger Test Execution

```sh

deno test --allow-read --unstable --allow-env https://x.nest.land/lodash@0.1.0/test.ts
  
```

## Documentation
[lodash docs](https://lodash.com/docs/4.17.15)