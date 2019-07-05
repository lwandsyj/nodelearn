{
  "name": "webpack1",    // 模块或应用名称

  "version": "1.0.0",    // 版本号

  "description": "",     // 描述

  "main": "index.js",    // 访问目录时，默认查找的文件

  // 脚本命令，使用npm run scriptskeyname 执行命令 
  
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  
  "keywords": [],        // 模块应用查找关键字
  
  "author": "",         // 作者
  
  "license": "ISC",
  
  // 开发环境依赖
 
  "devDependencies": {
    "cross-env": "^5.2.0"
  },
 
  // 生产环境依赖
 
  "dependencies": {
    "react": "^16.8.6",
    "react-dom": "^16.8.6"
  }

}