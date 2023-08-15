# Summer-Lessons-2023
2023暑期 Go Web 开发基础课程源代码以及 markdown 授课文档

# 注意
+ **如果是没有编程基础的同学，我们建议是先从 C/C++ 入门，Go 的语法和 C/C++ 还是很相似的，学习完 C/C++ 后再上手会更好**
+ **视频和 markdown 文档建议一起观看，可能部分视频中没提到的内容会在markdown 文档补充**
	+ **markdown 文档（以 .md 结尾）可以使用 VSCode（安装见第一节课） 打开**
	+ **在插件商店安装 Markdown Preview Enhanced**
	+ ![](https://image.bluebird.icu/img/231293dd-8d19-4425-8bad-c0b53b843f61.webp)
	+ **然后右键打开侧边预览即可**
	+ ![](https://image.bluebird.icu/img/01c2de7c-692d-4ad0-ad3a-f49cd3372d1e.webp)
+ **视频部分可能有口误或者讲错的地方，此外，遇到不理解的地方依旧是希望你可以在群里多提问**

# 学习流程
+ 跟着前置课程学习完 VSCode 和 Golang 的安装与配置
	+ 注意：视频中在 MySQL 安装配置完有一步给 Golang 配置境内的镜像源的操作别漏下，不然安装包可能会很慢或者出错
	+ **补充：在配置完镜像源后进入 VSCode 还需要一步去安装 Go 的开发工具包，具体见文档操作（视频里忘录了）**
	+ MySQL 在 Gorm 学习前不会使用到，可以选择一起配置完，也可以在讲到 Gorm 时再去安装配置
+ 由于本次课程主要是面向 Go 语言的 Web 开发课程，所以 Go 的基础语法等均不会涉及到，可以移步到我们去年的暑期授课视频第一节[【精弘网络】2022暑期课程-后端课程第一节直播回放_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1ud4y1o7Yt/?vd_source=43db43acaedd8464c1dd6f9669001984)
	+ 注：前面的环境配置可以跳过，去年基础语法讲课所使用的 IDE 是 GoLand，因为你们暂时还没有学生邮箱，所以我们使用的是 VSCode
	+ 听完 guessing-game 就行了，剩下后面的内容如果没有什么基础可能听不懂，这点没有关系，感兴趣可以听下去
+ 学习完基础语法，就可以正式开始我们的 Go Web 课程
	+ 先去看 Web 开发前置知识，了解什么是 Web
	+ 然后按照 gin-gorm-viper，也就是我们的视频发布顺序观看就可以了
    + **课程源码想要运行记得将各个部分单独拿出来，即用 VSCode 打开时不打开 Summer-Lessons-2023 文件夹，而是打开 gin 文件夹（如果你打算开始学习 gin 的部分）**
        + **打开后记得安装对应的软件包（不知道这是什么的可以先观看课程），或者在终端输入 `go mod tidy`**
+ 最后是项目部分，通讯录后端的一个实现
    + 如果想要直接运行需要将 config.example.yaml 文件名修改为 config.yaml，并将其中的数据库信息修改为自己的
    + apifox 文档在 doc 中可以导入（具体操作见视频）
+ 由于是基础课程，所以内容讲的都不会很深入，希望你可以学会自己去看文档、找资料，更进一步的进行学习

# 大作业和免笔试资格
## 大作业
+ 检验你的学习成果，我们会将要求用 apifox 文档的形式给出，你只需要根据文档去实现对应的要求
+ 如果遇到文档有问题也可以向我们反馈
+ 遇到不懂的地方也可以向我们提问
## 免笔试
+ 技术部招新分为笔试和面试两部分
+ 如果你能够运用所学在我们招新前（时间视具体通知）去完成我们布置的大作业（难度不高，都可以试试），那么我们技术部需要你这样的人才（大作业都做了这不来我们技术部（）），并且会给你一个免笔试的资格（没错只需要来面试让我们看看你就好了）。