# xminer 星河矿池专用挖矿工具


# Linux系统

## 一、 修改钱包地址:  

  找到第110行 `"user": "57Yp3AntU76LCWksPjRKkGFzdG4JVEysJUrjBr9NX48jA8iggcy6LMcYhHcfcnacWVNTXBG1qWLDFH4QcsqddegUG6E4GaM",`  将钱包地址替换成你自己的
  
## 二、修改CPU核心数  

找到第82行
   `"rx": [0, 1, 2, 3, 4, 5, 6, 7],`  根据CPU核心数修改,注意序号是从0开始算
  
  比如16核心
  `[0, 1, 2, 3, 4, 5, 6, 7，8，9，10，11, 12，13，14，15]`
  

## 三、 修改矿池地址  
  找到第109行 
   `"url": "pool.xinghe.app:5555", ` 根据自己的配置，修改矿池端口，
   
  ` 1、家用电脑的CPU建议使用3333端口`
  
   `2、服务器级的CPU建议使用5555端口`
   
   `3、高配服务器CPU建议使用7777端口`

  3333：初始难度 5000  
  5555：初始难度 25000
  7777：初始难度 500000
  

## 四、启动挖矿程序
给执行权限
  `sudo chmod +x xminer`
运行xminer  
 `sudo ./xminer -c config.json`

# Windows系统

## 一、 修改钱包地址:  

  找到第110行 `"user": "57Yp3AntU76LCWksPjRKkGFzdG4JVEysJUrjBr9NX48jA8iggcy6LMcYhHcfcnacWVNTXBG1qWLDFH4QcsqddegUG6E4GaM",`  将钱包地址替换成你自己的
  
## 二、修改CPU核心数  

找到第82行
   `"rx": [0, 1, 2, 3, 4, 5, 6, 7],`  根据CPU核心数修改,注意序号是从0开始算
   
  比如16核心
  `[0, 1, 2, 3, 4, 5, 6, 7，8，9，10，11, 12，13，14，15]`
  

## 三、 修改矿池地址  
  找到第109行 
  ` "url": "pool.xinghe.app:5555",`  根据自己的配置，修改矿池端口，
  
   1、家用电脑的CPU建议使用3333端口
   2、服务器级的CPU建议使用5555端口
   3、高配服务器CPU建议使用7777端口
   

  `3333：初始难度 5000  `
  
  `5555：初始难度 25000`
  
  `7777：初始难度 500000`
  

## 四、启动挖矿程序

右键->以管理员运行 `start_xminer.bat`

## 五、帮助

矿池地址: https://xinghe.app
