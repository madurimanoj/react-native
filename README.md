# react-native
manojmaduri$ npm i -g react-native-cli
/usr/local/bin/react-native -> /usr/local/lib/node_modules/react-native-cli/index.js
/usr/local/lib
└─┬ react-native-cli@2.0.1
  ├─┬ chalk@1.1.3
  │ ├── ansi-styles@2.2.1
  │ ├── escape-string-regexp@1.0.5
  │ ├─┬ has-ansi@2.0.0
  │ │ └── ansi-regex@2.1.1
  │ ├── strip-ansi@3.0.1
  │ └── supports-color@2.0.0
  ├── minimist@1.2.0
  ├─┬ prompt@0.2.14
  │ ├── pkginfo@0.4.1
  │ ├─┬ read@1.0.7
  │ │ └── mute-stream@0.0.7
  │ ├── revalidator@0.1.8
  │ ├─┬ utile@0.2.1
  │ │ ├── async@0.2.10
  │ │ ├── deep-equal@1.0.1
  │ │ ├── i@0.3.6
  │ │ ├─┬ mkdirp@0.5.1
  │ │ │ └── minimist@0.0.8
  │ │ ├── ncp@0.4.2
  │ │ └─┬ rimraf@2.6.2
  │ │   └─┬ glob@7.1.2
  │ │     ├── fs.realpath@1.0.0
  │ │     ├─┬ inflight@1.0.6
  │ │     │ └── wrappy@1.0.2
  │ │     ├── inherits@2.0.3
  │ │     ├─┬ minimatch@3.0.4
  │ │     │ └─┬ brace-expansion@1.1.8
  │ │     │   ├── balanced-match@1.0.0
  │ │     │   └── concat-map@0.0.1
  │ │     ├── once@1.4.0
  │ │     └── path-is-absolute@1.0.1
  │ └─┬ winston@0.8.3
  │   ├── colors@0.6.2
  │   ├── cycle@1.0.3
  │   ├── eyes@0.1.8
  │   ├── isstream@0.1.2
  │   ├── pkginfo@0.3.1
  │   └── stack-trace@0.0.10
  └── semver@5.4.1

manojmaduri$ react native init ReactApp
-bash: react: command not found
manojmaduri$ react-native init ReactApp
This will walk you through creating a new React Native project in /Users/manojmaduri/Documents/react-app/ReactApp
Installing react-native...
Consider installing yarn to make this faster: https://yarnpkg.com
npm WARN deprecated connect@2.30.2: connect 2.x series is deprecated

> fsevents@1.1.3 install /Users/manojmaduri/Documents/react-app/ReactApp/node_modules/fsevents
> node install

[fsevents] Success: "/Users/manojmaduri/Documents/react-app/ReactApp/node_modules/fsevents/lib/binding/Release/node-v48-darwin-x64/fse.node" already installed
Pass --update-binary to reinstall or --build-from-source to recompile
ReactApp@0.0.1 /Users/manojmaduri/Documents/react-app/ReactApp
├── UNMET PEER DEPENDENCY react@16.0.0
└─┬ react-native@0.50.3
  ├── absolute-path@0.0.0
  ├── art@0.10.1
  ├─┬ babel-core@6.26.0
  │ ├─┬ babel-code-frame@6.26.0
  │ │ ├── esutils@2.0.2
  │ │ └── js-tokens@3.0.2
  │ ├─┬ babel-generator@6.26.0
  │ │ ├─┬ detect-indent@4.0.0
  │ │ │ └─┬ repeating@2.0.1
  │ │ │   └── is-finite@1.0.2
  │ │ ├── jsesc@1.3.0
  │ │ └── trim-right@1.0.1
  │ ├── babel-helpers@6.24.1
  │ ├── babel-messages@6.23.0
  │ ├── babel-template@6.26.0
  │ ├─┬ babel-traverse@6.26.0
  │ │ ├── globals@9.18.0
  │ │ └── invariant@2.2.2
  │ ├─┬ babel-types@6.26.0
  │ │ └── to-fast-properties@1.0.3
  │ ├── babylon@6.18.0
  │ ├── convert-source-map@1.5.0
  │ ├── json5@0.5.1
  │ ├─┬ minimatch@3.0.4
  │ │ └─┬ brace-expansion@1.1.8
  │ │   ├── balanced-match@1.0.0
  │ │   └── concat-map@0.0.1
  │ ├── path-is-absolute@1.0.1
  │ ├── private@0.1.8
  │ ├── slash@1.0.0
  │ └── source-map@0.5.7
  ├── babel-plugin-syntax-trailing-function-commas@6.22.0
  ├─┬ babel-plugin-transform-async-to-generator@6.16.0
  │ ├── babel-helper-remap-async-to-generator@6.24.1
  │ └── babel-plugin-syntax-async-functions@6.13.0
  ├─┬ babel-plugin-transform-class-properties@6.24.1
  │ ├─┬ babel-helper-function-name@6.24.1
  │ │ └── babel-helper-get-function-arity@6.24.1
  │ └── babel-plugin-syntax-class-properties@6.13.0
  ├─┬ babel-plugin-transform-flow-strip-types@6.22.0
  │ └── babel-plugin-syntax-flow@6.18.0
  ├─┬ babel-plugin-transform-object-rest-spread@6.26.0
  │ └── babel-plugin-syntax-object-rest-spread@6.13.0
  ├─┬ babel-register@6.26.0
  │ ├── core-js@2.5.1
  │ ├─┬ home-or-tmp@2.0.0
  │ │ ├── os-homedir@1.0.2
  │ │ └── os-tmpdir@1.0.2
  │ └── source-map-support@0.4.18
  ├─┬ babel-runtime@6.26.0
  │ └── regenerator-runtime@0.11.0
  ├── base64-js@1.2.1
  ├─┬ chalk@1.1.3
  │ ├── ansi-styles@2.2.1
  │ ├── escape-string-regexp@1.0.5
  │ ├─┬ has-ansi@2.0.0
  │ │ └── ansi-regex@2.1.1
  │ ├── strip-ansi@3.0.1
  │ └── supports-color@2.0.0
  ├── commander@2.11.0
  ├─┬ connect@2.30.2
  │ ├── basic-auth-connect@1.0.0
  │ ├─┬ body-parser@1.13.3
  │ │ ├─┬ debug@2.2.0
  │ │ │ └── ms@0.7.1
  │ │ ├── iconv-lite@0.4.11
  │ │ ├─┬ on-finished@2.3.0
  │ │ │ └── ee-first@1.1.1
  │ │ └─┬ raw-body@2.1.7
  │ │   ├── bytes@2.4.0
  │ │   └── iconv-lite@0.4.13
  │ ├── bytes@2.1.0
  │ ├─┬ compression@1.5.2
  │ │ ├─┬ accepts@1.2.13
  │ │ │ └── negotiator@0.5.3
  │ │ ├─┬ compressible@2.0.12
  │ │ │ └── mime-db@1.30.0
  │ │ ├─┬ debug@2.2.0
  │ │ │ └── ms@0.7.1
  │ │ └── vary@1.0.1
  │ ├─┬ connect-timeout@1.6.2
  │ │ ├── debug@2.2.0
  │ │ └── ms@0.7.1
  │ ├── content-type@1.0.4
  │ ├── cookie@0.1.3
  │ ├── cookie-parser@1.3.5
  │ ├── cookie-signature@1.0.6
  │ ├─┬ csurf@1.8.3
  │ │ └─┬ csrf@3.0.6
  │ │   ├── rndm@1.2.0
  │ │   ├── tsscmp@1.0.5
  │ │   └─┬ uid-safe@2.1.4
  │ │     └── random-bytes@1.0.0
  │ ├─┬ debug@2.2.0
  │ │ └── ms@0.7.1
  │ ├── depd@1.0.1
  │ ├─┬ errorhandler@1.4.3
  │ │ ├─┬ accepts@1.3.4
  │ │ │ └── negotiator@0.6.1
  │ │ └── escape-html@1.0.3
  │ ├─┬ express-session@1.11.3
  │ │ ├── crc@3.3.0
  │ │ ├─┬ debug@2.2.0
  │ │ │ └── ms@0.7.1
  │ │ └─┬ uid-safe@2.0.0
  │ │   └── base64-url@1.2.1
  │ ├─┬ finalhandler@0.4.0
  │ │ ├─┬ debug@2.2.0
  │ │ │ └── ms@0.7.1
  │ │ ├── escape-html@1.0.2
  │ │ └── unpipe@1.0.0
  │ ├── fresh@0.3.0
  │ ├─┬ http-errors@1.3.1
  │ │ └── statuses@1.4.0
  │ ├─┬ method-override@2.3.10
  │ │ ├── methods@1.1.2
  │ │ └── vary@1.1.2
  │ ├─┬ morgan@1.6.1
  │ │ ├── basic-auth@1.0.4
  │ │ └─┬ debug@2.2.0
  │ │   └── ms@0.7.1
  │ ├─┬ multiparty@3.3.2
  │ │ ├─┬ readable-stream@1.1.14
  │ │ │ ├── core-util-is@1.0.2
  │ │ │ ├── isarray@0.0.1
  │ │ │ └── string_decoder@0.10.31
  │ │ └── stream-counter@0.2.0
  │ ├── on-headers@1.0.1
  │ ├── parseurl@1.3.2
  │ ├── pause@0.1.0
  │ ├── qs@4.0.0
  │ ├─┬ response-time@2.3.2
  │ │ └── depd@1.1.1
  │ ├─┬ serve-favicon@2.3.2
  │ │ ├── etag@1.7.0
  │ │ └── ms@0.7.2
  │ ├─┬ serve-index@1.7.3
  │ │ ├── batch@0.5.3
  │ │ ├─┬ debug@2.2.0
  │ │ │ └── ms@0.7.1
  │ │ └── mime-types@2.1.17
  │ ├─┬ serve-static@1.10.3
  │ │ └─┬ send@0.13.2
  │ │   ├── debug@2.2.0
  │ │   ├── depd@1.1.1
  │ │   ├── destroy@1.0.4
  │ │   ├── mime@1.3.4
  │ │   ├── ms@0.7.1
  │ │   ├── range-parser@1.0.3
  │ │   └── statuses@1.2.1
  │ ├─┬ type-is@1.6.15
  │ │ └── media-typer@0.3.0
  │ ├── utils-merge@1.0.0
  │ └── vhost@3.0.2
  ├─┬ create-react-class@15.6.2
  │ ├── loose-envify@1.3.1
  │ └── object-assign@4.1.1
  ├─┬ debug@2.6.9
  │ └── ms@2.0.0
  ├── denodeify@1.2.1
  ├─┬ envinfo@3.9.0
  │ ├─┬ copy-paste@1.3.0
  │ │ └── sync-exec@0.6.2
  │ ├─┬ os-name@2.0.1
  │ │ ├── macos-release@1.1.0
  │ │ └── win-release@1.1.1
  │ └─┬ which@1.3.0
  │   └── isexe@2.0.0
  ├── event-target-shim@1.1.1
  ├─┬ fbjs@0.8.16
  │ ├── core-js@1.2.7
  │ ├── isomorphic-fetch@2.2.1
  │ ├── setimmediate@1.0.5
  │ └── ua-parser-js@0.7.17
  ├─┬ fbjs-scripts@0.8.1
  │ ├─┬ babel-preset-fbjs@2.1.4
  │ │ ├── babel-plugin-check-es2015-constants@6.22.0
  │ │ ├── babel-plugin-syntax-jsx@6.18.0
  │ │ ├── babel-plugin-transform-es2015-arrow-functions@6.22.0
  │ │ ├── babel-plugin-transform-es2015-block-scoped-functions@6.22.0
  │ │ ├── babel-plugin-transform-es2015-block-scoping@6.26.0
  │ │ ├─┬ babel-plugin-transform-es2015-classes@6.24.1
  │ │ │ ├── babel-helper-define-map@6.26.0
  │ │ │ ├── babel-helper-optimise-call-expression@6.24.1
  │ │ │ └── babel-helper-replace-supers@6.24.1
  │ │ ├── babel-plugin-transform-es2015-computed-properties@6.24.1
  │ │ ├── babel-plugin-transform-es2015-destructuring@6.23.0
  │ │ ├── babel-plugin-transform-es2015-for-of@6.23.0
  │ │ ├── babel-plugin-transform-es2015-function-name@6.24.1
  │ │ ├── babel-plugin-transform-es2015-literals@6.22.0
  │ │ ├─┬ babel-plugin-transform-es2015-modules-commonjs@6.26.0
  │ │ │ └── babel-plugin-transform-strict-mode@6.24.1
  │ │ ├── babel-plugin-transform-es2015-object-super@6.24.1
  │ │ ├─┬ babel-plugin-transform-es2015-parameters@6.24.1
  │ │ │ └─┬ babel-helper-call-delegate@6.24.1
  │ │ │   └── babel-helper-hoist-variables@6.24.1
  │ │ ├── babel-plugin-transform-es2015-shorthand-properties@6.24.1
  │ │ ├── babel-plugin-transform-es2015-spread@6.22.0
  │ │ ├── babel-plugin-transform-es2015-template-literals@6.22.0
  │ │ ├── babel-plugin-transform-es3-member-expression-literals@6.22.0
  │ │ ├── babel-plugin-transform-es3-property-literals@6.22.0
  │ │ ├── babel-plugin-transform-react-display-name@6.25.0
  │ │ └─┬ babel-plugin-transform-react-jsx@6.24.1
  │ │   └── babel-helper-builder-react-jsx@6.26.0
  │ ├─┬ cross-spawn@5.1.0
  │ │ ├─┬ lru-cache@4.1.1
  │ │ │ ├── pseudomap@1.0.2
  │ │ │ └── yallist@2.1.2
  │ │ └─┬ shebang-command@1.2.0
  │ │   └── shebang-regex@1.0.0
  │ ├─┬ gulp-util@3.0.8
  │ │ ├── array-differ@1.0.0
  │ │ ├── array-uniq@1.0.3
  │ │ ├── beeper@1.1.1
  │ │ ├── dateformat@2.2.0
  │ │ ├─┬ fancy-log@1.3.0
  │ │ │ └── time-stamp@1.1.0
  │ │ ├─┬ gulplog@1.0.0
  │ │ │ └── glogg@1.0.0
  │ │ ├─┬ has-gulplog@0.1.0
  │ │ │ └── sparkles@1.0.0
  │ │ ├── lodash._reescape@3.0.0
  │ │ ├── lodash._reevaluate@3.0.0
  │ │ ├── lodash._reinterpolate@3.0.0
  │ │ ├─┬ lodash.template@3.6.2
  │ │ │ ├── lodash._basecopy@3.0.1
  │ │ │ ├── lodash._basetostring@3.0.1
  │ │ │ ├── lodash._basevalues@3.0.0
  │ │ │ ├── lodash._isiterateecall@3.0.9
  │ │ │ ├─┬ lodash.escape@3.2.0
  │ │ │ │ └── lodash._root@3.0.1
  │ │ │ ├─┬ lodash.keys@3.1.2
  │ │ │ │ ├── lodash._getnative@3.9.1
  │ │ │ │ ├── lodash.isarguments@3.1.0
  │ │ │ │ └── lodash.isarray@3.0.4
  │ │ │ ├── lodash.restparam@3.6.1
  │ │ │ └── lodash.templatesettings@3.1.1
  │ │ ├─┬ multipipe@0.1.2
  │ │ │ └── duplexer2@0.0.2
  │ │ ├── object-assign@3.0.0
  │ │ ├── replace-ext@0.0.1
  │ │ └─┬ vinyl@0.5.3
  │ │   ├── clone@1.0.3
  │ │   └── clone-stats@0.0.1
  │ └─┬ through2@2.0.3
  │   ├─┬ readable-stream@2.3.3
  │   │ ├── isarray@1.0.0
  │   │ ├── process-nextick-args@1.0.7
  │   │ └── string_decoder@1.0.3
  │   └── xtend@4.0.1
  ├─┬ fs-extra@1.0.0
  │ ├── jsonfile@2.4.0
  │ └── klaw@1.3.1
  ├─┬ glob@7.1.2
  │ ├── fs.realpath@1.0.0
  │ ├─┬ inflight@1.0.6
  │ │ └── wrappy@1.0.2
  │ ├── inherits@2.0.3
  │ └── once@1.4.0
  ├── graceful-fs@4.1.11
  ├─┬ inquirer@3.3.0
  │ ├── ansi-escapes@3.0.0
  │ ├─┬ chalk@2.3.0
  │ │ ├─┬ ansi-styles@3.2.0
  │ │ │ └─┬ color-convert@1.9.1
  │ │ │   └── color-name@1.1.3
  │ │ └─┬ supports-color@4.5.0
  │ │   └── has-flag@2.0.0
  │ ├─┬ cli-cursor@2.1.0
  │ │ └─┬ restore-cursor@2.0.0
  │ │   ├── onetime@2.0.1
  │ │   └── signal-exit@3.0.2
  │ ├── cli-width@2.2.0
  │ ├─┬ external-editor@2.0.5
  │ │ ├── iconv-lite@0.4.19
  │ │ ├── jschardet@1.6.0
  │ │ └── tmp@0.0.33
  │ ├── figures@2.0.0
  │ ├── mute-stream@0.0.7
  │ ├─┬ run-async@2.3.0
  │ │ └── is-promise@2.1.0
  │ ├── rx-lite@4.0.8
  │ ├── rx-lite-aggregates@4.0.8
  │ ├─┬ string-width@2.1.1
  │ │ ├── is-fullwidth-code-point@2.0.0
  │ │ └─┬ strip-ansi@4.0.0
  │ │   └── ansi-regex@3.0.0
  │ ├─┬ strip-ansi@4.0.0
  │ │ └── ansi-regex@3.0.0
  │ └── through@2.3.8
  ├── lodash@4.17.4
  ├─┬ metro-bundler@0.20.3
  │ ├── async@2.6.0
  │ ├── babel-plugin-external-helpers@6.22.0
  │ ├─┬ babel-preset-es2015-node@6.1.1
  │ │ ├─┬ babel-plugin-transform-es2015-sticky-regex@6.24.1
  │ │ │ └── babel-helper-regex@6.26.0
  │ │ └─┬ babel-plugin-transform-es2015-unicode-regex@6.24.1
  │ │   └─┬ regexpu-core@2.0.0
  │ │     ├── regenerate@1.3.3
  │ │     ├── regjsgen@0.2.0
  │ │     └─┬ regjsparser@0.1.5
  │ │       └── jsesc@0.5.0
  │ ├─┬ babel-preset-react-native@4.0.0
  │ │ ├── babel-plugin-react-transform@3.0.0
  │ │ ├── babel-plugin-syntax-dynamic-import@6.18.0
  │ │ ├── babel-plugin-transform-object-assign@6.22.0
  │ │ ├── babel-plugin-transform-react-jsx-source@6.22.0
  │ │ ├─┬ babel-plugin-transform-regenerator@6.26.0
  │ │ │ └── regenerator-transform@0.10.1
  │ │ └─┬ react-transform-hmr@1.0.4
  │ │   ├─┬ global@4.3.2
  │ │   │ ├─┬ min-document@2.19.0
  │ │   │ │ └── dom-walk@0.1.1
  │ │   │ └── process@0.5.2
  │ │   └─┬ react-proxy@1.1.8
  │ │     └── react-deep-force-update@1.1.1
  │ ├─┬ concat-stream@1.6.0
  │ │ ├─┬ readable-stream@2.3.3
  │ │ │ ├── isarray@1.0.0
  │ │ │ └── string_decoder@1.0.3
  │ │ └── typedarray@0.0.6
  │ ├── image-size@0.6.1
  │ ├── jest-docblock@21.2.0
  │ ├─┬ jest-haste-map@21.2.0
  │ │ ├─┬ fb-watchman@2.0.0
  │ │ │ └─┬ bser@2.0.0
  │ │ │   └── node-int64@0.4.0
  │ │ ├─┬ micromatch@2.3.11
  │ │ │ ├─┬ arr-diff@2.0.0
  │ │ │ │ └── arr-flatten@1.1.0
  │ │ │ ├── array-unique@0.2.1
  │ │ │ ├─┬ braces@1.8.5
  │ │ │ │ ├─┬ expand-range@1.8.2
  │ │ │ │ │ └─┬ fill-range@2.2.3
  │ │ │ │ │   ├── is-number@2.1.0
  │ │ │ │ │   ├─┬ isobject@2.1.0
  │ │ │ │ │   │ └── isarray@1.0.0
  │ │ │ │ │   ├─┬ randomatic@1.1.7
  │ │ │ │ │   │ ├─┬ is-number@3.0.0
  │ │ │ │ │   │ │ └── kind-of@3.2.2
  │ │ │ │ │   │ └── kind-of@4.0.0
  │ │ │ │ │   └── repeat-string@1.6.1
  │ │ │ │ ├── preserve@0.2.0
  │ │ │ │ └── repeat-element@1.1.2
  │ │ │ ├─┬ expand-brackets@0.1.5
  │ │ │ │ └── is-posix-bracket@0.1.1
  │ │ │ ├── extglob@0.3.2
  │ │ │ ├── filename-regex@2.0.1
  │ │ │ ├── is-extglob@1.0.0
  │ │ │ ├── is-glob@2.0.1
  │ │ │ ├─┬ kind-of@3.2.2
  │ │ │ │ └── is-buffer@1.1.6
  │ │ │ ├─┬ normalize-path@2.1.1
  │ │ │ │ └── remove-trailing-separator@1.1.0
  │ │ │ ├─┬ object.omit@2.0.1
  │ │ │ │ ├─┬ for-own@0.1.5
  │ │ │ │ │ └── for-in@1.0.2
  │ │ │ │ └── is-extendable@0.1.1
  │ │ │ ├─┬ parse-glob@3.0.4
  │ │ │ │ ├─┬ glob-base@0.3.0
  │ │ │ │ │ └── glob-parent@2.0.0
  │ │ │ │ └── is-dotfile@1.0.3
  │ │ │ └─┬ regex-cache@0.4.4
  │ │ │   └─┬ is-equal-shallow@0.1.3
  │ │ │     └── is-primitive@2.0.0
  │ │ ├─┬ sane@2.2.0
  │ │ │ ├── anymatch@1.3.2
  │ │ │ ├─┬ exec-sh@0.2.1
  │ │ │ │ └── merge@1.2.0
  │ │ │ ├─┬ fsevents@1.1.3
  │ │ │ │ ├── nan@2.7.0
  │ │ │ │ └─┬ node-pre-gyp@0.6.39
  │ │ │ │   ├── detect-libc@1.0.2
  │ │ │ │   ├─┬ hawk@3.1.3
  │ │ │ │   │ ├── boom@2.10.1
  │ │ │ │   │ ├── cryptiles@2.0.5
  │ │ │ │   │ ├── hoek@2.16.3
  │ │ │ │   │ └── sntp@1.0.9
  │ │ │ │   ├─┬ mkdirp@0.5.1
  │ │ │ │   │ └── minimist@0.0.8
  │ │ │ │   ├─┬ nopt@4.0.1
  │ │ │ │   │ ├── abbrev@1.1.0
  │ │ │ │   │ └─┬ osenv@0.1.4
  │ │ │ │   │   ├── os-homedir@1.0.2
  │ │ │ │   │   └── os-tmpdir@1.0.2
  │ │ │ │   ├─┬ npmlog@4.1.0
  │ │ │ │   │ ├─┬ are-we-there-yet@1.1.4
  │ │ │ │   │ │ └── delegates@1.0.0
  │ │ │ │   │ ├── console-control-strings@1.1.0
  │ │ │ │   │ ├─┬ gauge@2.7.4
  │ │ │ │   │ │ ├── aproba@1.1.1
  │ │ │ │   │ │ ├── has-unicode@2.0.1
  │ │ │ │   │ │ ├── object-assign@4.1.1
  │ │ │ │   │ │ ├── signal-exit@3.0.2
  │ │ │ │   │ │ ├─┬ string-width@1.0.2
  │ │ │ │   │ │ │ ├── code-point-at@1.1.0
  │ │ │ │   │ │ │ └─┬ is-fullwidth-code-point@1.0.0
  │ │ │ │   │ │ │   └── number-is-nan@1.0.1
  │ │ │ │   │ │ ├─┬ strip-ansi@3.0.1
  │ │ │ │   │ │ │ └── ansi-regex@2.1.1
  │ │ │ │   │ │ └── wide-align@1.1.2
  │ │ │ │   │ └── set-blocking@2.0.0
  │ │ │ │   ├─┬ rc@1.2.1
  │ │ │ │   │ ├── deep-extend@0.4.2
  │ │ │ │   │ ├── ini@1.3.4
  │ │ │ │   │ ├── minimist@1.2.0
  │ │ │ │   │ └── strip-json-comments@2.0.1
  │ │ │ │   ├─┬ request@2.81.0
  │ │ │ │   │ ├── aws-sign2@0.6.0
  │ │ │ │   │ ├── aws4@1.6.0
  │ │ │ │   │ ├── caseless@0.12.0
  │ │ │ │   │ ├─┬ combined-stream@1.0.5
  │ │ │ │   │ │ └── delayed-stream@1.0.0
  │ │ │ │   │ ├── extend@3.0.1
  │ │ │ │   │ ├── forever-agent@0.6.1
  │ │ │ │   │ ├─┬ form-data@2.1.4
  │ │ │ │   │ │ └── asynckit@0.4.0
  │ │ │ │   │ ├─┬ har-validator@4.2.1
  │ │ │ │   │ │ ├─┬ ajv@4.11.8
  │ │ │ │   │ │ │ ├── co@4.6.0
  │ │ │ │   │ │ │ └─┬ json-stable-stringify@1.0.1
  │ │ │ │   │ │ │   └── jsonify@0.0.0
  │ │ │ │   │ │ └── har-schema@1.0.5
  │ │ │ │   │ ├─┬ http-signature@1.1.1
  │ │ │ │   │ │ ├── assert-plus@0.2.0
  │ │ │ │   │ │ ├─┬ jsprim@1.4.0
  │ │ │ │   │ │ │ ├── assert-plus@1.0.0
  │ │ │ │   │ │ │ ├── extsprintf@1.0.2
  │ │ │ │   │ │ │ ├── json-schema@0.2.3
  │ │ │ │   │ │ │ └── verror@1.3.6
  │ │ │ │   │ │ └─┬ sshpk@1.13.0
  │ │ │ │   │ │   ├── asn1@0.2.3
  │ │ │ │   │ │   ├── assert-plus@1.0.0
  │ │ │ │   │ │   ├── bcrypt-pbkdf@1.0.1
  │ │ │ │   │ │   ├─┬ dashdash@1.14.1
  │ │ │ │   │ │   │ └── assert-plus@1.0.0
  │ │ │ │   │ │   ├── ecc-jsbn@0.1.1
  │ │ │ │   │ │   ├─┬ getpass@0.1.7
  │ │ │ │   │ │   │ └── assert-plus@1.0.0
  │ │ │ │   │ │   ├── jodid25519@1.0.2
  │ │ │ │   │ │   ├── jsbn@0.1.1
  │ │ │ │   │ │   └── tweetnacl@0.14.5
  │ │ │ │   │ ├── is-typedarray@1.0.0
  │ │ │ │   │ ├── isstream@0.1.2
  │ │ │ │   │ ├── json-stringify-safe@5.0.1
  │ │ │ │   │ ├─┬ mime-types@2.1.15
  │ │ │ │   │ │ └── mime-db@1.27.0
  │ │ │ │   │ ├── oauth-sign@0.8.2
  │ │ │ │   │ ├── performance-now@0.2.0
  │ │ │ │   │ ├── qs@6.4.0
  │ │ │ │   │ ├── safe-buffer@5.0.1
  │ │ │ │   │ ├── stringstream@0.0.5
  │ │ │ │   │ ├─┬ tough-cookie@2.3.2
  │ │ │ │   │ │ └── punycode@1.4.1
  │ │ │ │   │ ├── tunnel-agent@0.6.0
  │ │ │ │   │ └── uuid@3.0.1
  │ │ │ │   ├─┬ rimraf@2.6.1
  │ │ │ │   │ └─┬ glob@7.1.2
  │ │ │ │   │   ├── fs.realpath@1.0.0
  │ │ │ │   │   ├── inflight@1.0.6
  │ │ │ │   │   ├─┬ minimatch@3.0.4
  │ │ │ │   │   │ └─┬ brace-expansion@1.1.7
  │ │ │ │   │   │   ├── balanced-match@0.4.2
  │ │ │ │   │   │   └── concat-map@0.0.1
  │ │ │ │   │   └── path-is-absolute@1.0.1
  │ │ │ │   ├── semver@5.3.0
  │ │ │ │   ├─┬ tar@2.2.1
  │ │ │ │   │ ├── block-stream@0.0.9
  │ │ │ │   │ ├─┬ fstream@1.0.11
  │ │ │ │   │ │ └── graceful-fs@4.1.11
  │ │ │ │   │ └── inherits@2.0.3
  │ │ │ │   └─┬ tar-pack@3.4.0
  │ │ │ │     ├─┬ debug@2.6.8
  │ │ │ │     │ └── ms@2.0.0
  │ │ │ │     ├── fstream-ignore@1.0.5
  │ │ │ │     ├─┬ once@1.4.0
  │ │ │ │     │ └── wrappy@1.0.2
  │ │ │ │     ├─┬ readable-stream@2.2.9
  │ │ │ │     │ ├── buffer-shims@1.0.0
  │ │ │ │     │ ├── core-util-is@1.0.2
  │ │ │ │     │ ├── isarray@1.0.0
  │ │ │ │     │ ├── process-nextick-args@1.0.7
  │ │ │ │     │ ├── string_decoder@1.0.1
  │ │ │ │     │ └── util-deprecate@1.0.2
  │ │ │ │     └── uid-number@0.0.6
  │ │ │ ├─┬ walker@1.0.7
  │ │ │ │ └─┬ makeerror@1.0.11
  │ │ │ │   └── tmpl@1.0.4
  │ │ │ └── watch@0.18.0
  │ │ └─┬ worker-farm@1.5.1
  │ │   └─┬ errno@0.1.4
  │ │     └── prr@0.0.0
  │ ├── json-stable-stringify@1.0.1
  │ ├── json5@0.4.0
  │ ├── left-pad@1.1.3
  │ ├─┬ merge-stream@1.0.1
  │ │ └─┬ readable-stream@2.3.3
  │ │   ├── isarray@1.0.0
  │ │   └── string_decoder@1.0.3
  │ ├─┬ mime-types@2.1.11
  │ │ └── mime-db@1.23.0
  │ ├─┬ request@2.83.0
  │ │ ├── aws-sign2@0.7.0
  │ │ ├── aws4@1.6.0
  │ │ ├── caseless@0.12.0
  │ │ ├─┬ combined-stream@1.0.5
  │ │ │ └── delayed-stream@1.0.0
  │ │ ├── extend@3.0.1
  │ │ ├── forever-agent@0.6.1
  │ │ ├─┬ form-data@2.3.1
  │ │ │ └── asynckit@0.4.0
  │ │ ├─┬ har-validator@5.0.3
  │ │ │ ├─┬ ajv@5.3.0
  │ │ │ │ ├── co@4.6.0
  │ │ │ │ ├── fast-deep-equal@1.0.0
  │ │ │ │ ├── fast-json-stable-stringify@2.0.0
  │ │ │ │ └── json-schema-traverse@0.3.1
  │ │ │ └── har-schema@2.0.0
  │ │ ├─┬ hawk@6.0.2
  │ │ │ ├── boom@4.3.1
  │ │ │ ├─┬ cryptiles@3.1.2
  │ │ │ │ └── boom@5.2.0
  │ │ │ ├── hoek@4.2.0
  │ │ │ └── sntp@2.1.0
  │ │ ├─┬ http-signature@1.2.0
  │ │ │ ├── assert-plus@1.0.0
  │ │ │ ├─┬ jsprim@1.4.1
  │ │ │ │ ├── extsprintf@1.3.0
  │ │ │ │ ├── json-schema@0.2.3
  │ │ │ │ └── verror@1.10.0
  │ │ │ └─┬ sshpk@1.13.1
  │ │ │   ├── asn1@0.2.3
  │ │ │   ├── bcrypt-pbkdf@1.0.1
  │ │ │   ├── dashdash@1.14.1
  │ │ │   ├── ecc-jsbn@0.1.1
  │ │ │   ├── getpass@0.1.7
  │ │ │   ├── jsbn@0.1.1
  │ │ │   └── tweetnacl@0.14.5
  │ │ ├── is-typedarray@1.0.0
  │ │ ├── isstream@0.1.2
  │ │ ├── json-stringify-safe@5.0.1
  │ │ ├── oauth-sign@0.8.2
  │ │ ├── performance-now@2.1.0
  │ │ ├── qs@6.5.1
  │ │ ├── safe-buffer@5.1.1
  │ │ ├── stringstream@0.0.5
  │ │ ├─┬ tough-cookie@2.3.3
  │ │ │ └── punycode@1.4.1
  │ │ ├── tunnel-agent@0.6.0
  │ │ └── uuid@3.1.0
  │ ├─┬ temp@0.8.3
  │ │ └── rimraf@2.2.8
  │ ├── throat@4.1.0
  │ ├─┬ uglify-es@3.1.9
  │ │ └── source-map@0.6.1
  │ ├── wordwrap@1.0.0
  │ ├─┬ write-file-atomic@1.3.4
  │ │ ├── imurmurhash@0.1.4
  │ │ └── slide@1.1.6
  │ └── xpipe@1.0.5
  ├── mime@1.4.1
  ├── minimist@1.2.0
  ├─┬ mkdirp@0.5.1
  │ └── minimist@0.0.8
  ├─┬ node-fetch@1.7.3
  │ ├─┬ encoding@0.1.12
  │ │ └── iconv-lite@0.4.19
  │ └── is-stream@1.1.0
  ├─┬ node-notifier@5.1.2
  │ ├── growly@1.3.0
  │ └── shellwords@0.1.1
  ├─┬ npmlog@2.0.4
  │ ├── ansi@0.3.1
  │ ├─┬ are-we-there-yet@1.1.4
  │ │ ├── delegates@1.0.0
  │ │ └─┬ readable-stream@2.3.3
  │ │   ├── isarray@1.0.0
  │ │   └── string_decoder@1.0.3
  │ └─┬ gauge@1.2.7
  │   ├── has-unicode@2.0.1
  │   ├── lodash.pad@4.5.1
  │   ├── lodash.padend@4.6.1
  │   └── lodash.padstart@4.6.1
  ├── opn@3.0.3
  ├─┬ optimist@0.6.1
  │ ├── minimist@0.0.10
  │ └── wordwrap@0.0.3
  ├─┬ plist@1.2.0
  │ ├── base64-js@0.0.8
  │ ├── util-deprecate@1.0.2
  │ ├─┬ xmlbuilder@4.0.0
  │ │ └── lodash@3.10.1
  │ └── xmldom@0.1.27
  ├── pretty-format@4.3.1
  ├─┬ promise@7.3.1
  │ └── asap@2.0.6
  ├── prop-types@15.6.0
  ├── react-clone-referenced-element@1.0.1
  ├─┬ react-devtools-core@2.5.2
  │ └─┬ ws@2.3.1
  │   ├── safe-buffer@5.0.1
  │   └── ultron@1.1.0
  ├── react-timer-mixin@0.13.3
  ├── regenerator-runtime@0.9.6
  ├── rimraf@2.6.2
  ├── semver@5.4.1
  ├─┬ shell-quote@1.6.1
  │ ├── array-filter@0.0.1
  │ ├── array-map@0.0.0
  │ ├── array-reduce@0.0.0
  │ └── jsonify@0.0.0
  ├── stacktrace-parser@0.1.4
  ├── whatwg-fetch@1.1.1
  ├─┬ ws@1.1.5
  │ ├── options@0.0.6
  │ └── ultron@1.0.2
  ├─┬ xcode@0.9.3
  │ ├── pegjs@0.10.0
  │ ├─┬ simple-plist@0.2.1
  │ │ ├─┬ bplist-creator@0.0.7
  │ │ │ └── stream-buffers@2.2.0
  │ │ ├─┬ bplist-parser@0.1.1
  │ │ │ └── big-integer@1.6.25
  │ │ └─┬ plist@2.0.1
  │ │   ├── base64-js@1.1.2
  │ │   └── xmlbuilder@8.2.2
  │ └── uuid@3.0.1
  ├─┬ xmldoc@0.4.0
  │ └── sax@1.1.6
  └─┬ yargs@9.0.1
    ├── camelcase@4.1.0
    ├─┬ cliui@3.2.0
    │ ├─┬ string-width@1.0.2
    │ │ ├── code-point-at@1.1.0
    │ │ └─┬ is-fullwidth-code-point@1.0.0
    │ │   └── number-is-nan@1.0.1
    │ └─┬ wrap-ansi@2.1.0
    │   └─┬ string-width@1.0.2
    │     └── is-fullwidth-code-point@1.0.0
    ├── decamelize@1.2.0
    ├── get-caller-file@1.0.2
    ├─┬ os-locale@2.1.0
    │ ├─┬ execa@0.7.0
    │ │ ├── get-stream@3.0.0
    │ │ ├─┬ npm-run-path@2.0.2
    │ │ │ └── path-key@2.0.1
    │ │ ├── p-finally@1.0.0
    │ │ └── strip-eof@1.0.0
    │ ├─┬ lcid@1.0.0
    │ │ └── invert-kv@1.0.0
    │ └─┬ mem@1.1.0
    │   └── mimic-fn@1.1.0
    ├─┬ read-pkg-up@2.0.0
    │ ├─┬ find-up@2.1.0
    │ │ └─┬ locate-path@2.0.0
    │ │   ├─┬ p-locate@2.0.0
    │ │   │ └── p-limit@1.1.0
    │ │   └── path-exists@3.0.0
    │ └─┬ read-pkg@2.0.0
    │   ├─┬ load-json-file@2.0.0
    │   │ ├─┬ parse-json@2.2.0
    │   │ │ └─┬ error-ex@1.3.1
    │   │ │   └── is-arrayish@0.2.1
    │   │ ├── pify@2.3.0
    │   │ └── strip-bom@3.0.0
    │   ├─┬ normalize-package-data@2.4.0
    │   │ ├── hosted-git-info@2.5.0
    │   │ ├─┬ is-builtin-module@1.0.0
    │   │ │ └── builtin-modules@1.1.1
    │   │ └─┬ validate-npm-package-license@3.0.1
    │   │   ├─┬ spdx-correct@1.0.2
    │   │   │ └── spdx-license-ids@1.2.2
    │   │   └── spdx-expression-parse@1.0.4
    │   └── path-type@2.0.0
    ├── require-directory@2.1.1
    ├── require-main-filename@1.0.1
    ├── set-blocking@2.0.0
    ├── which-module@2.0.0
    ├── y18n@3.2.1
    └── yargs-parser@7.0.0

npm WARN react-native@0.50.3 requires a peer of react@16.0.0 but none was installed.
Setting up new React Native app in /Users/manojmaduri/Documents/react-app/ReactApp
Installing React...
ReactApp@0.0.1 /Users/manojmaduri/Documents/react-app/ReactApp
└── react@16.0.0

Installing Jest...
ReactApp@0.0.1 /Users/manojmaduri/Documents/react-app/ReactApp
├─┬ babel-jest@21.2.0
│ ├─┬ babel-plugin-istanbul@4.1.5
│ │ ├── istanbul-lib-instrument@1.9.1
│ │ └─┬ test-exclude@4.1.1
│ │   ├── arrify@1.0.1
│ │   └─┬ read-pkg-up@1.0.1
│ │     ├─┬ find-up@1.1.2
│ │     │ ├── path-exists@2.1.0
│ │     │ └─┬ pinkie-promise@2.0.1
│ │     │   └── pinkie@2.0.4
│ │     └─┬ read-pkg@1.1.0
│ │       ├─┬ load-json-file@1.1.0
│ │       │ └─┬ strip-bom@2.0.0
│ │       │   └── is-utf8@0.2.1
│ │       └── path-type@1.1.0
│ └─┬ babel-preset-jest@21.2.0
│   └── babel-plugin-jest-hoist@21.2.0
├── babel-preset-react-native@4.0.0
├─┬ jest@21.2.1
│ └─┬ jest-cli@21.2.1
│   ├─┬ chalk@2.3.0
│   │ ├── ansi-styles@3.2.0
│   │ └── supports-color@4.5.0
│   ├─┬ is-ci@1.0.10
│   │ └── ci-info@1.1.1
│   ├─┬ istanbul-api@1.2.1
│   │ ├── fileset@2.0.3
│   │ ├─┬ istanbul-lib-hook@1.1.0
│   │ │ └─┬ append-transform@0.4.0
│   │ │   └─┬ default-require-extensions@1.0.0
│   │ │     └── strip-bom@2.0.0
│   │ ├─┬ istanbul-lib-report@1.1.2
│   │ │ ├── path-parse@1.0.5
│   │ │ └─┬ supports-color@3.2.3
│   │ │   └── has-flag@1.0.0
│   │ ├─┬ istanbul-reports@1.1.3
│   │ │ └─┬ handlebars@4.0.11
│   │ │   ├── async@1.5.2
│   │ │   ├─┬ source-map@0.4.4
│   │ │   │ └── amdefine@1.0.1
│   │ │   └─┬ uglify-js@2.8.29
│   │ │     ├── source-map@0.5.7
│   │ │     ├── uglify-to-browserify@1.0.2
│   │ │     └─┬ yargs@3.10.0
│   │ │       ├── camelcase@1.2.1
│   │ │       ├─┬ cliui@2.1.0
│   │ │       │ ├─┬ center-align@0.1.3
│   │ │       │ │ ├─┬ align-text@0.1.4
│   │ │       │ │ │ └── longest@1.0.1
│   │ │       │ │ └── lazy-cache@1.0.4
│   │ │       │ ├── right-align@0.1.3
│   │ │       │ └── wordwrap@0.0.2
│   │ │       └── window-size@0.1.0
│   │ └─┬ js-yaml@3.10.0
│   │   ├─┬ argparse@1.0.9
│   │   │ └── sprintf-js@1.0.3
│   │   └── esprima@4.0.0
│   ├── istanbul-lib-coverage@1.1.1
│   ├─┬ istanbul-lib-source-maps@1.2.2
│   │ └── debug@3.1.0
│   ├── jest-changed-files@21.2.0
│   ├─┬ jest-config@21.2.1
│   │ ├─┬ chalk@2.3.0
│   │ │ ├── ansi-styles@3.2.0
│   │ │ └── supports-color@4.5.0
│   │ ├── jest-environment-node@21.2.1
│   │ ├── jest-get-type@21.2.0
│   │ ├─┬ jest-jasmine2@21.2.1
│   │ │ ├─┬ chalk@2.3.0
│   │ │ │ ├── ansi-styles@3.2.0
│   │ │ │ └── supports-color@4.5.0
│   │ │ ├─┬ expect@21.2.1
│   │ │ │ └── ansi-styles@3.2.0
│   │ │ └── p-cancelable@0.3.0
│   │ ├─┬ jest-resolve@21.2.0
│   │ │ ├─┬ browser-resolve@1.11.2
│   │ │ │ └── resolve@1.1.7
│   │ │ └─┬ chalk@2.3.0
│   │ │   ├── ansi-styles@3.2.0
│   │ │   └── supports-color@4.5.0
│   │ ├─┬ jest-validate@21.2.1
│   │ │ ├─┬ chalk@2.3.0
│   │ │ │ ├── ansi-styles@3.2.0
│   │ │ │ └── supports-color@4.5.0
│   │ │ ├── leven@2.1.0
│   │ │ └─┬ pretty-format@21.2.1
│   │ │   └── ansi-regex@3.0.0
│   │ └─┬ pretty-format@21.2.1
│   │   └── ansi-regex@3.0.0
│   ├─┬ jest-environment-jsdom@21.2.1
│   │ ├── jest-mock@21.2.0
│   │ └─┬ jsdom@9.12.0
│   │   ├── abab@1.0.4
│   │   ├── acorn@4.0.13
│   │   ├── acorn-globals@3.1.0
│   │   ├── array-equal@1.0.0
│   │   ├── content-type-parser@1.0.2
│   │   ├── cssom@0.3.2
│   │   ├── cssstyle@0.2.37
│   │   ├─┬ escodegen@1.9.0
│   │   │ ├── esprima@3.1.3
│   │   │ ├── estraverse@4.2.0
│   │   │ └─┬ optionator@0.8.2
│   │   │   ├── deep-is@0.1.3
│   │   │   ├── fast-levenshtein@2.0.6
│   │   │   ├── levn@0.3.0
│   │   │   ├── prelude-ls@1.1.2
│   │   │   └── type-check@0.3.2
│   │   ├── html-encoding-sniffer@1.0.2
│   │   ├── nwmatcher@1.4.3
│   │   ├── parse5@1.5.1
│   │   ├── sax@1.2.4
│   │   ├── symbol-tree@3.2.2
│   │   ├── webidl-conversions@4.0.2
│   │   ├─┬ whatwg-encoding@1.0.3
│   │   │ └── iconv-lite@0.4.19
│   │   ├─┬ whatwg-url@4.8.0
│   │   │ ├── tr46@0.0.3
│   │   │ └── webidl-conversions@3.0.1
│   │   └── xml-name-validator@2.0.1
│   ├─┬ jest-message-util@21.2.1
│   │ └─┬ chalk@2.3.0
│   │   ├── ansi-styles@3.2.0
│   │   └── supports-color@4.5.0
│   ├── jest-regex-util@21.2.0
│   ├── jest-resolve-dependencies@21.2.0
│   ├─┬ jest-runner@21.2.1
│   │ └── pify@3.0.0
│   ├─┬ jest-runtime@21.2.1
│   │ ├─┬ chalk@2.3.0
│   │ │ ├── ansi-styles@3.2.0
│   │ │ └── supports-color@4.5.0
│   │ └── write-file-atomic@2.3.0
│   ├─┬ jest-snapshot@21.2.1
│   │ ├─┬ chalk@2.3.0
│   │ │ ├── ansi-styles@3.2.0
│   │ │ └── supports-color@4.5.0
│   │ ├─┬ jest-diff@21.2.1
│   │ │ ├─┬ chalk@2.3.0
│   │ │ │ ├── ansi-styles@3.2.0
│   │ │ │ └── supports-color@4.5.0
│   │ │ ├── diff@3.4.0
│   │ │ └─┬ pretty-format@21.2.1
│   │ │   └── ansi-regex@3.0.0
│   │ ├─┬ jest-matcher-utils@21.2.1
│   │ │ ├─┬ chalk@2.3.0
│   │ │ │ ├── ansi-styles@3.2.0
│   │ │ │ └── supports-color@4.5.0
│   │ │ └─┬ pretty-format@21.2.1
│   │ │   └── ansi-regex@3.0.0
│   │ ├── natural-compare@1.4.0
│   │ └─┬ pretty-format@21.2.1
│   │   └── ansi-regex@3.0.0
│   ├─┬ jest-util@21.2.1
│   │ ├── callsites@2.0.0
│   │ └─┬ chalk@2.3.0
│   │   ├── ansi-styles@3.2.0
│   │   └── supports-color@4.5.0
│   ├── pify@3.0.0
│   ├─┬ string-length@2.0.0
│   │ ├── astral-regex@1.0.0
│   │ └─┬ strip-ansi@4.0.0
│   │   └── ansi-regex@3.0.0
│   └─┬ strip-ansi@4.0.0
│     └── ansi-regex@3.0.0
└── react-test-renderer@16.0.0

To run your app on iOS:
   cd /Users/manojmaduri/Documents/react-app/ReactApp
   react-native run-ios
   - or -
   Open ios/ReactApp.xcodeproj in Xcode
   Hit the Run button
To run your app on Android:
   cd /Users/manojmaduri/Documents/react-app/ReactApp
   Have an Android emulator running (quickest way to get started), or a device connected
   react-native run-android
