9.85 KB gzipped (26.6 KB uncompressed).

Zippy Angular app using renderComponent and component render modules.

1 Angular module, 2 components, 1 directive, 1 pipe.

# AOT caveat
Commment out this line (line 70)

```
addDiagnostics(util_1.makeDuplicateDeclarationError(node, duplicateDeclarations, kind));
```

in `node_modules/@angular/compiler-cli/src/ngtsc/annotations/src/diagnostics.js`
to enable AOT compilation.