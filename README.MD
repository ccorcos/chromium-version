# chromium-version

> Fork of node-chromium, with release version pinned to a specific version of Chromium.

Install a specific version of Chromium:
```sh
npm install --save chromium-version@77
npm install --save chromium-version@78
npm install --save chromium-version@79 # broken
npm install --save chromium-version@80 # broken
```

**TODO**: need to update `./versions.js` with the latest versions and update `./utils.js` to allow for newer versions. Please submit a PR if you'd like to fix these issues!

Get the path to the binary:
```js
require("chromium-version").path
```

More information at https://github.com/dtolstyi/node-chromium