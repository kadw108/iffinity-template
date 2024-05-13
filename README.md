This is a template for games made with <a href="https://github.com/zehanort/iffinity">iffinity</a>, a Tweego-like interactive fiction engine by Sotiris Niarchos.

Needed but not included in the repository due to being build outputs:

* export/index.html
* src/meta/typeScriptMain.js

They are generated with `build`. The files in `src` are the actual source code of the final iffinity project, while the files in `script_files` get compiled by `build` into `src/meta/typeScriptMain.js`, which is loaded into the final project (as a story script).

There are two versions of `build`. The minify version minifies files and is intended to be used for "production".
