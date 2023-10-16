it's a reproduction for sprout2000/create-electron-webpack issue [#213](https://github.com/sprout2000/create-electron-webpack/issues/3)

Steps
 - clone this project
 - run `npm i`
 - run `npm run rebuild`
 - run `npm run dev`
 - following error will appear in your teminal

```sh
WARNING in ./node_modules/@mapbox/node-pre-gyp/lib/util/compile.js 43:23-45
Module not found: Error: Can't resolve 'npm' in '/home/e/ws/pg/svelte-electron/node_modules/@mapbox/node-pre-gyp/lib/util'
 @ ./node_modules/@mapbox/node-pre-gyp/lib/ sync ^\.\/.*$ ./util/compile.js ./util/compile
 @ ./node_modules/@mapbox/node-pre-gyp/lib/node-pre-gyp.js 86:13-36 291:36-53
 @ ./node_modules/sqlite3/lib/sqlite3-binding.js 1:15-46
 @ ./node_modules/sqlite3/lib/sqlite3.js 2:16-47
 @ ./src/main.js 3:0-30

WARNING in ./node_modules/@mapbox/node-pre-gyp/lib/util/versioning.js 17:18-65
Critical dependency: the request of a dependency is an expression
 @ ./node_modules/@mapbox/node-pre-gyp/lib/pre-binding.js 4:19-55
 @ ./node_modules/@mapbox/node-pre-gyp/lib/node-pre-gyp.js 56:11-40
 @ ./node_modules/sqlite3/lib/sqlite3-binding.js 1:15-46
 @ ./node_modules/sqlite3/lib/sqlite3.js 2:16-47
 @ ./src/main.js 3:0-30

WARNING in ./node_modules/promise-inflight/inflight.js 6:13-32
Module not found: Error: Can't resolve 'bluebird' in '/home/e/ws/pg/svelte-electron/node_modules/promise-inflight'
 @ ./node_modules/cacache/lib/util/fix-owner.js 7:17-44
 @ ./node_modules/cacache/lib/entry-index.js 13:17-44
 @ ./node_modules/cacache/index.js 10:14-45
 @ ./node_modules/make-fetch-happen/lib/cache/entry.js 6:16-34
 @ ./node_modules/make-fetch-happen/lib/cache/index.js 2:19-40
 @ ./node_modules/make-fetch-happen/lib/fetch.js 7:14-41
 @ ./node_modules/make-fetch-happen/lib/index.js 4:14-35
 @ ./node_modules/node-gyp/lib/install.js 12:14-42
 @ ./node_modules/node-gyp/lib/ sync ^\.\/.*$ ./install.js ./install
 @ ./node_modules/node-gyp/lib/node-gyp.js 41:13-36 191:36-53
 @ ./node_modules/@mapbox/node-pre-gyp/lib/util/compile.js 31:26-53
 @ ./node_modules/@mapbox/node-pre-gyp/lib/ sync ^\.\/.*$ ./util/compile.js ./util/compile
 @ ./node_modules/@mapbox/node-pre-gyp/lib/node-pre-gyp.js 86:13-36 291:36-53
 @ ./node_modules/sqlite3/lib/sqlite3-binding.js 1:15-46
 @ ./node_modules/sqlite3/lib/sqlite3.js 2:16-47
 @ ./src/main.js 3:0-30

WARNING in ./node_modules/sqlite3/lib/sqlite3-binding.js 4:16-37
Critical dependency: the request of a dependency is an expression
 @ ./node_modules/sqlite3/lib/sqlite3.js 2:16-47
 @ ./src/main.js 3:0-30

4 warnings have detailed information that is not shown.
Use 'stats.errorDetails: true' resp. '--stats-error-details' to show it.

ERROR in ./node_modules/@mapbox/node-pre-gyp/lib/util/nw-pre-gyp/index.html 1:0
Module parse failed: Unexpected token (1:0)
You may need an appropriate loader to handle this file type, currently no loaders are configured to process this file. See https://webpack.js.org/concepts#loaders
> <!doctype html>
| <html>
| <head>
 @ ./node_modules/@mapbox/node-pre-gyp/lib/ sync ^\.\/.*$ ./util/nw-pre-gyp/index.html
 @ ./node_modules/@mapbox/node-pre-gyp/lib/node-pre-gyp.js 86:13-36 291:36-53
 @ ./node_modules/sqlite3/lib/sqlite3-binding.js 1:15-46
 @ ./node_modules/sqlite3/lib/sqlite3.js 2:16-47
 @ ./src/main.js 3:0-30

ERROR in ./node_modules/@mapbox/node-pre-gyp/lib/util/s3_setup.js 43:20-42
Module not found: Error: Can't resolve 'mock-aws-s3' in '/home/e/ws/pg/svelte-electron/node_modules/@mapbox/node-pre-gyp/lib/util'
 @ ./node_modules/@mapbox/node-pre-gyp/lib/node-pre-gyp.js 15:21-62
 @ ./node_modules/sqlite3/lib/sqlite3-binding.js 1:15-46
 @ ./node_modules/sqlite3/lib/sqlite3.js 2:16-47
 @ ./src/main.js 3:0-30

ERROR in ./node_modules/@mapbox/node-pre-gyp/lib/util/s3_setup.js 76:14-32
Module not found: Error: Can't resolve 'aws-sdk' in '/home/e/ws/pg/svelte-electron/node_modules/@mapbox/node-pre-gyp/lib/util'
 @ ./node_modules/@mapbox/node-pre-gyp/lib/node-pre-gyp.js 15:21-62
 @ ./node_modules/sqlite3/lib/sqlite3-binding.js 1:15-46
 @ ./node_modules/sqlite3/lib/sqlite3.js 2:16-47
 @ ./src/main.js 3:0-30

ERROR in ./node_modules/@mapbox/node-pre-gyp/lib/util/s3_setup.js 112:15-30
Module not found: Error: Can't resolve 'nock' in '/home/e/ws/pg/svelte-electron/node_modules/@mapbox/node-pre-gyp/lib/util'
 @ ./node_modules/@mapbox/node-pre-gyp/lib/node-pre-gyp.js 15:21-62
 @ ./node_modules/sqlite3/lib/sqlite3-binding.js 1:15-46
 @ ./node_modules/sqlite3/lib/sqlite3.js 2:16-47
 @ ./src/main.js 3:0-30

ERROR in ./node_modules/node-gyp/lib/Find-VisualStudio.cs 9:6
Module parse failed: Unexpected token (9:6)
You may need an appropriate loader to handle this file type, currently no loaders are configured to process this file. See https://webpack.js.org/concepts#loaders
| // This script needs to be compatible with PowerShell v2 to run on Windows 2008R2 and Windows 7.
| 
> using System;
| using System.Text;
| using System.Runtime.InteropServices;
 @ ./node_modules/node-gyp/lib/ sync ^\.\/.*$ ./Find-VisualStudio.cs
 @ ./node_modules/node-gyp/lib/node-gyp.js 41:13-36 191:36-53
 @ ./node_modules/@mapbox/node-pre-gyp/lib/util/compile.js 31:26-53
 @ ./node_modules/@mapbox/node-pre-gyp/lib/ sync ^\.\/.*$ ./util/compile.js ./util/compile
 @ ./node_modules/@mapbox/node-pre-gyp/lib/node-pre-gyp.js 86:13-36 291:36-53
 @ ./node_modules/sqlite3/lib/sqlite3-binding.js 1:15-46
 @ ./node_modules/sqlite3/lib/sqlite3.js 2:16-47
 @ ./src/main.js 3:0-30

3 errors have detailed information that is not shown.
Use 'stats.errorDetails: true' resp. '--stats-error-details' to show it.

webpack 5.89.0 compiled with 5 errors and 4 warnings in 1226 ms
[electronmon] restarting app due to file change
App threw an error during load
Error: svelte-electron package.json is not node-pre-gyp ready:
package.json must declare these properties: 
binary
    at Object.validate_config (/home/e/ws/pg/svelte-electron/dist/main.js:2343:11)
    at exports.find (/home/e/ws/pg/svelte-electron/dist/main.js:1084:14)
    at ./node_modules/sqlite3/lib/sqlite3-binding.js (/home/e/ws/pg/svelte-electron/dist/main.js:63009:29)
    at __webpack_require__ (/home/e/ws/pg/svelte-electron/dist/main.js:71457:42)
    at ./node_modules/sqlite3/lib/sqlite3.js (/home/e/ws/pg/svelte-electron/dist/main.js:63023:17)
    at __webpack_require__ (/home/e/ws/pg/svelte-electron/dist/main.js:71457:42)
    at /home/e/ws/pg/svelte-electron/dist/main.js:71517:65
    at /home/e/ws/pg/svelte-electron/dist/main.js:71538:3
    at Object.<anonymous> (/home/e/ws/pg/svelte-electron/dist/main.js:71540:12)
    at Module._compile (node:internal/modules/cjs/loader:1271:14)
svelte-electron encountered an error
Error: svelte-electron package.json is not node-pre-gyp ready:
package.json must declare these properties: 
binary
    at Object.validate_config (/home/e/ws/pg/svelte-electron/dist/main.js:2343:11)
    at exports.find (/home/e/ws/pg/svelte-electron/dist/main.js:1084:14)
    at ./node_modules/sqlite3/lib/sqlite3-binding.js (/home/e/ws/pg/svelte-electron/dist/main.js:63009:29)
    at __webpack_require__ (/home/e/ws/pg/svelte-electron/dist/main.js:71457:42)
    at ./node_modules/sqlite3/lib/sqlite3.js (/home/e/ws/pg/svelte-electron/dist/main.js:63023:17)
    at __webpack_require__ (/home/e/ws/pg/svelte-electron/dist/main.js:71457:42)
    at /home/e/ws/pg/svelte-electron/dist/main.js:71517:65
    at /home/e/ws/pg/svelte-electron/dist/main.js:71538:3
    at Object.<anonymous> (/home/e/ws/pg/svelte-electron/dist/main.js:71540:12)
    at Module._compile (node:internal/modules/cjs/loader:1271:14)
[electronmon] uncaught exception occured
[electronmon] waiting for any change to restart the app
[electronmon] ignoring exit with code 1

```