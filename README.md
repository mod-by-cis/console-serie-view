# console-extended

## `deno.json`

```json
{
    "imports": {  
        "@mod-by-cis/console-style-text": "https://raw.githubusercontent.com/mod-by-cis/console-extended/refs/tags/v0.0.1/mod.ts"
    }
}
```

## `main.ts`

```ts
import { ConsoleStyleText as t } from "@mod-by-cis/console-extended";

console.log(`${
  t.t("Hello, World!")
    .c({ r: 255, g: 0, b: 0 }, { r: 0, g: 255, b: 0 })._
}`);

```

---

---