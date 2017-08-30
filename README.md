# Safe Browsing v4 Crash Rate Shield Study

## install

`npm install`
`npm run build`


at second shell/prompt, watch files for changes to rebuild:

`npm run watch`


## in Firefox:

1. `about:config`, set
   1. `extensions.legacy.enabled` to `true`
   2. `xpinstall.signatures.required` to `false`
2. `about:debugging > [load temporary addon] > choose `dist/addon.xpi`
3. `tools > Web Developer > Browser Toolbox`

