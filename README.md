# ModelContext Protocol Inspector
npx @modelcontextprotocol/inspector wassette serve --stdio

https://www.moonbitlang.com/pearls/moonbit-wassette

```
wassette permission grant network weather wttr.in\n
```

```
moon build --target wasm\n
wasm-tools component embed wit target/wasm/release/build/gen/gen.wasm -o dist/core.wasm --encoding utf16\n
wasm-tools component new dist/core.wasm -o dist/weather.wasm\n
wassette component load file://$(pwd)/dist/weather.wasm\n
```