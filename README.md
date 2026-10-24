# JSONPath Expression Extractor & Tester

Paste any JSON into the left pane and type a JSONPath expression to instantly extract and highlight matching values. Supports dot notation, bracket notation, wildcards (`*`), and array indices, with a live "no match" indicator for invalid or unresolved paths. Results are shown in a syntax-highlighted extracted-values panel alongside the highlighted source JSON.

## Features

- Real-time extraction as you type the path expression
- Syntax-highlighted JSON display with color-coded keys, strings, numbers, booleans, and nulls
- Supports `$`, `.child`, `[index]`, `[*]`, `*` wildcard, and `['bracket']` notation
- Match count badge and per-result labeling for multi-value results
- Pre-loaded sample JSON (bookstore) with one-click example paths
