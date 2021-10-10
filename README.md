# 小帅b写给新手们的《轻松入门Python基础教程》


> 作者：[小帅b](https://fxxkpython.com/)
> 欢迎关注公众号：小帅b和他的朋友们，微信搜索：xsb_pro

# pick up Python

那个，如果你是 0 基础，那么接下来就和我一起 pick up Python 吧。

是的，没错，pick up，以后你告诉别人说你要学 python，你可以很装逼的告诉他：“老子要pick up Python了！”

>  ![人生苦短，我特么要pick up Python~~~ ](http://www.ubuntu520.com/images/py1.jpg)
   人生苦短，我特么要pick up Python~~~ 

这个教程我会尽量做得风趣幽默，让你看起来像看小黄文一样轻松，把我当作你的朋友，少点距离感，这正是我想做的事情。

> ![听到小黄文，想想还有点鸡动呢 (你可别乱来啊！)](http://www.ubuntu520.com/images/py2.png)
  听到小黄文，想想还有点鸡动呢 (你可别乱来啊！)

## 为什么要学 Python

对了，还没告诉你为什么要学 Python 呢，我来说说这几点就已经足够：

> ![Python](http://www.ubuntu520.com/images/py3.png)

1. 现在 Python 已经成为世界上最流行的编程语言之一了，而且大部分的 Linux 系统，MacOS系统都直接内置了 Python ，就问你牛逼不？



2. 现在连小学生都开始学习 Python 了，Python 已经纳入了某地区小学的教材了。Pyhon 已然成为了编程界的 “网红”，现在程序员们可能不知道Cobol，Basic，Pascal，Perl，Ruby，但没有一个程序员不知道Python的。



3. 上手简单，现在很多从来没接触过编程的人都着手开始学习Python 了，我有一朋友，之前没有任何编程基础，学了半年多找到了份工作，工资 12k 妥妥的，不过不要去羡慕别人的数字，人家背后的努力你没看到而已，如果你现在也是没有任何基础或者想要从 0 学习 Python ，那么你来对地方了！因为人生苦短，我们一起搞 Python。



4. web开发，科学计算，3D建模，人工智能，嵌入式开发，云计算，大数据等等都特么能看到 Python 的身影，不知道你知不知道 NASA（美国宇航局）使用 Python 来开发用于系统集成和卫星，火箭的测试自动化么？还有网易，腾讯，搜狐，金山，豆瓣，YouTube ，google，雅虎（太多，举例不完）都在用Python。所以这么牛逼，何不 pick up python 呢？



5. 用 Python 可以做很多事情，可以爬取你想要的数据，可以做自动脚本，之前的微信跳一跳辅助，12306抢票等都可以用Python实现，还有很多数据分析，项目系统，聊天系统，游戏等等多了去了。所以这么牛逼，何不 pick up Python 呢？

> ![是不是真的啊？又想骗我学习~](http://www.ubuntu520.com/images/py5.jpg)
是不是真的啊？又想骗我学习~

不妨再来看下[Python官网](https://www.python.org/)之前的介绍，**他说这些是使用Python的人宁愿不使用其他任何东西的一些原因**：

> ![python](http://www.ubuntu520.com/images/py6.jpg)

1. Python很牛逼...而且很快；

2. 可以和别人一起P；

3. 在哪都可以搞；

4. 非常友好&学习简单；

5. 开放。

> ![好棒！我要pick up Python了，接下来将是学习python的正确势！](http://www.ubuntu520.com/images/py7.jpg)
>好棒！我要pick up Python了，接下来将是学习python的正确势！

## 别怕，Python 不是蟒蛇

PS：虽然 Python 的中文意思是「蟒蛇」，但是 [Python 语言的创造者 Guido van Rossum](https://mp.weixin.qq.com/s?__biz=Mzg2NzYyNjg2Nw==&mid=2247490157&idx=1&sn=2538bae8abf60bf5e745cfc7f24afe76&chksm=ceb9e071f9ce696744bd1ee3a6b785c46a41e0b278d8a541c4aa5f9254cf28e0496716e8681b&token=1031215785&lang=zh_CN#rd) 是因为超喜欢英国广播公司的节目「蟒蛇飞行马戏」而命名这个语言的，所以你可别以为 Python 创造者是个喜欢蟒蛇的怪叔叔哦。

> ![python 创始人](http://www.ubuntu520.com/images/py8.jpg)
>python 创始人


# Python : Hello World !

不管学什么编程语言，在一开始入门的时候，都会从「Hello Wrold」开始，这已经成为编程界的不成文规定。

在 1972 年的时候，有个叫科比 布莱恩的人使用 B 语言撰写了第一个使用参数的 Hello World 相关程序。

说明一下：此科比非彼科比，这哥们当然不是我的那位打NBA的偶像啊！

> ![如果科比不打 NBA 而去编程，会是怎么样呢？](http://www.ubuntu520.com/images/py5.jpg)
>如果科比不打 NBA 而去编程，会是怎么样呢？


看下图！这就是由 科比 布莱恩 撰写的「Hello Wrold」程序：

> ![Hello Wrold](http://www.ubuntu520.com/images/py2.2.jpg)

自此，Hello World 成为了计算机程序员学习新的编程语言的传统美德！

那么，我们学习 Python 也从「Hello World」开始吧！

## 安装 Python

如果你用的 Mac 或者 Linux 的话，那么你就不需要安装了，因为系统已经内置 Python 了，如果是 Windows 系统的话，安装也很简单，比安装 LOL 英雄联盟还简单。所以我相信不用我说，你也知道怎么安装，如果你连软件都不会安装，那么可以不用关注我了。

> ![说的好屌啊，不知道是不是真的？](http://www.ubuntu520.com/images/py5.jpg)
>说的好屌啊，不知道是不是真的？

你可以直接访问 [Python 的官网](http://www.python.org) 下载最新的版本。

> ![下载 python](http://www.ubuntu520.com/images/py2.3.jpg)

在这里告诉一下完全没经验的朋友们，千万不要去百度搜索 python 下载，然后去到类似这样的地方下载：

> ![别在这里下载 python](http://www.ubuntu520.com/images/py2.4.png)
>别在这里下载 python

因为这样做**很容易被人骂傻逼的**。

> ![听说现在骂百度是一种正确的价值观！](http://www.ubuntu520.com/images/py5.jpg)
>听说现在骂百度是一种正确的价值观！

## 开始玩耍

已经安装好Python之后呢，你可以在命令行里面输入「python」，然后你就会看到这样的东东：

> ![python 版本](http://www.ubuntu520.com/images/py2.5.png)
> 如果你显示的是 python2 版本，请升级到 python3 版本哦，现在最新版本是 3.10 啦～

有没有看到三道杠杠 「 >>>」。是不是突然想到小学的时候，那些受老师爱戴，学生中的好榜样的队长袖口上的三道杠！

> ![三道杠，怕不怕](http://www.ubuntu520.com/images/py2.6.jpg)
>三道杠，怕不怕

> ![大队长和大队委，牛逼牛逼，社会社会。](http://www.ubuntu520.com/images/py2.7.jpg)
>大队长和大队委，牛逼牛逼，社会社会。

不过在 Python 这里呢， >>> 是一个提示符来的，也就是在它后面可以输入一些内容，更确切的说，**这是交互式Pyhon解释器接收内容的符号**。

比如我们要 Python 给我们打印 Hello World 的字样，那么你就可以这样子：在 "三道杠" 后面输入 print ("Hello World") , 然后用力按一下回车键，你就可以看到 Python 解释器打印出 Hello World 这样的字符串了：

> ![Hello World ](http://www.ubuntu520.com/images/py2.8.png)

当然仅仅是打印 Hello World 你可能觉得没什么牛逼的，但是这不是才入门么，想要做更多有趣的事情么？跟着我一步一步来！


# Pythoner ：挑选一个Python编辑器



我们在玩游戏的时候，我们通过层层努力的打怪升级，为的是什么？是女人么？是金钱么？ 当然不是，我们有那么肤浅么？我们为了能够拥有更牛逼的装备。

> ![老话说的好：工欲善其事必先利其器！你的武器越牛逼，你的女人就越能够对你服服帖帖的。](http://www.ubuntu520.com/images/py3-1.jpg)
>老话说的好：工欲善其事必先利其器！你的武器越牛逼，你的女人就越能够对你服服帖帖的。

所以，我们在使用 Python 来编程的时候，我们也需要一个牛逼的武器，来编写我们的代码 —— 编辑器！



在这里跟大家说一下现在市面上比较主流的 Python 编辑器供你参考，要知道，适合自己的才是好的。如果你的丁丁很小，使用再大 size 的套套也是白搭！

## IDLE

> ![IDLE](http://www.ubuntu520.com/images/py3-3.png)

如果你之前都没碰过编辑器，可以先使用 [IDLE](https://docs.python.org/3/library/idle.html), 它是 Pyhton 自带的一款编辑器，所以刚开始也可以使用它来玩玩，IDLE具备语法高亮功能，还允许你在IDLE中运行你的程序。

## PyCharm

> ![PyCharm](http://www.ubuntu520.com/images/py3-5.jpg)

我个比较多人使用，如果你使用过 [IntelliJ IDEA](https://www.jetbrains.com/idea/) 的话，你应该会对其爱不释手，而这款 PyCharm 也是出自同一家公司，用起来会很顺手，现在很多公司，如Twitter，Groupon，Spotify，eBay和 Telefonica 等都在用 PyCharm。 Pycharm 社区免费版本就很适合新手使用了。


##  Sublime Text

> ![Sublime Text](http://www.ubuntu520.com/images/py3-2.jpg)

[Sublime Text](https://www.sublimetext.com/) 也适合 Python 新手使用，Sublime Text支持跨平台，而且可以使用其丰富的插件和主题。各种语法高亮和代码补全，整体看起来挺舒服的，而且主题配置起来也不难。


## Visual Studio Code

> ![Visual Studio Code](https://code.visualstudio.com/assets/home/home-screenshot-mac-lg-2x.png)
[vc code](https://code.visualstudio.com/) ，微软出品，拥有很多丰富的插件，也很适合作为 Python 的编辑器使用，容易上手。


## VIM

> ![VIM](http://www.ubuntu520.com/images/py3-4.jpg)

[Vim](https://www.vim.org/)是一款强大的编辑器，如果你熟练使用 Vim 的话，那么你完全可以脱离鼠标，双手在键盘上像弹钢琴那般酸爽，不过 Vim 需要一定的学习成本，需要花点时间去研究一下各种快捷命令和插件的使用，但是从长远来看，这都是大有所益的。


## Emacs

> ![Emacs](http://www.ubuntu520.com/images/py3-6.jpg)

[Emacs](https://www.gnu.org/s/emacs/) 在 python 开发界也很受欢迎，它是一款开源的编辑器，支持插件扩展，可以配置一个 python 集成开发环境， Emacs 不仅仅是一个编辑器，他是一个整合环境，可以说是一个集成开发环境。


ok，就推荐这几个市面上比较流行的编辑器，当然还有其他的编辑器，最适合自己的才是最好的，用起来顺手不尴尬才爽嘛~

在这里给点建议就是新手可以先上手使用 IDLE 和 Pycharm 或 vs code，Vim 是一款强大的编辑器，没事花点时间研究下，相信我，真的会受益匪浅的。

# 自己写一个 Say Hello 的 python 程序

是不是觉得我特么才安装了 Python 软件，这么快我就可以写出 python 程序了？

先别怀疑着先，一开始我就说了，Python 语言简单，上手快，所以你跟着我呢，一步一步来，准没错的。

> ![又他妈的不要脸了！](http://www.ubuntu520.com/images/py4-1.jpg)
>又他妈的不要脸了！

相信你已经知道使用什么样的编辑器了，因为这里要照顾到一些还没有编程基础的朋友们，所以现在就先用 IDLE 这个编辑器，到时候你越来越牛逼了，咱们再换编辑器，没毛病。

> ![好了，别废话了，快点带我写程序啊！](http://www.ubuntu520.com/images/py5.jpg)
>好了，别废话了，快点带我写程序啊！

## 这个Python程序可以干嘛

首先我们来想一下我们这个 Python 程序可以干嘛？

1. 可以让我们输入名字；
2. 可以跟我们输入的这个名字say Hello！

ok，我们要达到以上的功能，咱们说干就干！

## 开始编写第一个 python 小程序

打开我们的编辑器：

> ![IDLE编辑器](http://www.ubuntu520.com/images/py4-3.jpg)

现在的它是处于交互式解释器的状态，如果我们现在在这个交互解释器编写代码，那等下关掉所有的代码就不见了，我们当然是想要能够写出一个自己和别人都能够运行的程序，怎么能说代码丢掉就丢掉呢？

> ![我的小九九都被你发现了，是不是我的pp一抬，你就知道我是要拉尿还是拉shit。](http://www.ubuntu520.com/images/py5.jpg)
>我的小九九都被你发现了，是不是我的pp一抬，你就知道我是要拉尿还是拉shit。

那么我们就使用快捷键「Ctrl + N」来新建一个编辑窗口，可以看到这里没有「三道杠」提示符了吧，我们在这里写的代码待会可以保存，爱在哪里运行就哪里运行。

> ![IDLE编辑器](http://www.ubuntu520.com/images/py4-5.jpg)

我们刚刚说了，想要这个程序可以让我们输入名字，那么我们可以用一个叫做 name 的变量来接收别人输入名字，可能你现在不知道变量是什么鬼，但是没关系，你现在把它理解为是一个「标签」，这个「标签」可以来对应用户输入的名字就好了，往后我会告诉你变量的使用，别急，咱们慢慢来。

ok，那么我们就可以写我们的第一行代码了：

``` python
name = input ("你他妈叫什么玩意儿？")
```

解释一下这行代码的意思，input 是输入的意思，而「你他妈叫什么玩意儿？」就是显示给用户看的提示语。

我们已经完成了第一点，也就是这个程序可以让我们输入名字，那么我们继续完成第二点，可以跟我们输入的这个名字 say Hello！

那么很简单，我们只要再写一行代码即可：

``` python
    print("Hello" + name)
```

解释一下这行代码的意思， print 就是打印的意思，你可以理解为信息的输出，我们已经知道 name 这个 "标签" 已经贴到了用户输入的名字，所以 "Hello" + name 就是会输出 Hello xxx！

> ![IDLE编辑器](http://www.ubuntu520.com/images/py4-6.png)


ok，我们已经写完代码了，我们「Ctrl + S」保存一下文件到桌面，你可以把它命名为「Hello.py」。

接着我们就可以来运行我们的程序了，在我们的 IDLE 中用力的按一下 F5 开始运行程序：

> ![IDLE编辑器](http://www.ubuntu520.com/images/py4-7.gif)

> ![可以可以~](http://www.ubuntu520.com/images/py4-8.jpg)
>可以可以~

看到木有，我们的程序完成了。是不是挺好玩的！慢慢来，我们到时就可以写游戏，写网站，写爬虫了，是不是想想还有点小激动呢？


# 什么是常量，什么是变量？

这两个概念很简单理解，以后我们在使用 Python 编程的时候也会经常用到。

## 常量

我们知道，世界杯踢球每队会派出 11 名队员出场比赛，这里的 11 是固定不变的。我们高中的时候学的物理有个叫做重力加速度的概念，它是 9.8 m/s²，这里的 9.8 也是一样是固定不变的，**对于这些固定不变的，具备字面上的意义的量我们就称为「常量」**，它就像一座高高的大山，不会被轻而易举的改变，愚公移山？不存在的。

> ![愚公移山](http://www.ubuntu520.com/images/py5-1.jpg)

> ![愚公不畏艰难，坚持不懈，挖山不止，最终感动天帝而将山挪走的故事。通过愚公的坚持不懈与智叟的胆小怯懦，以及“愚”与“智”的对比告诉人们，无论遇到什么困难，只要有恒心、有毅力地做下去，就有可能成功。](http://www.ubuntu520.com/images/py3-1.jpg)
>愚公不畏艰难，坚持不懈，挖山不止，最终感动天帝而将山挪走的故事。通过愚公的坚持不懈与智叟的胆小怯懦，以及“愚”与“智”的对比告诉人们，无论遇到什么困难，只要有恒心、有毅力地做下去，就有可能成功。

> ![这特么跟常量有毛关系？](http://www.ubuntu520.com/images/py5-2.png)
>这特么跟常量有毛关系？

## 变量

变量可以把它理解为一个「标签」，你可以通过它来「贴到」一些变化的值上。

其实说白了变量就是指向你的计算机中存储信息的一部分内存地址，对应的内存可以存储一些值（对象）。

比如说你想要用「 i 」 来表示一个变量，对 python 来说是一件很简单的事，你只要用 「i = 变化的值」就可以了。

举个例子：

> ![python 变量](http://www.ubuntu520.com/images/py5-3.jpg)

这里使用 i 来表示一个值 5，也就是说我们将 5 赋值给变量 i 。那么现在这个 i 指向的值就是 5 。

所以这里的 i+6 就是 5+6。

假如我们现在想让 i 来表示的值变成 2，这完全没问题，只要这样即可：

> ![python 变量](http://www.ubuntu520.com/images/py5-6.png)

> ![男人能屈能伸，可长可短，算不算变量？](http://www.ubuntu520.com/images/py5.jpg)
>男人能屈能伸，可长可短，算不算变量？

注意了，Python中的变量名称只能**由字母、数字、下划线构成，而且不可以数字打头**，像「xiaoshuaib_520」这样的是合法的，但是如果是「520_xiaoshuaib」那是不可以的。

不信你瞧：

> ![python 变量](http://www.ubuntu520.com/images/py5-5.png)

# Python基本数据类型之「数」

相信你已经知道了变量是个什么玩意了，变量可以来表示变化的值，而这些变化的值呢，是可以对其分门别类的，也就是说每个变化的值它是有专属的类型的，你可以理解为这个值就是一个对象。



在这里补充一点：Python 中的变量是不需要声明。每个变量在使用前都必须赋值，变量赋值以后这个变量才会被创建。



比如说 i = 5 ，在这里并不需要去定义这个 i 的类型，例如「整数类型 i = 5」，我们只要直接把 5 赋值给 i 就可以了，赋值后这个变量 i 就被创建了。这时候我们就可以说变量 i 现在所指的是一个为「整数类型的值5」。

> ![Python除了基本数据类型「数」之外，还别的基本类型例如字符串，我们也可以自己定义数据类型，这个往后讲。](http://www.ubuntu520.com/images/py3-1.jpg)
>Python除了基本数据类型「数」之外，还别的基本类型例如字符串，我们也可以自己定义数据类型，这个往后讲。

接下来就来说说 Python 中基础数据类型中的「数」。

## 数

在 Python 中的数有四种，分别是整数（int）、长整数（long）、浮点数（float）、复数（complex）。

### 整数

像 6 这样的数字就是整数，不带小数点的，而长整数只不过代表的是比较大一点的整数，现在 python3 中的整数（int）已经不限制数的大小限制了，所以整数类型也包括长整数。



我们可以通过 Python 交互式解释器来运算整数：

> ![python运算整数](http://www.ubuntu520.com/images/py6-1.jpg)

这里的 「6+6」没什么好说的吧，而 「6//2」就是6整除2的意思了，「1%2」的意思是说1除以2的余数，「%」有个专业名词叫做取余或者取模。而「2**3」就是2的三次方的意思。



怎么样？简单吧！

### 浮点数

但是如果你试试 「1/2」，这时候你会发现结果有小数点：

> ![python运算浮点数](http://www.ubuntu520.com/images/py6-2.jpg)

在这里的 「/」是除的意思，但是不会整除，你可以看到每次的结果都会有小数点。而这些像 「0.5」，「1.0」带有小数点的数我们就叫做浮点数。

### 复数

Python中的复数由实数部分和虚数部分组成。虚部的后缀为「j」。


例如：4+5j 就是一个复数，实数部分为 4.0，虚数部分为 5.0。



你可以把复数理解成为一个平面的一个点，例如上面这个例子你可以把它理解为平面上的点（4,5）。



Python连复数都支持，你说它能不强大么？

# 二进制八进制十六进制的快速转化

## 二进制

我们都知道，在计算机中，存储的数据都是像这样「010101010110010101...」的东东，这一串数字就是二进制。

想想你家里的灯，是不是只有两种状态，一种是开灯，一种是关灯。

> ![开关灯](http://www.ubuntu520.com/images/py8-1.jpg)

而我们的计算机在表示数据的时候也是按照这样的状态来表示的。也就是一开一关两个状态。



我们把 0 当做关，把 1 当做开！

> ![0有点像把锁，1有点像把钥匙！emmmm..](http://www.ubuntu520.com/images/py8-2.jpg)
>0有点像把锁，1有点像把钥匙！emmmm..

但是现在想想啊，我们那么多数据，比如说一个 mp3 音乐，一部苍老师的教程视频，如果只让计算机仅仅以 0 和 1 这两种状态来表达这些数据，那是心有余而力不足的。



那么怎么办呢？这时候国际标准化组织就决定了，不够用是吧，那么用 8 个这样的状态来表达一个数据！



也就是：



一个数据 = 01010101 （8个状态）



那么这样的由 8 个状态组成的数据就叫做**字节**！

不信的话你可以随便点开的桌面的文件，右键打开属性看看，是不是都会给你显示这个文件的大小都会用字节来表示：

> ![文件的大小](http://www.ubuntu520.com/images/py8-3.jpg)

> ![你这小黄图能否图片分享一下？](http://www.ubuntu520.com/images/py8-4.gif)
>你这小黄图能否图片分享一下？

所以知道以下的东东代表的是什么了吧：

    1byte（字节）= 8bit（位，状态）

    1kb = 1024byte
    1mb = 1024kb
    1g = 1024mb
    1tb = 1024g

## 二进制怎么转化成八进制？

我们已经知道了一个字节需要 8 个二进制位来表示，有点长了，那么用八进制来表示的话就会短一点，比如说有怎么一个字节：



0101101

如果我们想把它变成「八进制」的话，那就从右到左，每三位当做一个，最左边的不够就补0。也就是说上面这个可以这样：

000101101

把每三位的整体转化成十进制的数，就变成八进制了。至于怎么转换，下面会说到。

这时候用八进制就只用3个数就可以表示了。

## 二进制怎么转化成十六进制？

同理，十六进制可以用更少的位数来表示，如果我们想把0101101变成 十六进制 的话，那就从右到左，每四位当做一个，最左边的不够就补0。也就是说上面这个可以这样：

00101101

把每四位的整体转化成十进制的数，就变成十六进制了。

至于这么转换，下面也会说到。

这时候用十六进制就只用2个数就可以表示了。

## 不同的进制表达方式

二进制是由 「0,1」 组成，通常以 0b 开头。


八进制是由 「0,1,2,3,4,5,6,7」 组成，以 0 开头。



十进制是由 「0,1,2,3,4,5,6，7,8,9,0」 组成。



十六进制是由 「0,1,2,3,4,5,6,7,8,9,a,b,c,d,e,f」 组成，以0x开头的。

## 进制之间的相互转化

在这里告诉大家一个进制之间快速转化的方法，当然，不是使用计算器啊 - -



首先你只要记住以下对应关系即可：

```
1    1    1    1    1    1    1    1

128 64  32  16   8    4    2    1
```

### 二进制转化为十进制

那么如果告诉你一个二进制 如 0b11111111，转化成十进制，怎么做呢？把对应的数加起来就可以了。



0b11111111 = 128+64+32+16+8+4+2+1 = 255



看到 255 有没有一种熟悉的感觉？



所以这时候再给你出道题，把 0b010110 转化成十进制你应该会了吧？



0b010110 = 16 + 4 + 2 = 22

### 十进制转化为二进制

同样的：

```
1    1    1    1    1    1    1    1

128 64  32  16   8    4    2    1
```

我们要把十进制如22，转为二进制就是：



22之内16有没有？ 那么在16对应的地方就有1。

> ![](http://www.ubuntu520.com/images/8-1.png)

22-16=6，那么8对应的就不存在了。

> ![](http://www.ubuntu520.com/images/8-2.png)

6之内有4对吧，那么4对应的就有1，6-4=2，那么2也有，2-2=0，所以1就没了。

> ![](http://www.ubuntu520.com/images/8-3.png)

所以最后的答案就是 22 = 0b10110。

### 二进制转化为八进制

我们已经知道了在二进制中每三位的十进制代表一个八进制位：



000101101



那么这时候只要把这个二进制拆成三份，每一份转化成十进制，再组合起来就是八进制了。



000 = 0；

101 = 4+1 = 5；

101 = 4+1 = 5；



所以二进制 0b000101101 = 八进制0055。

### 二进制转化为十六进制

我们已经知道了在二进制中每四位的十进制代表一个十六进制位：



00101101



那么这时候只要把这个二进制拆成两份，每一份转化成十进制，再组合起来就是十六进制了。



0010 = 2；

1101 = 8+4+1 = D；



所以二进制 0b00101101 = 十六进制0x2D。

ok，以上，其实说实话，如果不懂这个也不影响后面使用 Python 来编程，但是懂的多一些总归没有什么坏处。




# 各种符号的意义及用法

我们小时候，老师都教过我们 1+1=2 ，这个 「1+1」 就是表达式， 「+」 就是运算符。



咱们接下来就来了解一下，在 python 中，那些运算符是什么意思，怎么用？ 相信看完，你就能够明白了。

## 加减乘除(+-/*)

对于 +-*/ 我们都知道它们是什么含义了吧，就算你的数学是体育老师教的，你也会懂加减乘除吧。



不过有两个小细节值得你去注意，就是字符串之间的相加和相乘：


> ![python运算浮点数](http://www.ubuntu520.com/images/7-1.jpg)


看懂是啥意思了么？



字符串之间的相加会被"拼接"起来，而字符串和数字相乘就会重复多次相同的字符串。



其它的大于、小于、大于等于、小于等于就不说了，因为我们小学老师都跟我们说过了。接下来说几个比较少见的符号。

## 幂(**)

幂就是以前我们学数学的时候老师讲的什么什么几次方，别一看到幂就想到杨幂。

> ![杨幂](http://c1.yaofangwang.net/Common/Upload/guide/0/2e5d2989-a526-4aaa-b7cc-61e24e4ac8ea8928.jpg)

用符号 `**` 表示， 比如 `2**3 = 8`。

## 整除（//）

我们知道 / 是除的意思，你知道 6/3 等于多少么？你可能会觉得在侮辱你的智商对不对，不是 2 么？ 在 python 中得出的结果是 2.0 ， 也就是它返回的是浮点数。 那么我们只想得到整数部分怎么玩呢？



用 // 这个 ： 6//3 = 2。

## 取模（%）

取模的意思不是让你去获取个模特，是得到除法的余数，比如 8%5 = 3 ，因为 8/5 = 1余3。

## 左移（<<）和右移(>>)

移的意思就是把一个数的二进制移动多少个位。



比如 2 << 2 = 8 。这是为什么呢？



首先 2 的 二进制 是 0b00000010 ，然后将它左移2位（虚位补0）就变成这样： 0b00001000 ，它对应的十进制就是 8 。



同样的道理：



8 >> 2 的意思就是将 8 的二进制向右移动2位：



0b00001000 右移动2位：0b00000010 也就是对应十进制的 2。



那么下次有人问你2*8怎么样写代码比较高效，你就直接甩给它： 2<<3 就好了。

## 与（&）

记住一句话："同真与真"，什么意思呢？ 比如 1&1=1,1&0=0,

1就是真，0就是假。也就是只有 1&1=1，其它的都等于0。



那么 2 & 3 怎么算？



先将它们转化为二进制：



2对应的二进制 ： 0b00000010

3对应的二进制 ： 0b00000011



那么从右往左： 0&1=0 ，1&1=1，0&0=0，所以结果为

0b00000010，转化为十进制就是2，所以 2&3=2。

## 或（|）

记住一句话："同假或假"，什么意思呢？ 比如 1|1=1,0|0=0,

1就是真，0就是假。也就是只有 0|0=0，其它的都等于1。



那么 2 | 3 怎么算？



先将它们转化为二进制：



2对应的二进制 ： 0b00000010

3对应的二进制 ： 0b00000011



那么从右往左： 0|1=1 ，1&1=1，0&0=0，所以结果为

0b00000011，转化为十进制就是3，所以 2|3=3。

## 异或（^）

相同者假，不同者真，什么意思呢？就是 1^1=0, 1^0=1。



那么 2^3 怎么算？



先将它们转化为二进制：



2对应的二进制 ： 0b00000010

3对应的二进制 ： 0b00000011



那么从右往左： 0^1=1 ，1^1=0，0&0=0，所以结果为

0b00000001，转化为十进制就是1，所以 2^3=1。

## 翻转（~）

x的按位翻转就是是-(x+1)。



那么 ~2 怎么算？



~2 = -（2+1） ； 所以答案就是-3。


ok，以上，其实没必要去记住，了解一下就这些符号是什么意思，怎么算的就好了。

# Python基本数据类型之「字符串」

## 单引号（'）字符串

把一段文本用单引号「'」包围起来，它就变成了字符串，和数一样是一个值。比如：



text = '世界上最帅的人是wistbean'

> ps：[wistbean](https://mp.weixin.qq.com/s?__biz=Mzg2NzYyNjg2Nw==&mid=2247490335&idx=1&sn=29662850d41f9c0d24e283cb22a318a6&chksm=ceb9e103f9ce68155bdbe3dbf83ef6ac81b6ac24b2cf8d552b115e30e7bf515818229fdb7b28&token=1031215785&lang=zh_CN#rd)是我的英文名哦～


这里的变量名就是text，而对应的值就是字符串「世界上最帅的人是wistbean」。

## 双引号(")字符串

把一段文本用双引号「"」包围起来，它就变成了字符串，和数一样是一个值。比如：



text = "世界上最帅的人是wistbean"



这里的变量名就是text，而对应的值就是字符串「世界上最帅的人是wistbean」。

> ![挖槽，这不是和单引号一样么？别特么逗我啊！](http://www.ubuntu520.com/images/py9-1.webp)
>挖槽，这不是和单引号一样么？别特么逗我啊！

哈哈，是的，其实单引号的字符串和双引号的字符串是一样的，不过为什么Python要支持单引号又支持双引号呢？



那是因为，有时候我们的文本里面，不一定就只用双引号或者单引号啊，比如说：



"包钟480，包夜1200"，她说。



这句话对于 Python 解释器来说，他只认识引号里面的内容，也就是说 python 只知道字符串「包钟480，包夜1200」，而后面的「，她说。」对于 Python 来说不认识。



那么如果是这样的话：



'"包钟480，包夜1200"，她说。'



Python 就能懂！


> ![](http://www.ubuntu520.com/images/py9-2.webp)

所以你应该理解为什么 Python 同时支持双引号和单引号了吧。

> ![包夜太贵了，能不能便宜点啊？](http://www.ubuntu520.com/images/py9-3.webp)
>包夜太贵了，能不能便宜点啊？

## 三引号字符串（'''或者"""）

这三引号是来干嘛的呢？如果你要表示一个很长很长的字符串，那么这个三引号就可以派上用场了，因为它支持跨多行，而且在这个三引号的字符串里面你要用单引号和双引号都无所谓。

像这样：



""" MM："噢，请你不要吻我"MM："噢，请你不要吻"MM："噢，请你不要"MM："噢，请你不"MM："噢，请你"MM："噢，请"MM："噢" """



Python 是完全看得懂的。

> ![](http://www.ubuntu520.com/images/py9-4.webp)

> ![我好像发现了什么不得了的事情！！！](http://www.ubuntu520.com/images/py9-5.webp)
>我好像发现了什么不得了的事情！！！

## 转义

可能你会对这样的字符串「'"包钟480，包夜1200"，她说。'」感到别扭，老子就想都用一种引号，不想要一下双引号一下单引号的行不行？

> ![行行行，老子说什么就是什么！](http://www.ubuntu520.com/images/py9-6.webp)
行行行，老子说什么就是什么！

那么这时候就可以用「转义」来解决，转义的符号是反斜杠「\」。



比如这句话「'"包钟480，包夜1200"，她说。'」我们通过转义可以变成这样：



' \'包钟480，包夜1200\'，她说。'



那么这个时候 Python 就能够看懂了， 现在这玩意「\'」在 Python 眼中就是「'」。


> ![](http://www.ubuntu520.com/images/py9-7.webp)

所以你可以把转义「\」理解为是为了让 Python 看的到我们想要表达的东西。


u' \'包钟480，包夜1200\'，她说。'

## 字符串的拼接

有时候我们需要两段话拼接在一起，对于 Python 来说so easy，只要像两个数字一样相加即可。


像这样：


    x = "Hello, "

    y = "World!"

    x+y



这时候呢，「+」这个符号就把两个字符串连接起来了，在这里的 x+y 就等于 Hello，World！

> ![](http://www.ubuntu520.com/images/py9-8.webp)


## 原始字符串

有一些符号是代表特殊意义的，比如说 「\n」就代表换行。比如像这样：



print("小帅b\n我爱死你了。")



那么这时候在 Python 眼中就是：



小帅b

我爱死你了。

> ![](http://www.ubuntu520.com/images/py9-9.webp)

> ![这很好啊， Python 很聪明还帮忙换行啦！](http://www.ubuntu520.com/images/py9-10.webp)
>这很好啊， Python 很聪明还帮忙换行啦！

可是，有时候 Python 自作聪明了，比如说我们有这么一个在 c 盘下的一个叫做niubi的文件夹「C:\niubi」，那么我们这样打印的话：



print("C:\niubi")



结果你也知道了，路径被拆掉了。

> ![](http://www.ubuntu520.com/images/py9-11.webp)

这就尴尬了，不过还好，有个叫做原始字符串的东西，我们只要在前面加个「r」就相安无事了，这时候 Python 就知道，哦，原来你要的是原始字符串啊，那老子不帮你换行了，省的被说自作聪明。



我们只需要这样：



print(r"C:\niubi")

> ![](http://www.ubuntu520.com/images/py9-12.webp)

ok，Python基本数据类型之「字符串」就到这里，当然字符串的使用以后会经常用到的，对字符串的操作，字符串的序列，Unicode等是接下来需要了解使用的。


# Python 的控制流条件语句

## if...else

还记的你以前小学的时候老师问你用「如果...那么...否则...」来造句么？每当想起这个的时候，我就会想到费玉清老师的经典名句：



「你追我，如果你追到我，我就跟你嘿嘿嘿。」



那么在Python如何表示的呢？ 其实很简单，就是 if 和 else：

```python

    if 你追到我：   （如果的条件语句）

        我就跟你嘿嘿嘿  （如果为真，就执行这里）

    else ：           （否则）

        我就不跟你嘿嘿嘿  （如果为假，就执行这里）
```

## if...elif...else

此外，如果老师要你用「如果...否则如果..否则..」来造句的话，比如说：如果你很持久，那么我嫁给你，否则如果你很有钱，那么我考虑一下，否则滚蛋。那么对应于 python 来说就是：


```python

    if 你很持久：

        嫁给你

    elif 你很有钱：

        考虑一下

    else：

        滚蛋。
```


好了，我们已经知道怎么用 Python 去使用我们的条件语句了，那么如果你想开发一个猜数字的小程序对你来说不在话下了。


我们这就来开发一个「python猜数字小游戏」，首先我们自己在程序定义好一个数字，然后让用户去猜，如果猜中了我们就恭喜他，猜不中就告诉他猜的数字偏大还是偏小。

打开我们的idle，撸起我们的代码：



首先定义一个变量，把我们要被猜的数字先写好：



`number = 520`



接着让用户输入数字：



`guessNumber = int(input('请输入你要猜的数字： '))`



接着我们来判断：


```python

if guessNumber == number :

    print("哇塞，牛逼啊，这就被你猜中了")

elif guessNumber < number :

    print("你猜的数字小了，再往高了猜")

else :

    print("你猜的数字大了，再往低了猜")

```

> ![](http://www.ubuntu520.com/images/py10-1.webp)
> ![](http://www.ubuntu520.com/images/py10-2.webp)

## and

如果你想要一个又有钱又帅的男人，怎么用 python 表示呢？



可以这样：


```
if 有钱 and 帅 ：

    嫁给你。
```


在这里就用到了「and」这个逻辑符，就是并且的意思，如果有钱和帅同时成立，那么就执行 if 下的语句。如果他没钱，那么立即返回，不会再管他帅不帅了，不会去执行 if 下面的语句。


## or

那么这时候你可能会问：那么我想要嫁给一个有钱或者帅就行了，也就是满足其一我都嫁，怎么表示呢？



可以这样：


```
if 有钱 or 帅 ：

    嫁给你。
```


这里用到的「or」逻辑符，它代表的意思就是或者，如果他是一个有钱的人，那么就直接执行 if 下面的语句，不需要再去判断帅不帅了，如果他没钱，就会再去判断他帅不帅，如果帅才执行 if 下面的语句。

> ![虽然我没钱也不帅，但是我骚，可不可以嫁给我？](http://www.ubuntu520.com/images/py11-1.webp)
>虽然我没钱也不帅，但是我骚，可不可以嫁给我？

# Python中的循环语句

不知道你有没有听过这么个东西：除去睡眠，我们每个人只能活1万多天，有些人活了1万多次，而有些人呢，则只是活了1天，而重复了1万多次。



我希望我的读者不要成为后者，咱们每天提升自己一点点，活出个样子来。


> ![好阔怕，我不要重复~~](http://www.ubuntu520.com/images/py11-2.webp)
>好阔怕，我不要重复~~


在 Python 的世界里面，可以用 while 和 for 来表示重复，也就是循环。

## while循环

```
 while 活着：

    每天做着一样的事情。
```

这样写的意思就是，只要你活着，就一直不断的执行while下面的语句。



我们可以来写一个抛硬币的 python 程序，我们事先定义好硬币的正反面，然后让用户猜，如果用户猜对了就奖励一个吻，猜错了就继续猜，直到让他猜中为止。



打开我们的 IDLE，代码撸起来：



首先定义一个变量，我们的值定义为正面：



`coin = "正面"`



接着定义一个 flag ：



`flag = True`



然后我们写一个循环：



```

while flag :

    guess = input("请猜一下是正面还是反面：")

    if(guess == "反面") :
        print("你猜错了，继续猜")
    elif(guess == "正面") :
        print("恭喜你猜对了，奖励你一个吻")
        flag = False
```

> ![](http://www.ubuntu520.com/images/py11-3.webp)

执行：

> ![](http://www.ubuntu520.com/images/py11-4.webp)

解释一下：当 while 发现 flag 为 true 的时候，就会一次又一次的执行执行 while 下面的一句，直到我们猜中之后，我们就将flag 这个变量改为 false ，while 发现为 false 的时候就不往下循环了。


## for循环

while 可以做到在条件为真的时候反复的执行，不过有时候我们需要在特定范围循环，比如说我们要在第一天到第五天每天啪啪啪一次，那么这时候用 for 就再适合不过了：


```
days = [1,2,3,4,5]

for day in days :
    print("第" + str(day) + "天啪啪啪")
```

我们来运行下：

> ![](http://www.ubuntu520.com/images/py11-5.webp)

可以看到第一次执行，day就是1，第二次执行day就是2，它就这样一直循环下去，没有一点念想。

## 终止循环break

有一天你突然发现，我不能再这么下去了，不能再重复的过这样的日子了，得有点改变，跳出这个重复的怪圈，那么对于 Python 来说，用break：


```
while 活着：
    重复的过日子。
    if（醒悟）：
    break
```


通过 break 呢，就可以跳出这个循环了。

## continue

有时候我们在循环里面，在某个地方不希望它循环下去，先跳过本次接下来的东西，直接执行下一次，这时候我们就可以用 continue了，来试试：

> ![](http://www.ubuntu520.com/images/py11-6.webp)



# Python中的函数

你可以把函数当做是一个「特定的小程序」，可以用它们来执行特定的事情。



Python中有内置了许多「特定的小程序」，我们可以非常方便的直接调用它们来执行我们想要操作的东西，这叫内置函数。



另外我们也可以根据我们自己的需要来创造「特定的小程序」，这叫自定义函数。

## 定义函数

假设我们要自己定义一个函数，这个函数用来叫：亚麻跌，哈哈，想想我们一调用这个函数，它就叫「亚麻跌」。是不是很好玩。



像这样定义一个函数：


```
def jiao（）：
    print（"亚麻跌~~~"）
```


那么当我们要调用它的时候只要这样「jiao（）」就可以了。



用 IDLE 来试一试吧：


> ![](http://www.ubuntu520.com/images/py12-1.webp)
> ![](http://www.ubuntu520.com/images/py12-2.webp)

来解释一下：

```
def jiao（）：
    print（"亚麻跌~~~"）
```


这里的 def 就是一个关键字来的，代表我们要去定义一个函数，而 jiao 就是函数名称，当我们要使用这个函数的时候直接调用它就可以了。而  print（"亚麻跌~~~"） 就是**函数体**，也就是它所具备的功能实现。

## 函数的形参和实参

我们既然定义了一个会叫床的函数了，那么每调用一下它就叫一下是不是不太爽？如果我们能调用这个函数，然后传个数字给它，这个数字是多少，它就叫多少次，岂不是更好？

可以这样：


```
def jiao(times) :
    for time in range(times) :
        print("亚麻跌~~~")
```

在这里我们定义了一个 times 的参数，接下来我们通过这个range用内置函数生成一个序列，接着用 for 循环，这样子当我们调用函数并传一个数字进去，它就能根据这个数字，去叫相应的次数了。



比如我们调用 jiao（5），那么它就会叫 5 次。

> ![](http://www.ubuntu520.com/images/py12-3.webp)
> ![](http://www.ubuntu520.com/images/py12-4.webp)

那么如果我们想要用户输入多少次，就让它叫多少次，怎么玩呢？想必你看过之前的文章也知道怎么玩了：

> ![](http://www.ubuntu520.com/images/py12-5.webp)
> ![](http://www.ubuntu520.com/images/py12-6.webp)

可以看到我们这里的 jiao（int（time）） 传入的是一个变量，那么这样传递的参数叫做**形参**。而我们刚刚 jiao（5）传递的是一个实实在在的数字，我们叫**实参**。

## 局部变量和全局变量

我们在函数里面定义的变量，只有函数里面才可以用，在函数外面是使用不到这个变量的，所以这个变量存在函数这个局部里，我们叫这个变量为局部变量。

比如说：
```
def jiao(times):
    x = 1

    for time in range(times+x):
        print("亚麻跌~~~")
```


这里的x就是局部变量啦。



知道了什么是局部变量之后我们在来了解一下什么是全局变量，其实顾名思义，全局嘛~ 那么就是哪里都可以使用这个变量咯。比如说我们在函数内想要更改外边的变量，怎么办呢？这时候我们可以使用 global：


```
def jiao(times):

    global x
    x = 5

    for time in range(times+x):
        print("亚麻跌~~~")

x = 2
jiao(5)
```

那么这里 x 就是全局变量。

## return返回值

有时候我们需要调用一个函数返回给我们结果，比如我们定义了一个加法计算的函数，我们希望扔两个数给它，它直接计算好然后返回给我们，那么这时候我们就可以用到 return：



定义一个加法的函数，并返回结果：


```
def addition(x,y):
    return x+y
```


那么我们调用的时候：

`print(addition(5,6)) `

直接返回 11 。


## docString

很多程序员其实不太喜欢写文档的，因为觉得文档这事儿好像不关自己的事情，代码才是。老子写个代码而已，凭什么还要我写文档？



Python 有个叫做 docString 的东西完美解决了这问题，让你直接在代码中写文档，其实说白了就是给代码写点注释，什么语言都会有给代码写注释的，不过 Python 的 docString 可以直接把你的注释变成文档，是不是很厉害？

我们可以通过 help(requests) 或者 requests.__doc__ 就可以访问到它的文档了。



接下来我们自己写一个docString吧。



我们定义一个叫 myDoc 的函数，传入两个参数，再写一下docString，告诉别人我们的函数是干嘛的，传入的参数是什么，返回什么。

```
def myDoc(param1 ,param2):
    """
    this is myDoc function
    :param param1:  this is a first param
    :param param2: this is a second param
    :return: param1 + param2
    """
    print(param1 + param2)
    return param1 + param2
```

是不是一目了然。


而且我们还可以使用 sphinx 的 autodoc 自动从docString生产api文档。是不是很方便呢？

# 模块


你可以把模块理解为一个 .py文件，这个文件里面包含了所需要的函数和变量，那么下次我们任何一个程序要使用这里面的东西，我们只需要把这个模块导入到我们的程序里面来，就可以直接用了，简直不要太爽。造轮子多麻烦啊，拿来就用是了。

其实 Python 有内置了一些模块，我们可以直接引用，还有一些第三方模块，也就是我们可以自己创建模块，安装好模块就可以直接使用了。

## 使用模块

如果我们要使用一个模块，可以将这个模块导入，使用 import ，比如我们要导入 Python 的内置的 sys 模块（sys模块包含了与Python解释器和它的环境有关的函数），那么我们就可以使用 import sys:

> ![](http://www.ubuntu520.com/images/py13-1.webp)
> ![](http://www.ubuntu520.com/images/py13-2.webp)

## 创建自己的模块

创建自己的模块其实就是自己写了个程序，然后给别人import，我们来写一个模块：

> ![](http://www.ubuntu520.com/images/py13-3.webp)

记住，这模块要保存到和你即将要用的 Python 程序的同一目录下，然后这文件必须是 .py 结尾不用我说了吧。



接着我们就来使用我们自己的模块吧：

> ![](http://www.ubuntu520.com/images/py13-4.webp)

运行一下：

> ![](http://www.ubuntu520.com/images/py13-5.webp)

可以看到我们不仅会使用模块，而且会自己创建模块了，真是越来越牛逼了。


## 安装第三方模块

世界那么大，牛人那么多，牛人写的模块，我们直接拿来用，不是很爽吗？



那么我们要使用他们写的模块之前要先将他们的模块安装到我们的 Python 环境来，然后才可以使用。

首先你要确保你的电脑已经安装好了 pip，如果你在命令行工具中输入 pip 可以像我这样那就说明你已经安装好了 pip：

> ![](http://www.ubuntu520.com/images/py13-6.webp)

推荐一个网站给你们：https://pypi.org/ 这个网站聚集了一堆牛逼的模块，你可以通过搜索任何你想要的模块：

> ![](http://www.ubuntu520.com/images/py13-7.webp)

比如说我要安装一个叫做 BTrees 的模块，那么我只需要使用「pip install BTrees」  这个命令就可以安装了。

> ![](http://www.ubuntu520.com/images/py13-8.webp)

安装完之后呢，你就可以通过 import 直接使用模块了。


# 面向对象

## python创建一个类

为了让你更好的理解类和对象，我来举一个例子，哆啦A梦大家都很熟悉吧，那个矮胖矮胖的家伙，口袋里面有着许多我们梦寐以求的东西。



我们可以把哆啦A梦理解为它是一个对象。如果我们创建一个叫做哆啦A梦的类，那么这个类的实例，我们就叫做哆啦A梦对象。



在 python 中，可以用 class 来定义一个类，比如：


```
class DuoLaAMeng：
```


那么当我们要去使用这个类的对象的时候我们可以这样：


```
duola = DuoLaAMeng（）
```


在这里呢，我们定义了一个叫做 duola 的变量，指向的是哆啦A梦这个实例。

## 类中的方法使用

我们的对象肯定是有一些属性给我们用的，比如说哆啦A梦这个对象可以给我们提供竹蜻蜓，所以我们可以在类中定义一些方法给别人去使用。



我们创建一个类，并且给它定义一个获取竹蜻蜓的方法：


```
class DuoLaAMeng:
    def getZhuQingTing(self):
        print("给一个竹蜻蜓")
```


那么当我们要调用的时候就可以这样子：


```
duola = DuoLaAMeng()
duola.getZhuQingTing()
```


我们可以看到在定义 getZhuQingTing 这个方法的时候，定义了一个 self 这个参数，其实这个参数指的是DuoLaAMeng对象本身，这就和我们普通定义的函数有些许区别。


## __init__函数

我们在调用对象的时候，有些东西是可以初始化的，这个时候 Python 就给我们提供了一个初始化函数，也就是当我们去调用这个对象的时候，它会先去执行 __init__ 这个函数。举个例子你就明白了：

```
class DuoLaAMeng:
    def __init__(self, name):
        self.name = name

    def getZhuQingTing(self):
        print("给"+self.name+"一个竹蜻蜓")

duola = DuoLaAMeng("大雄")
duola.getZhuQingTing()
```

我们定义了一个 DuoLaAMeng 类， 并且给了一个初始化函数，当别人调用这个类的时候呢，传一个 name 进来，我们就可以对这个名字进行初始化了。

> ![](http://www.ubuntu520.com/images/py14-1.webp)

## 继承

如果我们想要再定义一个类似哆啦A梦的对象，比如说哆啦A梦的儿子对象，那么这时候我们用继承来实现，继承就是实现代码重用的方式。



如果说哆啦A梦的儿子叫做哆啦B梦，那么当我们的哆啦B梦继承了它的爸爸哆啦A梦的时候，哆啦B梦拥有哆啦A梦的所有功能。

> ![](http://www.ubuntu520.com/images/py14-2.webp)

在 Python 中继承的表现形式只这样的：


```
class 哆啦B梦（哆啦A梦）：
```


这样就说明了哆啦B梦是哆啦A梦的儿子。



举个例子：

> ![](http://www.ubuntu520.com/images/py14-3.webp)
> ![](http://www.ubuntu520.com/images/py14-4.webp)

我们在这里定义了一个叫做 DuoLaAMeng 的类，然后定义了两个方法，一个是初始化，一个是获取竹蜻蜓。



接着我们创建了 DuoLaBMeng 这个类来继承 DuoLaAMeng ，可以看到 DuoLaBMeng 其实啥也没做，但是它就是拥有了DuoLaBMeng 的所有功能。



这种继承的方式很好，比如我们以后要创建 DuoLaCMeng ，直接继承 DuoLaAMeng 就可以用所属的方法，以后我们要增加什么共同的功能的时候，只需要在父类 DuoLaAMeng 添加就好了，它的子类们都可以使用。

## 多态

DuoLaBMeng 和 DuoLaCMeng 是 DuoLaAMeng 的儿子，我们也可以把它的儿子当做 DuoLaAMeng 对象来使用，比如说有一天 DuoLaAMeng在忙，这时候大雄完全可以把它的儿子们当做是 DuoLaAMeng 来使用，完全木有问题，这就是面向对象中多态的意思。

> ![](http://www.ubuntu520.com/images/py14-5.webp)

但是有些子类是独具特色的，比如 DuoLaBMeng 可以从口袋中拿出充气娃娃，而它的父亲 DuoLaAMeng 没有这个功能。

> ![](http://www.ubuntu520.com/images/py14-6.webp)

这时候父类 DuoLaAMeng 是不可以把它当做子类DuoLaBMeng 来用的，也就是子类可以用父类的方法，但是父类不能用子类的方法。

> ![](http://www.ubuntu520.com/images/py14-7.webp)
> ![](http://www.ubuntu520.com/images/py14-8.webp)

# 异常

知道代码有错还狂往下写？是的没错，就是明明知道可能代码会有错误，但是我们还是往下写。就是这么任性！

## 异常捕获

有时候我们对我们的代码的报错是可预知的，比如我们想让 Python 帮我们打开一个小黄文的文件，比如 yellow.txt，可是我们的电脑不一定有，如果这个时候没有的话我们的代码会报错的对吧？

```
document = open('yellow.txt')
print('filename:' + document.name)
```

运行之后可以看到这里报错:

```
FileNotFoundError: [Errno 2] No such file or directory: 'yellow.txt'
```

告诉我们没有这个文件。



但是如果这时候我们还想往下运行怎么办呢？



那就可以把这异常给捕获掉，使用 `try...except...finally...`


>try：用来包裹我们可能存在错误的代码；
except：当发现错了就会执行这里
finally：无论怎么样最后都会执行到的。


举个例子你就明白了：
```
try:
    document = open('yellow.txt')
    print('filename:' + document.name)
except FileNotFoundError as e:
    print("error:" , e)
finally:
    print("最后执行的语句")
```

我们这里打开 yellow.txt ,Python发现不存在，那么就执行except下的语句，finally最后也会被执行：

```
error: [Errno 2] No such file or directory: 'yellow.txt'
最后执行的语句
```

那么这样子的话，以后我们就可以将预料到的错误进行捕获，然后对其进行操作。

## 抛出异常

有时候我们没有去处理异常， Python 也会给我们报出错误，这是因为 Python 有个 BaseException 的异常基类，当Python发现我们的代码错误的时候，又没人去处理，它就会层层的往上抛出错误，直到最上级。

我们可以自己定义一个异常类：

```
class MyError(Exception):
    pass

def foo(value):
    if(value==0):
        raise MyError('ERROR %s' % value)

foo(0)
```
可以看到我们自定义了一个叫做MyError的异常类，继承与Exception，当我们传入 0 的时候就会抛出异常。在这里我们使用到的**关键字是raise，就是用来抛出异常的意思**。

放个异常让你心情疙瘩一下，哈哈哈：

```
Traceback (most recent call last):
  File "G:/test.py", line 11, in <module>
    foo(0)
  File "G:/test.py", line 9, in foo
    raise MyError('ERROR %s' % value)
__main__.MyError: ERROR 0
```

ok，有了这两招，妈妈再也不用担心，我错误的代码该如何安放了。

# python 中的数据结构

什么是数据结构呢？就是存储一组相关数据的结构。



在 python 里面呢，有几种内置好了的数据结构，比如「列表」、「元组」、「字典」、「集合」。

## 列表


我们应该都很熟悉列表吧，一个列表里面，有多个列表项，每一项就是具体的内容：

> ![](http://www.ubuntu520.com/images/py15-1.webp)

看，这个列表是不是很熟悉？那么在 python 中要表示一个列表可以用到 list 这个对象。例如：



`avlist = ['亞洲無碼原創區','亞洲有碼原創區','歐美原創區','動漫原創區']`



可以看到，我们用中括号把每个列表项的内容用逗号隔开，就成了一个 list 对象，然后我们将这个对象赋值给 avlist 这个变量。

在 python 中想要知道怎么运用 list 这个对象，我们可以在python 解释器中输入 help(list) 得到帮助：


> ![](http://www.ubuntu520.com/images/py15-2.webp)

来看看这里例子怎么使用 list 的吧：


> ![](http://www.ubuntu520.com/images/py15-3.webp)


运行一下：

> ![](http://www.ubuntu520.com/images/py15-4.webp)

讲讲过程：

> 首先我们定义了一个叫做 avlist 的列表对象，这个列表中有一些内容 ['亞洲無碼原創區' ,'亞洲有碼原創區' ,'歐美原創區' ,'動漫原創區' ]



> 我们通过 len 这个列表对象的方法可以得到列表中的条目数。



> 可以通过 for 循环来获取列表中每一个项的内容。



> 我们可以通过 append 方法在列表中添加条目。



> 使用了 sort 对列表中的内容进行排序。



> 列表中的内容可以通过下标索引获取，从0开始，例如avlist[0] 就是获取avlist这个列表的第一个条目。


通过上面我们可以看到， list 这个列表对象是可变的数据类型，什么意思呢？就是我们可以对列表里面的内容进行修改，删除，添加等操作。

## 元组

其实元组和列表是差不多的，不过它们有一点区别就是：元组是不可变的数据类型，也就是说元组里面的内容是不能进行修改，删除，添加等操作的。



元组使用圆括号来表示，例如：avlist = （'亞洲無碼原創區' ,'亞洲有碼原創區' ,'歐美原創區' ,'動漫原創區' ）



元组通常被用来打印语句：

> ![](http://www.ubuntu520.com/images/py15-5.webp)
> ![](http://www.ubuntu520.com/images/py15-6.webp)

## 字典

如果你想描述 苍井空 的特点是怎么样怎么样，波多野结衣的特点是怎么样怎么样，那么你就可以用到字典啦。



字典是以键和值组成的，键呢，是不可变的，而值可变。



字典的表示如下：



nvyou = {'苍井空':'美丽大方'，'波多野结衣':'身材特好'}



接下来看看怎么使用字典吧：

> ![](http://www.ubuntu520.com/images/py15-7.webp)
> ![](http://www.ubuntu520.com/images/py15-8.webp)

可以看到，我们可以通过字典对象用[键]来获取对应的值，也可以往字典里面添加数据，我们可以用字典的items（）方法获取字典中的具体内容。


# 序列

我们之前所说的 列表，元组都是序列，序列还有一个叫做 字符串，为什么它们会被叫做序列呢？



那是因为它们有一些特别的地方，比如：索引，切片，相加相乘，成员资格。

## 索引

对于序列来说，序列里面的每个元素都有一个编号，而这个编号是从 0 开始的，例如下面的这个序列，第 0 号就是：亞洲無碼原創區，第 1 号就是亞洲有碼原創區，以此类推。

> ![](http://www.ubuntu520.com/images/py16-1.webp)

这里我们所说的编号就是索引，我们可以通过索引去获取列表的具体想要的内容，如果我们的索引是负数的时候，那么 Python 就会从序列的最后一个元素开始数起，比如说上面这个序列，如果我们用索引  -1 ，那么就可以获取得到「在线成人电影」这个元素。

> ![](http://www.ubuntu520.com/images/py16-2.webp)

## 切片

可能你这时候想说了，我用索引只能获取到一个元素，那如果我想在一个序列里面获取部分元素怎么玩？那么这时候就可以用切片来获取。



比如 `[1:3]`，就代表我要获取序列中第一个元素（包含）到第三个元素（不包含）的所有内容：



这里定义一个列表：



`avlist = ['亞洲無碼原創區','亞洲有碼原創區','歐美原創區','動漫原創區']`



然后我们通过 `avlist[1:3]` 就可以获取到：



`['亞洲有碼原創區', '歐美原創區']`





切片最常用的还是在使用字符串这个序列中，比如：


```
url = input("请输入你的网站：")
print("主机名是："+ url[11:-4])
```


在这里我们就可以通过切片的方式，来获取字符串这个序列的部分内容，比如这里我们输入：`http://www.google.com`，那么这个时候我们就可以获取到[11:-4]之间的内容，也就是 google。




切片还有个叫做步长的东西，还是拿刚刚那个序列为例：



`avlist = ['亞洲無碼原創區','亞洲有碼原創區','歐美原創區','動漫原創區','國產原創區','在綫成人影院 ']`



在这个序列中我们如果通过 `avlist[1,-1]`，那么python会从第一个元素逐一的去获取范围内的内容，也就是一步一步一个脚印的获取，那如果我们想要让它的步伐跨的大一点呢？每一步跨两个元素，那就可以这样：

> ![](http://www.ubuntu520.com/images/py16-3.webp)

## 相加相乘

序列是可以相加相乘的，比如我们之前在说Python : Hello World !中就知道了字符串的拼接，其实就是序列的相加。

> ![](http://www.ubuntu520.com/images/py16-4.webp)
> ![](http://www.ubuntu520.com/images/py16-5.webp)
> ![](http://www.ubuntu520.com/images/py16-6.webp)

## 成员资格

如果我们想要判断一个元素是不是在这个列表中，那么我们就可以用到 in 这个关键字，如果存在的话， python 就会给我们返回 True ，如果不存在的话，那么 Python 就会给我们返回 Fasle：

> ![](http://www.ubuntu520.com/images/py16-7.webp)

# Python中的IO

我们到时候肯定是需要用到对文件进行读写操作的，也就是IO，但是我们不能直接去操作文件，我们需要去告诉操作系统，我们想操作什么文件，然后操作系统帮我们操作。


## 读取文件

我们先创建个叫做 xiaohuangwen.txt 的文件吧：

> ![](http://www.ubuntu520.com/images/py17-02.webp)

python有个内置的函数叫做 open() , 我们可以通过它直接打开文件，打开完文件就可以读取了，但是有可能会报错，就是文件不存在，这个时候我们可以用到上次说的 try...finally 来处理异常：

```
try:
    f = open("G:/xiaohuangwen.txt","r",encoding="UTF-8")
    print(f.read())
finally:
    if f:
        f.close()
```

我们通过 open 打开了 xiaohuangwen.txt 这个文件。 r 就是读的意思， encoding就是定义好文件编码。



接着我们就打印出我们 read 出来的文件啦：


> ![](http://www.ubuntu520.com/images/py17-03.webp)


最后一定要记得将文件 close 掉，这样才不会造成系统浪费资源。



有时候你在读取文件的时候，是不是觉得每次都要 try...finally 很麻烦？ 贴心的 Python 帮我们简化了流程，我们只要直接这样写就可以了：

```
with open("G:/spider/xiaohuangwen.txt","r",encoding="UTF-8") as f:
    print(f.read())
```

是不是简化了很多？？

## 写入文件

写入文件内容也是一个道理，我们首先要打开文件，然后往里写内容，如果我们传入的参数是 ‘w’ 的话，它会覆盖原来的文件，而我们传入 ‘a’ 则可以在文件末尾追加内容：

```
with open("G:/spider/xiaohuangwen.txt","a",encoding="UTF-8") as f:
    print(f.write("\n我想看苍老师啊！"))
```

ok，运行之后你会发现，你已经把内容写进去了，是不是很简单？

> ![](http://www.ubuntu520.com/images/py17-02.webp)


## 文件存储器

Python 有一个叫做 pickle 的模块，有了它，我们就可以在一个文件中持久的存储我们的女朋友，哦，不是，可以持久的存储我们的对象。



还有一个叫做 cPickle 的模块，它是用 C 写的，所以它更加牛逼一点，比 pickle 速度快，要快上 1000 倍，所以我么用 cPickle 这个模块会好点。



不过在 Python3 已经将 cPickle 改名为 pickle 了，所以我们就可以直接 import pickle 就可以啦。



写个文件存储器的例子：


```
import pickle as p


# 我们要存储内容的文件名
girlfriendlistfile = 'girlfriend.data'

girlfriends = ['波多野结衣', '苍井空', '小泽玛利亚']

# 把我们的女朋友写到文件里，然后存储器存储
with open(girlfriendlistfile,'wb+') as f:
    p.dump(girlfriends, f)
    f.close()

del girlfriends # 删掉我们的女朋友

# 把我们的女朋友读回来！！
with open(girlfriendlistfile,'rb+') as f:
    list = p.load(f)
    print (list)
```
这就是存储器的使用，是不是so easy？


# 用python给自己写一个操作界面

Python 有一个自带的库叫做 tkinter ，用它我们可以写出系统的操作界面，不管你是 Mac OS 系统，还是 Windows 系统，它都可以生成相对应的操作界面。这就是所谓的跨平台。

> ![](http://www.ubuntu520.com/images/py18-01.webp)


原理就是我们使用 Python 的代码去调用 Tkinter， Tkinter 已经封装了访问TK的接口，这个接口是一个图形库，支持多个操作系统，通过它我们就可以调用我们系统本身的GUI接口了。



接下来我们用代码玩一下吧：

```
from tkinter import *
import tkinter.messagebox as messagebox

class MyApp(Frame):

    def __init__(self,master=None):
        Frame.__init__(self,master)
        self.pack()
        self.createWidgets()

    def createWidgets(self):
        self.helloLabel = Label(self,text="世界上最帅的人是谁？")
        self.helloLabel.pack()
        self.quitButton = Button(self,text="谁呢？",command=self.who)
        self.quitButton.pack()

    def who(self):
        messagebox.showinfo("答案","当然是小帅b啦")


myapp = MyApp()
myapp.master.title('hello')
myapp.mainloop()
```

在这里：



1. 我们导入了 tkinter 的相关模块



2. 定义了初始化函数，通过 pack（） 方法将我们的组件传给父容器



3. 自定义一个创建组件的方法，我们创建了一个标签和一个按钮，这个按钮被点击后就会触发 who 这个方法



4. 我们通过 messagebox 来显示一个提示框



5. 实例化我们的 APP，然后通过主线程来监听我们的界面操作


运行后如下：
> ![](http://www.ubuntu520.com/images/py18-02.webp)
> ![](http://www.ubuntu520.com/images/py18-03.webp)


# Python的互联网编程

> ![你怎么还在用Python写的单机版程序？](http://www.ubuntu520.com/images/py5.jpg)
>你怎么还在用Python写的单机版程序？

> ![因为我现在才刚学不久](http://www.ubuntu520.com/images/py2.png)
>因为我现在才刚学不久

> ![现在开发的基本上都是互联网程序了，你要不要跟我一起学一下用Python网络编程？](http://www.ubuntu520.com/images/py5.jpg)
>现在开发的基本上都是互联网程序了，你要不要跟我一起学一下用Python网络编程？

> ![哇！真的吗？大佬求带！](http://www.ubuntu520.com/images/py2.png)
>哇！真的吗？大佬求带！

> ![低调低调，说到网络编程，那么我们先要了解互联网。](http://www.ubuntu520.com/images/py5.jpg)
>低调低调，说到网络编程，那么我们先要了解互联网。

> ![我了解，互联网就是把许多网络连接起来。](http://www.ubuntu520.com/images/py2.png)
>我了解，互联网就是把许多网络连接起来。

> ![恩，不错，那你知道什么是TCP，UDP吗？](http://www.ubuntu520.com/images/py5.jpg)
>恩，不错，那你知道什么是TCP，UDP吗？

> ![em，以前听过，现在有点忘了，你可以给我说道说道吗？](http://www.ubuntu520.com/images/py2.png)
>em，以前听过，现在有点忘了，你可以给我说道说道吗？

> ![可以，我们以前的计算机网络，为了能够互相通信，很多厂商都有自己的一套协议，这就弄得很乱，因为互不兼容，所以通信起来很费劲。后来呢，为了让成千上万的计算机连接起来，定义了两个标准的协议，一个是TCP，一个是 IP，也就是我们现在简称的 TCP/IP 协议。](http://www.ubuntu520.com/images/py5.jpg)
>可以，我们以前的计算机网络，为了能够互相通信，很多厂商都有自己的一套协议，这就弄得很乱，因为互不兼容，所以通信起来很费劲。后来呢，为了让成千上万的计算机连接起来，定义了两个标准的协议，一个是TCP，一个是 IP，也就是我们现在简称的 TCP/IP 协议。

> ![也就是说我们遵循 TCP/IP 协议就可以互联了是吧！](http://www.ubuntu520.com/images/py2.png)
>也就是说我们遵循 TCP/IP 协议就可以互联了是吧！

> ![恩，通信的时候，双方要知道对方的标识，才能通信。](http://www.ubuntu520.com/images/py5.jpg)
>恩，通信的时候，双方要知道对方的标识，才能通信。

> ![那。。大佬能告诉我下 TCP 和 IP 的区别吗？](http://www.ubuntu520.com/images/py2.png)
>那。。大佬能告诉我下 TCP 和 IP 的区别吗？

> ![当然可以，那我先告诉你 IP 协议吧，假如我要发信息给你，我们都在互联网上，都有自己的 IP 地址和路由，那么当我发信息给你的时候呢，IP 协议就负责将数据进行传输，这些数据被分割成一小块一小块的，通过 IP 包给发送过去。因为们之间在互联网上是有很多链路的，所以路由就会将一小块一小块的数据包逐个进行转发，直到发送到你的IP地址。但是它不能够保证数据都能到达，也保证不了能够按顺序的到达。](http://www.ubuntu520.com/images/py5.jpg)
>当然可以，那我先告诉你 IP 协议吧，假如我要发信息给你，我们都在互联网上，都有自己的 IP 地址和路由，那么当我发信息给你的时候呢，IP 协议就负责将数据进行传输，这些数据被分割成一小块一小块的，通过 IP 包给发送过去。因为们之间在互联网上是有很多链路的，所以路由就会将一小块一小块的数据包逐个进行转发，直到发送到你的IP地址。但是它不能够保证数据都能到达，也保证不了能够按顺序的到达。

> ![啊~那如果丢失怎么办？有什么办法吗？](http://www.ubuntu520.com/images/py2.png)
>啊~那如果丢失怎么办？有什么办法吗？

> ![有！那就是 TCP 协议，TCP协议建立在IP协议之上的。TCP协议会建立可靠连接，保证数据包按顺序到达。TCP协议会通过握手建立连接，确保对方按顺序收到，如果包丢掉了，就自动的重新再发。](http://www.ubuntu520.com/images/py5.jpg)
>有！那就是 TCP 协议，TCP协议建立在IP协议之上的。TCP协议会建立可靠连接，保证数据包按顺序到达。TCP协议会通过握手建立连接，确保对方按顺序收到，如果包丢掉了，就自动的重新再发。

> ![哦，明白了，那刚刚你说的 UDP 又是？](http://www.ubuntu520.com/images/py2.png)
>哦，明白了，那刚刚你说的 UDP 又是？

> ![ 我们已经知道了 TCP 是面向连接的，比较可靠，而UDP协议呢，它是面向无连接的，也就是我只要知道你的IP地址和端口就可以直接给你发送数据了，不需要先跟你握手，不过数据能不能到达就不知道了。](http://www.ubuntu520.com/images/py5.jpg)
>我们已经知道了 TCP 是面向连接的，比较可靠，而UDP协议呢，它是面向无连接的，也就是我只要知道你的IP地址和端口就可以直接给你发送数据了，不需要先跟你握手，不过数据能不能到达就不知道了。

> ![哦，明白，就是TCP可靠，UDP传输效率高。](http://www.ubuntu520.com/images/py2.png)
>哦，明白，就是TCP可靠，UDP传输效率高。

> ![对头，所以呢，如果不要求数据可靠到达的话就可以用UDP。那么接下来我们就用 Python 来进行 TCP 和 UDP 的编程吧。](http://www.ubuntu520.com/images/py5.jpg)
>对头，所以呢，如果不要求数据可靠到达的话就可以用UDP。那么接下来我们就用 Python 来进行 TCP 和 UDP 的编程吧。

> ![太好了！！](http://www.ubuntu520.com/images/py2.png)
>太好了！！

> ![不过在此之前跟你讲一下 Socket 的东西，因为等下我们要用到，Socket 在互联网编程中表示建立了一个互联网连接，Socket知道了对方的IP地址、端口号、协议，就可以建立连接了。](http://www.ubuntu520.com/images/py5.jpg)
>不过在此之前跟你讲一下 Socket 的东西，因为等下我们要用到，Socket 在互联网编程中表示建立了一个互联网连接，Socket知道了对方的IP地址、端口号、协议，就可以建立连接了。

> ![恩，感谢大佬，明白了。](http://www.ubuntu520.com/images/py2.png)
>恩，感谢大佬，明白了。


##  Python 中的 TCP 编程
###TCP客户端的编写
我们现在访问一些网页什么的，这些网页是在服务器端的，而我们访问的设备属于客户端。



比如我们现在通过浏览器访问这个地址：



http://www.meizitu.com/



那么会得到好多小姐姐的图片哈哈：

> ![](http://www.ubuntu520.com/images/19-01.webp)

那么我们怎么通过 Python 来建立可靠的 TCP 连接，获取到这些图片呢？

```
# 导入socket这个库
import socket

# 创建一个socket对象
s = socket.socket(socket.AF_INET,socket.SOCK_STREAM)
# 开始建立TCP连接
s.connect(("www.meizitu.com",80))
# 连接后，发送请求
s.send(b'GET / HTTP/1.1\r\nHost: www.meizitu.com\r\nConnection: close\r\n\r\n')
# 接收数据
buffer = []
while True:
    d = s.recv(1024)
    if d:
        buffer.append(d)
    else:
        break
# 把字节连接起来
data = b''.join(buffer)

# 关闭连接
s.close()

# 把数据读取出来

with open('meizi.html','wb') as f:
    f.write(data)

```

运行之后，我么就有了咱们的妹纸文件：
> ![](http://www.ubuntu520.com/images/19-02.webp)

打开有惊喜。

### TCP 服务端的编写

服务端一般都是一直在运行着的，等待着客户端来连接，然后给出请求响应，服务端需要提供 ip 地址和端口给客户端去连接。



首先我们来写一个简单服务端的：

```
import socket

# 创建socket对象
s = socket.socket(socket.AF_INET,socket.SOCK_STREAM)

# 绑定监听端口
s.bind(('127.0.0.1',8888))

# 监听
s.listen(1)

while True:
    # 接收连接
   sock,addr = s.accept()
    print("有人连进来了")
    sock.send(b'hei man, are you ok?')
    sock.close
```
当有人连接进来我们就给他发一句：hei man，are you ok ？



接着我们再来写个客户端的连接过去：
```
# 导入socket这个库
import socket

# 创建一个socket对象
s = socket.socket(socket.AF_INET,socket.SOCK_STREAM)
# 开始建立TCP连接
s.connect(("127.0.0.1",8888))
# 接收数据
buffer = []
d = s.recv(1024)
buffer.append(d)

# 把字节连接起来
data = b''.join(buffer)
print(data)

# 关闭连接
s.close()
```
然后先运行我们的服务端，再运行客户端：

> ![](http://www.ubuntu520.com/images/19-03.webp)
> ![](http://www.ubuntu520.com/images/19-04.webp)

## Python中的 UDP 编程

我们来先写服务端：

```
import socket

# 创建socket对象,这里传入的是SOCK_DGRAM，代表UDP
s = socket.socket(socket.AF_INET,socket.SOCK_DGRAM)

# 绑定监听端口
s.bind(('127.0.0.1',8090))

while True:
    # 接收连接
   data,addr = s.recvfrom(1024)
    print(addr)
    s.sendto(b'hei man, are you ok?',addr)
```

可以看到，在这里我们不需要跟对方连接，只要知道地址就直接发送过去就可以了。

客户端：

```
import socket

# 创建一个socket对象
s = socket.socket(socket.AF_INET,socket.SOCK_DGRAM)

s.sendto(b'ha',("127.0.0.1",8090))
# 接收数据
print(s.recv(1024).decode('utf-8'))

# 关闭连接
s.close()
```

运行如下：
> ![](http://www.ubuntu520.com/images/19-05.webp)
> ![](http://www.ubuntu520.com/images/19-06.webp)

# 把你的Python程序打包成exe可执行文件

你可以把自己写好的脚本 py 文件打包成 exe 给朋友使用。

在这里呢，以一个写好了的爬取妹纸的脚本为例，我们要使用 PyInstaller 来将我们的爬取小程序打包成一个 exe 执行文件，然后在没有安装 python 环境的情况下也可以双击直接运行。

首先我们要通过 pip 来安装 PyInstaller。

```
pip install pyinstaller
```

可以先去喝杯茶，等它一顿安装：
> ![](http://www.ubuntu520.com/images/pp5.webp)

喝完茶，差不多也安装完成了。



我们可以使用 Pyinstaller 的 F 选项来打包：

> -F, --onefile         Create a one-file bundled executable.

以我们的爬虫小程序为例，我们要将其打包成一个 exe ，那么我们就可以这样：

pyinstaller -F .\meizi.py

这里的 meizi.py 就是我们的项目名称。在执行的时候，Pyinstall帮我们在当前目录创建了 meizi.spec、build文件夹、dist文件夹、__pycache__文件夹。


> ![](http://www.ubuntu520.com/images/pp6.webp)

双击dist文件夹进去一看，你会发现有一个exe执行文件。它就是一个应用程序啦。

> ![](http://www.ubuntu520.com/images/pp7.webp)

接着我们双击一下，就开始运行啦~

> ![](http://www.ubuntu520.com/images/pp8.webp)

可以看到它按我们的程序执行，创建了一个 meizi 的文件夹，并且去妹子网站爬取美女图片然后下载到我们这个文件夹里面。



爽！！！



打开我们的meizi文件夹，看看图片爬的怎么样了：
> ![](http://www.ubuntu520.com/images/pp9.webp)

(完)

# 写在最后

你能看到这里也是厉害的了，没关注我的记得关注我呀，我的微信：xsb_pro(备注读者就可以通过)。

感到意犹未尽？

上面的教程只是带你入门，其实 Python 还有很多好玩的地方，如果你感兴趣，欢迎加入我的 VIP 课程，在这里我给你提供了更多 Python 进阶的知识点，思维导图，还有一些项目练习等等，最近我就在里面更新《使用 Python 开发自己的人生管理系统》教程，为的是让你可以让自己的想法通过自己的双手实现出来！
详情点击：[通往 Python 高手之路](https://mp.weixin.qq.com/s?__biz=Mzg2NzYyNjg2Nw==&mid=2247490010&idx=1&sn=ae6843b25a5e112eac3df0c4aaeced49&chksm=ceb9e3c6f9ce6ad04fc8f05b10d0b5a2b31944c20c77ea794bfc1d07d190f0d73885af2182eb&token=1031215785&lang=zh_CN#rd)

加入学习一段时间后，我[公众号的这些教程](https://mp.weixin.qq.com/s?__biz=Mzg2NzYyNjg2Nw==&mid=2247490309&idx=1&sn=146137dccc36f76c43dbf092a10f0d4a&chksm=ceb9e119f9ce680fe3441d2fe39cdef1f195d57a97f081cfefca6a4e7fc3669d7fbc2373ed74&token=1031215785&lang=zh_CN#rd)你会很容易看懂。
