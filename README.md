## Hi, I'm Jacqueline 👋

Front-end developer based in Sydney, Australia. I work mostly in **React**, **TypeScript** and
**Vue**, and I like problems where the fix is small but finding it isn't.

---

### Open source

**[microsoft/vscode-documentdb](https://github.com/microsoft/vscode-documentdb)** — DocumentDB Extension for VS Code

- **[#662](https://github.com/microsoft/vscode-documentdb/pull/662)** · *merged* — The default `_id_`
  index was being displayed below uppercase-named indexes. Root cause: `_` (ASCII 95) sorts after
  `A–Z` (ASCII 65–90) under locale-aware comparison. Extracted the inline sort lambda into an
  exported, testable `compareIndexNames()` and added the component's first test suite (8 tests).
  Also fixed a comparator-contract violation raised in review — equal inputs returned `-1`, breaking
  antisymmetry. The comparator is live in `main`.

- **[#713](https://github.com/microsoft/vscode-documentdb/pull/713)** — Field autocomplete emitted
  `$fieldName` unconditionally, producing invalid MQL for names like `order-items` or `my field`.
  Routed unsafe path segments through `{ $getField: … }`, and returned no reference at all for unsafe
  nested paths rather than emitting a wrong expression. Maintainers confirmed this was the earlier
  submission and credited its scoping before consolidating the fix.

---

### Projects

| | |
|---|---|
| **[webtube](https://github.com/Jacquelinezhong/webtube)** | Video streaming site — TypeScript, React, Vite, Tailwind CSS · [live](https://webtubejac-jacquelinezhongs-projects.vercel.app/) |
| **[shopsy](https://github.com/Jacquelinezhong/shopsy)** | E-commerce front end — JavaScript, React · [live](https://shopsy-seven-omega.vercel.app/) |

---

### Working with

`TypeScript` `JavaScript` `React` `React Native` `Vue` `Node.js` `Tailwind CSS` `Vite` `Jest`
`Shopify` `MySQL` `MongoDB` `Git` — and AI coding tools (Claude Code, Cursor) as part of my day-to-day
workflow.

---

📫 jacquelinezhong08@gmail.com · [LinkedIn](https://www.linkedin.com/in/jie-jaczhong)
