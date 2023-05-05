Reproduction for error originating from a cyclic dependency inside VPS:

```
TypeError: (0 , assert_1.assertUsage) is not a function
    at assertSingleInstance (/home/rom/tmp/hattip-vps-issue/node_modules/.pnpm/vite-plugin-ssr@0.4.122-draft.56544_vite@4.3.4/node_modules/vite-plugin-ssr/dist/cjs/utils/assertSingleInstance.js:22:38)
    at onProjectInfo (/home/rom/tmp/hattip-vps-issue/node_modules/.pnpm/vite-plugin-ssr@0.4.122-draft.56544_vite@4.3.4/node_modules/vite-plugin-ssr/dist/cjs/utils/assertSingleInstance.js:61:5)
    at Object.<anonymous> (/home/rom/tmp/hattip-vps-issue/node_modules/.pnpm/vite-plugin-ssr@0.4.122-draft.56544_vite@4.3.4/node_modules/vite-plugin-ssr/dist/cjs/utils/projectInfo.js:13:42)
    at Module._compile (node:internal/modules/cjs/loader:1254:14)
    at Module._extensions..js (node:internal/modules/cjs/loader:1308:10)
    at Module.load (node:internal/modules/cjs/loader:1117:32)
    at Module._load (node:internal/modules/cjs/loader:958:12)
    at Module.require (node:internal/modules/cjs/loader:1141:19)
    at require (node:internal/modules/cjs/helpers:110:18)
    at Object.<anonymous> (/home/rom/tmp/hattip-vps-issue/node_modules/.pnpm/vite-plugin-ssr@0.4.122-draft.56544_vite@4.3.4/node_modules/vite-plugin-ssr/dist/cjs/utils/assert.js:6:23)
```
