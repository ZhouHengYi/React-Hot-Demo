# React-Hot-Demo
# 安装相关工具
npm install -g --save-dev webpack-dev-server react-hot-loader

# 编译文件
webpack —config webpack-build.js

# 启动
webpack-dev-server —config webpack-build.js

# Node Server
node js/server.js


webpack-dev-server --hot --quiet

webpack-dev-server --content-base build/ --hot