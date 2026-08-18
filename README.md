# deepseek-桌宠V0.1版本
桌面虚拟宠物-如何自定义
找到asseets文件夹，替换里面枣片即可完成替换，照片要求必须是pet.png文件
开始步骤
第一步：创建项目，1. 安装 Node.js 2.确认打开 CMD：  node -v   npm -v  能看到版本就可以。
第二步：创建文件夹1.例如：D:\MyDeskPet 2.CMD进入（D:\MyDeskPet）刚刚创建的目录下，输入：npm init -y   3.安装 Electron：npm install electron --save-dev
第三步：项目结构
创建：
MyDeskPet                                                                                               
│
├── package.json
├── main.js
├── index.html
├── style.css
├── renderer.js
│
└── assets
    └── pet.png
 图片保存：
assets/pet.png   
修改 package.json
创建main.js文件
index.html文件
style.css
renderer.js
运行：CMD：npm start（在创建的目录下进行运行）
#素材来源于网络，照片仅作示范
