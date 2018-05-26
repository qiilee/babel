
1.npm install babel-cli -g 全局安装

2.babel test01.js --out-file output01.js  编译js文件

3.mv test01.js src  移动test01.js到src目录

4.rm -rf output01.js  删除刚刚编译生成的output01.js

5.babel src --out-dir dist   编译整个目录

  babel src --out-dir dist -w  持续监听

6.当前项目需要babel依赖的时候 npm install babel-cli --save-dev
