## 0.4.0 (6.1.2015)

- Removed deprecated js-import task
- Added packaging-ns which provides download-task to be used when creating
  new cljsjs libraries.

## 0.3.1 (5.1.2015)

- Main namespace is now `cljsjs.boot-cljsjs`
- Removed `:package` flag
  - It's responsibility of other tasks to add files to resource set if needed.
  - E.g. boot-cljs should add .inc.js files to resource set when doing `:optimizations :none` build.
