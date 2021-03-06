# 第一次课程总结
在完成徐老师布置的课前预习作业时，还一脸懵圈，只知道生搬硬套过来，虽然还是完成了，也有了学习编程的信心，但是对开始的编程课还是有些忐忑，生怕自己听不懂。
没想到小白的编程之旅——第一堂课会是以“银行开会流程”来切入的，跟着老师的思路，信心马上就提升上来了。整个1个半小时下来，虽然仍有不明白的地方，但是对JS编程终于也有一些感觉。
再加上回看了几遍，补充了一些断层知识和概念，下面就对第一堂课的学习内容进行一下总结。
## 一、梳理课程所学概念及内在逻辑
第一堂课主要通过类比“银行开户流程”的方式，认识了JavaScript运行环境框架及其涵盖的概念，以及代码解释、执行的基础流程。
### 1. 所学概念
“银行开户流程”的业务架构与JS的运行环境架构非常相似，JS的运行环境架构主要由内置库、V8引擎组成，再加上一个第三方库，JS代码就能运行起来
- 运行环境：JS代码能被执行的前提，就像植物需要土壤才能长出花草一般，有了运行环境，代码才能通过计算机实现操作意图。JS的运行环境分为web端和nodejs在不同运行环境中，有不同的功能。
- V8引擎：属于JS运行环境中的核心，主要用来执行代码，JS代码被编译成计算机能懂的指令后，再执行代码。就像汽车的发动机，把燃油转化成汽车所需的动力。
- 编译器、解释（执行）器：JS作为一种编程语言，在输入端，由程序员来编写，然后V8引擎来执行代码。PS：JS属于边解释边执行的编程语言，开发率较高，但是运行效率较低。
- 内置库：类比为“银行开户流程”中的内置服务，为输入进来的JS代码提供一些额外的加成服务，对输入进来的代码进行一些预处理，方便V8引擎执行代码。
- 第三方库：类比理解为第三方服务，为主业提供一些直接可以调用的功能便利，转嫁一些风险。第三方库的作用同样是为JS代码提供一些方便执行的功能。
而不是要求JS什么功能都具备
### 2. 课程内在逻辑框架搭建
- 流程：（代码+调用内置库和第三方库）→V8引擎编译、解释（执行）→输出结果
- 框架：运行环境包括内置库+V8引擎+第三方库，按照前、后端又分为浏览器运行环境和nodejs运行环境，在前、后端内置库的共同点都有内置对象
### 3. 课程中有所启发的学习方法
老师通过类比“银行开户流程”来告诉我们JS运行环境架构，其中有一个思路值得借鉴。
- 设计流程→优化流程→定义流程→抽象出框架
### 4.学习JS的方向：
一开始认为JS是专业人士的专用工具，后面加入新大之后，认识到编程的思维其实每个人都应该学习、具备，因为这是一种机器智商，关于人如何操作机器去高效完成工作，实现自己的意图。
编程语言是人和机器沟通的工具，就像不同国家的人使用不同语言一样，学会了编程，能与计算机沟通。JS作为一种前端、后端都能使用的语言，学习JS既要学会编程的思维，又需要出成果。
所以JS学习的方向是，掌握好JS的基础知识，以微信小程序为目标，实际出一个成果。
## 二、预习作业实际操作中存在的问题
- github网页和终端使用流程：
1. git clone URL→本地修改→git status查询状态→git add 添加→git commit -m"提交日志信息"→git push origin master推送到远程
2. fork到自己的仓库→编辑、修改（网页版git上操作）→pull request给老师
- 存在问题：
1. 没搞清楚GitHub是搞什么的，先用再说吧
2. 在pr的时候，是直接在网页上操作的，没clone到本地仓库操作后用终端推送远程。
有个疑问：如果clone到本地仓库进行编辑修改，文件扩展名是.md这个是不是需要找个专门的编辑器来打开使用呢？
