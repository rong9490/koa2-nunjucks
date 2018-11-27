## 使用koa-generator构建koa2项目
## 指定使用nunjucks模板引擎（默认是jade）
    koa2 koa2_project --nunjucks --git
    npm install
    npm start
## 安装eslint
    npm install eslint --save-dev
    npm install eslint-config-standard eslint-plugin-standard eslint-plugin-promise
    eslint --init
    配置.eslintrc.js 和 public-eslintrc.js
    执行 eslint ./app.js (--fix)
    