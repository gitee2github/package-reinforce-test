# package-reinforce-test

## 介绍
此仓库提供重要软件包加强测试的源代码

## 软件架构
软件架构说明

├── README.en.md
├── README.md
├── License
│   └── LICENSE
├── suite2cases
└── testcases

## 使用说明
openEuler社区作为一个集成社区，发布了上千个软件包；为更好地保障各软件包提供的能力能够满足用户使用，除依赖原生上游社区的测试能力，还需进行更深层更广的测试。从系统影响程度和用户使用场景角度出发，选取重要软件包进行测试加强活动。

具体实施策略如下：

- 分析软件包提供的功能/用户使用场景/软件包发布的命令及参数/提供的服务/包使用系统资源等方面
- 进行测试设计，如功能类/性能类/可靠性类等
- 根据测试设计编写测试代码
- 提交PR到本仓库
- maintainer评审合入PR

## 参与贡献
1. Fork 本仓库
2. 在suite2cases目录的制定文件中定义测试套和测试用例对应关系
3. 在testcases目录下编写测试代码
4. 下载[mugen](https://gitee.com/openeuler/test-tools.git)测试框架并完成代码调试
5. 本地提交代码
6. 码云新建 Pull Request


#### 码云特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  码云官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解码云上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是码云最有价值开源项目，是码云综合评定出的优秀开源项目
5.  码云官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  码云封面人物是一档用来展示码云会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
