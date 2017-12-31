+---
 +layout: default
 +title:  "网页设计作品"
 +categories: portfolio
 +---
## jekyll+Github搭建个人博客
### 起因
最近在着手于网页设计与制作的期末专题——用网站搭建个人博客。
由于申请个人的域名是需要消耗金钱，而且我发现了可以在github上自建博客。经过一段研究之后，发现可以在期中使用各种标签或者是脚本，这个这个笔记就是介绍和总结了如何搭建的方法，若有出现什么错误或者是疏漏，欢迎来指教。
### jekyll

jekyll是一个纯前端的框架，无需使用数据库，即是不用涉及到后端，就可以灵活的生成动态的html页面。Githbu原生支持jekyll,不需要在本地bulid，直接把jekyll项目push到github,就可以自动的生成html。
![image](https://upload-images.jianshu.io/upload_images/2949750-927907b6e1de330f.png?imageMogr2/auto-orient/)

### 搭建步骤
* #### 第一步 创建一个代码库
必须创建一个特殊的代码仓库，名字必须是xxx.github.io，xxx是你的github昵称。

* #### 第二步 拷贝代码到本地
将自己的git 直接拷贝到本地，以下是代码
> git clone git@github.com:SquarePants1991/SquarePants1991.github.io.git
cd SquarePants1991.github.io
* #### 第三步 安装ruby环境
如果你没有安装ruby，请安装，Mac上一般会自带ruby。通过终端运行ruby --version可以检测有没有安装
> source 'https://rubygems.org'
gem "github-pages", group: :jekyll_plugins
* #### 第四步 安装Jekyll环境
在你的xxx.github.io目录下新增文件Gemfile。复制下面的内容到Gemfile里。
> source 'https://rubygems.org'
gem "github-pages", group: :jekyll_plugins
* #### 第五步 创建个人博客
删除你xxx.github.io目录下的Gemfile和Gemfile.lock文件，然后使用终端在该目录下运行jekyll new ./。成功后，直接运行jekyll serve就可以在本地预览效果了。在浏览器输入http://127.0.0.1:4000/，可以查看效果。
*　#### 第六步 添加文章
> x.github.io/_posts目录下按照年-月-日-名称.markdown的文件名格式创建新文章。文章内容可以参考自带的文章示例。
*　### 最后一步 访问个人博客
最后我们把xxx.github.io目录下的内容都push到Github上，就可以访问你的个人博客啦。地址就是xxx.github.io。

