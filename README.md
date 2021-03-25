Just running this via "vite --debug" and trying to change the contents of either the main.js or style.css demonstrates this bug.

```
vite:hmr [file change] style.css +5s
vite:hmr [no modules matched] style.css +0ms
vite:hmr [file change] main.js +9s
vite:hmr [no modules matched] main.js +0ms
vite:hmr [file change] README.md +6s
vite:hmr [no modules matched] README.md +0ms
```