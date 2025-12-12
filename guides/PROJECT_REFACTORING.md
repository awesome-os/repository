# Refactoring

- Always use only Typescript
- always Verbatim syntax and earsableSyntax
- see proposal TypeAnnotations:
  - [ ] [STAGE-2](https://github.com/tc39/proposal-type-annotations/issues/245)

```js
{
  "compilerOptions": {
    // The key new flag that provides the static guarantee
    "erasableSyntaxOnly": true,

    // Ensures the module system is 1-to-1 with standard JS
    "verbatimModuleSyntax": true,
    "allowImportingTsExtensions": true,
    "module": "esnext",

    // Standard best practices for this mode
    "target": "esnext",
    "noEmit": true
  }
}
```
