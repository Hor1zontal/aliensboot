# aliensboot

## QuickStart

### 环境安装

1. git clone --recursive https://github.com/KylinHe/aliensboot.git

2. 设置环境变量 ALIENSBOT_HOME 到仓库的根目录, PATH中添加 %ALIENSBOT_HOME%/bin

3. cd %ALIENSBOT_HOME%/bin, 执行build_toolkit.sh 或 build_toolkit.bat 

    注:这里使用的是go module方式下载依赖包 


### 使用

如果当前工程目录为  %Project%

1. 创建工程
   
   cd %Project%
   aliensboot init 工程包名
   
   目录结构说明参考wiki
   
2. 添加模块
   
   cd %Project%
   aliensboot module add 模块名
   
3. 编译
   
   cd %Project%/src/工程包名
   go build
   
   更多详细使用参考wiki
    
  
