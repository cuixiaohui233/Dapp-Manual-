# Dapp-Manual

今天在 windows 上搞一下，mac 上的有问题啊啊啊... 

咳咳，快开始吧!npm install npm run build 开玩笑hhh

以下文章纯属原创，感谢网易云音乐、酷狗音乐的大力支持，特贡献音乐付费包APP各一个。

### 直接安装

新建一个空的文件夹，注意一定要是空的，连个 READEME 都不能有

一言不合就 `npm install -g truffle `

`truffle init` 初始化项目，盐后你可以看到：

![image](https://github.com/cuixiaohui233/Dapp-Manual-/blob/master/git-image/success.PNG)

### 此时的项目结构

![image](https://github.com/cuixiaohui233/Dapp-Manual-/blob/master/git-image/catalog.png)

`contracts 这个文件里面都是你写的智能合约，都是 .sol 文件，里面的语法是 solidity，这个也得学...`

`git-image 这是存图片的文件夹`

`migrations 这是 我也不知道是啥...`

### 编译智能合约

`truffle compile contracts/Migrations.sol` 

编译完成如下图：

电脑太卡，自己脑补。


这个编译完成之后会形成一个build/contracts/Migrations.json 文件，供前端使用

### 前端调用

如果用 truffle unbox 会形成一个src文件，那个里面就是前端代码，但是这个项目是手动的，所以，自己搞个 create-react-app 进来,然后，调用的库，用的是 web3，详细调用代码请见 https://github.com/cuixiaohui233/solidity-learn 当然了，现在还是空的...


