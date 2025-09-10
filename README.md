# webpack_ast
web逆向AST自动扣webpack

Forked from <https://gitcode.net/zjq592767809/webpack_ast>

安装环境：npm install @babel/core


执行：node xxx.js(解析文件,也就是webpack_mixer.js) -l 加载器.js -m 模块1.js -m 模块2.js -o 输出.js


比如：执行`node webpack.js -l jiazaiqi.js -m mokuai.js -o target.js`生成目标js
创建一个新的js引入并执行
```
let dd = require("./target")

console.log(dd(113)());



```
