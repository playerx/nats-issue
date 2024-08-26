# nats.ws issue with latest Angular 18

Issue: Build doesn't work

Run: `npm run build` and you will get error:
```
✘ [ERROR] Could not resolve "crypto"

    node_modules/nats.ws/esm/nats.js:4914:24:
      4914 │       crypto1 = require('crypto');
           ╵                         ~~~~~~~~

  The package "crypto" wasn't found on the file system but is built into node. Are you trying to bundle for node? You can use "platform: 'node'" to do that, which will remove this error.
```
