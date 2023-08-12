# lilireleases

Step 1. Ensure GH_TOKEN is set with:
```
export GH_TOKEN=<token>
env | grep GH
```

Step 2. Run npm publish
```
npm run publish
```

# Notes
electron-builder is used and not electron-packager

The settings for build are in quasar.config.js under electron{builder:{}}
