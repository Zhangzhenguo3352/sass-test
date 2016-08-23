# sass-test
小练 sass
```
命令
  gem index.sass index.css

```

```
介绍
整体都是css 预处理器
sass 和 less 的区别
          sass 是基于 ruby的  大文件 sass 略微胜出一点点，
                                             优势2  sass 的扩展稍微 比 less 稍微强悍点
                                             优势3  sass 的标签嵌套的略专业
特点  1种是压缩，1种是编译 ，和有一种是直接的监听
less  是基于 javascript ，内部使用的
css 还有后 处理器

css 预处理器 不只有 less 和 sass 还有很多
函数上 编程是一种趋势，因为传统的 css 太单调了，
          没有什么技术含量，就是一             个 “对接” 的过程，
          而且用这种开发的话，对于网站的复用性，
          而且可以用逻辑性的处理 css

学习sass 方法：不一定要把 sass 所有东西都来一遍，在学习的
          的时候边学习边早就OK了，因为这个东西是就行 API 适的提供，
          不用吧所有的东西全部学会，只要掌握基础的部分，比如如何编译，
          如何嵌套的写法，如何里面就行计算等等。。随着项目需要不断的看它的
          API ，慢慢的一样新技术就熟了，熟练以后可以看一下 sass 背后的一些
          事情，它是 如何编译的，它都做了什么那
js 学习也是最处要懂得 变量、循环、逻辑判断这些
要知道 sass 是什么： 1 它是预处理器
                                    2 函数式编程
                                    3 它是基于 ruby
          中文网站  sass 的爱好者开发的 http://www.w3cplus.com/sassguide/
          英文网站  http://sass-lang.com/
sass 安装
          基于 ruby 所以要先安装 ruby
          MAC 自带 ruby 因此不用安装
          win 安装可能 环境变量会出现点问题
          gem 是 ruby 的包管理，也就是ruby 的命令方法
          ruby 方式安装 sass
                    gem install sass
sass 入门
          文件夹里建一个 xxx.scss 文件
          写完内容后 用 sass xxx.scss xxx.css 命令来编译（也就是转成 css）
                    sass  xxx.scss xxx.css
          后缀 有  1，xxx.sass     严格模式类型的
                        2,  xxx.scss     不是严格模式类型的，日常中用这种

Compass 是什么？
          简单说 Compass是sass 的工具库 光这点就比 less 强
          sass 本身只是编译器，Compass在它的基础上，封装了一系列有用的模块和模板，
          补充sass 的功能，它们之间的关系，有点像javasciprt和 jquery
```
