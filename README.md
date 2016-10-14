# eslint-config-metrological
Configuration files for ESLint

[ESLint Config Metrological](git.io/eslint-config-metrological "ESLint Config Metrological")

To use this from your IDE:
- Sublime Text: https://packagecontrol.io/packages/ESLint
- WebStorm: https://www.jetbrains.com/help/webstorm/2016.2/eslint.html
- VS Code: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
- TextMate: https://github.com/natesilva/javascript-eslint.tmbundle

## TODO:
- [x] test maf.js with linter as well, before release to internal
- [x] run script on apps dir to test output
- [/] ignore maf + ui's + sdk, etc... for now, but discuss with Albert how to handle
- [x] run lint only on complete app file, to prevent undefined errors? requires source mapping!
- [x] run script to determine most made errors
- [ ] release to internal teams via flowdock (& mail???) met mooi verhaaltje
- [ ] make formatting of console output better
- [ ] fix TODO's in SDK code
- [ ] ignore iframe apps
- [ ] fix stripcomments to not remove eslint comments...
- [ ] add dependency indicators: david-dm, etc...
- [ ] provide shortcut urls to all rule definitions for ESLint
- [ ] make console logger maf into plugin formatter for eslint, with sourcemap support
- [ ] add bin file/link for easy starting sdk
- [ ] make console output linkable via chrome dev tools workspaces
- [ ] release to public maf-sdk
- [ ] incorporate in dashboard/release server
- [ ] own rules;
  - typeOf - but only in maf repo -> so that extends this default config
  - don't extend/overwrite/append to MAF namespace/components
  - (un)subscribe - but only in maf repo -> so that extends this default config
  - geen maf scope functies in function die in global scope is gedefineerd, e.g. zonder var/ als statement
  - provide shortcut urls to MAF docs for rule explainations
