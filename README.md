一、开发环境
Git 环境
Node.js 运行环境，最好是 v8.x 以上版本，建议使用 nvm 来安装；
Mac 下的 iTerm，或者 Windows 下的 cmder
VSCode
编译工具 solc(yarn add solc@0.4.24)
Infura节点接口工具
二、目录结构
contracts 目录存放合约源代码，
scripts 目录存放我们的编译、部署脚本，
complied 目录存放编译结果，
tests 目录存放单元测试。
三、注意事项
切换测试网络的时候，需保证账户余额不能为0，否侧程序运行报错