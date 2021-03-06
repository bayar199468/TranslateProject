# 7款最佳的Linux电子书神器 #

**摘要：**本文中，我们将列举linux平台上的一些最好用的电子书软件。这些软件能提供良好的阅读体验，同时能够帮助管理你的电子书。

![][1]

最近，随着人们意识到用手持电子设备阅读更加舒适(比如kindle或PC)，阅读电子书的需求与日俱增。当谈到Linux用户时，市场上有很多app能够方便我们阅读和管理电子书。
在本文中，我们列举了7个最佳Linux电子书阅读神器。这些神器良好适配了pdf,epubs以及其他的电子书格式。

## 最佳linux电子书阅读神器 ##

正如我现在使用Ubuntu,我提供了在Unbutu上安装命令.如果您使用[非ubuntu Linux发行版][2]，您可以在发行版的软件存储库中找到这些电子书app。

### 1.Calibre ###

[Calibre][3]是最受用欢迎的电子书app之一，坦白说，它并不仅仅是简单的电子书阅读神器。它是一个完整的电子书解决方案。你甚至可以[在Calibre上编撰专业电子书][4]。
凭借强大的电子书管理功能和简易的用户界面，在电子书制作和编撰过程中到重要作用。Calibre支持多种格式，而且还可以与其他电子书阅读神器进行同步。它可以轻易地将一种电子书格式转换为其他格式。
Calibre最大的缺点就是它对资源的消耗太大，这使得它作为一个单独的电子书阅读器是一个艰难的选择。

![PIC][5]

**特点**

- 管理电子书:Calibre可以通过管理元数据对电子书进行排序和分组。你可以从各种来源下载电子书的元数据，或者创建和编辑现有字段。
- 支持所有主流电子书格式:Calibre支持所有主流子书格式，并兼容各种电子阅读器。
- 文件转换:您可以将任何电子书格式转换成另一种格式，您可以选择更改图书样式、创建内容表或在转换时提高页边距。你也可以把你的个人文件转换成电子书。
- 从网上下载杂志:Calibre可以通过各种新闻来源或RSS feed发布新闻。
- 共享和备份你的图书馆:它提供了一个选择-托管你保存在其服务器上的电子书，随时随地使用任何设备都可以与你的朋友分享。备份和导入/导出功能向你保证了已有收集资源的安全性和简易的可移植性。

**安装**

您可以在所有主要Linux发行版的软件存储库中找到它。对于Ubuntu，在软件中心中搜索或者使用下面的命令:

```
sudo apt-get install calibre
```

### 2.FBReader ###

![PIC][6]


[FBReader][7]是一个开源、轻量级、多平台的电子书阅读器，支持各种格式，如ePub、fb2、mobi、rtf、html等。它的强大之处包括能够访问主流的在线图书馆，在上面你可以免费下载或购买电子书。

FBReader非常人性化，你可以定制颜色，字体，翻页动画，书签和字典。

**特点**

- 支持各种文件格式和设备，如Android, iOS, Windows, Mac甚至其他设备。
- 同步图书收集、阅读位置和书签。
- 通过在所有设备中添加Linux桌面的任何图书，在线管理你的图书库。
- 可使用浏览器访问已收藏的资源。
- 支持在谷歌云盘（Google Drive)中存储图书，并根据作者、系列或其他属性管理图书。

**安装**

您可以从官方仓库安装FBReader电子书阅读器，或者在终端窗口中输入以下命令。

```
sudo apt-get install fbreader
```

或者，您可以从[这里][8]获取一个.deb包，并将其安装到基于Debian的发行版上。

### 3.Okular###

[Okular][9]是KDE开发的另一个开源跨平台文档查看器，作为KDE app版本的一部分发布。

![Okular][10]

**特点**

- Okular支持PDF、Postscript、DjVu、CHM、XPS、ePub等多种文档格式。
- 支持的功能包括评论PDF文档，高亮显示和绘制不同的形状等。
- 上述修改是单独保存的，无需修改原始PDF文件。
- 电子书上的文本可以提取到一个文本文件，并有一个称为Jovie的内置文本阅读服务。

**注意**:在检查app时，我发现这个app不支持Ubuntu及其衍生工具中的ePub文件格式。其他发行版用户仍然可以充分利用它的潜力。

**安装**

Ubuntu用户可以在终端输入以下命令进行安装:

```
sudo apt-get install okular
```

### 4. Lucidor ###


Lucidor是一款支持epub文件格式和OPDS目录格式的电子书阅读神器。它还具有在本地书库中管理已有电子书、从网上搜索并下载以及将web feed和网页转换为电子书的功能。

Lucidor是[XULRunner][11] app，它提供了一个带有标签布局的Firefox外观，并且在存储数据和配置时表现与之类似。它是这份清单中最简单的电子书阅读神器，包括文本对齐和滚动选项等配置。

![lucidor][12]


您可以通过选择一个单词并右键单击 > 查找单词选项来查找Wiktionary.org中的定义。它还包括作为电子书的Web Feed或网页的选项。

您可以从[这里][13]下载并安装deb或RPM包.

### 5. Bookworm ###

![Bookworm][14]

Bookworm是另一个免费且开源的电子书阅读神器，支持epub、pdf、mobi、cbr和cbz等不同的文件格式。我写了一篇关于Bookworm app的特点和安装的文章，请在这里阅读:Bookworm:[一个简单而又出色的Linux电子书阅读神器][15]

**安装**
```
sudo apt-add-repository ppa:bookworm-team/bookworm

sudo apt-get update

sudo apt-get install bookworm
```

### 6. Easy Ebook Viewer ###

（注：已停更）

[Easy Ebook Viewer][16]是另一个极好的能够读取ePub文件的GTK Python app。像是基本章节导航，从最后的阅读位置继续阅读，从其他电子书文件格式导入，章节跳转以及更多功能，Easy Ebook Viewer是一个极简的ePub阅读器。


![Easy-Ebook-Viewer][17]

该app仍处于初始阶段，并且只支持ePub文件。


**安装**

你可以通过从github下载源代码并将其与依赖项一起编译来安装Easy Ebook Viewer。或者，下面的终端命令将执行完全相同的操作。
```   
sudo apt install git gir1.2-webkit-3.0 libwebkitgtk-3.0-0 gir1.2-gtk-3.0 python3-gi

git clone https://github.com/michaldaniel/Ebook-Viewer.git
cd Ebook-Viewer/
sudo make install
```

在成功完成上述步骤后，您可以从Dash启动它。

### 7. Buka ###

Buka是一个拥有简洁的用户界面的电子书管理器。它目前支持PDF格式，旨在帮助用户更多地关注内容。有着pdf阅读器所有基本功能的Buka，可以让你通过方向键导航，有缩放选项，你可以并排查看两个页面。


你可以创建PDF文件的单独列表，并在它们之间随意切换。Buka还提供了一个内置的翻译工具，但是你需要连网使用该功能。

![Buka][18]


**安装**

你可以从[官方下载页面][19]下载AppImage。如果你不知道这一点，请阅读[如何在Linux中使用AppImage][20]。或者，你可以从命令行安装它:
```
sudo snap install buka
```

### 后记 ###

就我个人而言，我觉得Calibre最适合我的需要。而且，对我来说，Bookworm看上去很有前途，我现在也经常地使用它。然而，选择一个电子书应用完全取决于你的喜好。

你使用哪一个电子书app?请在下面的评论中告诉我们。

****

via: https://itsfoss.com/best-ebook-readers-linux/

作者：[Ambarish Kumar][a]

译者：[bayar199468](https://github.com/bayar199468)

校对：校对者ID

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]:https://itsfoss.com/author/ambarish/
[1]:https://camo.githubusercontent.com/20a2ac507156a67f87f1f91eca485584b9fcb18d/68747470733a2f2f346264733668657267632d666c79776865656c2e6e6574646e612d73736c2e636f6d2f77702d636f6e74656e742f75706c6f6164732f323031372f31302f626573742d65626f6f6b2d726561646572732d6c696e75782d383030783435302e706e67
[2]:https://itsfoss.com/non-ubuntu-beginner-linux/
[3]:https://www.calibre-ebook.com/
[4]:https://itsfoss.com/create-ebook-calibre-linux/
[5]:https://camo.githubusercontent.com/a77e39b5f8baa4db97d2f1510376ba4f79904b7b/68747470733a2f2f346264733668657267632d666c79776865656c2e6e6574646e612d73736c2e636f6d2f77702d636f6e74656e742f75706c6f6164732f323031372f30392f43616c696272652d383030783630332e6a706567
[6]:https://camo.githubusercontent.com/4fc7037ba516290f3d5bb2ba6d50285288c0a038/68747470733a2f2f346264733668657267632d666c79776865656c2e6e6574646e612d73736c2e636f6d2f77702d636f6e74656e742f75706c6f6164732f323031372f31302f66627265616465722d383030783632342e6a706567
[7]:https://fbreader.org/content/fbreader-beta-linux-desktop
[8]:https://fbreader.org/content/fbreader-beta-linux-desktop
[9]:https://okular.kde.org/
[10]:https://camo.githubusercontent.com/0c8d80059e3ace432da56f2c67fc3b29b5c68250/68747470733a2f2f346264733668657267632d666c79776865656c2e6e6574646e612d73736c2e636f6d2f77702d636f6e74656e742f75706c6f6164732f323031372f30392f4f6b756c61722d383030783433352e6a7067
[11]:https://en.wikipedia.org/wiki/XULRunner
[12]:https://camo.githubusercontent.com/130219e45bd103746aced4b0a86ba84b7bcc17fb/68747470733a2f2f346264733668657267632d666c79776865656c2e6e6574646e612d73736c2e636f6d2f77702d636f6e74656e742f75706c6f6164732f323031372f30392f6c756369646f722d322e706e67
[13]:http://lucidor.org/lucidor/download.php
[14]:https://camo.githubusercontent.com/17e37350d26add133b063b1a887c173c7bdb2750/68747470733a2f2f346264733668657267632d666c79776865656c2e6e6574646e612d73736c2e636f6d2f77702d636f6e74656e742f75706c6f6164732f323031372f30382f626f6f6b776f726d2d65626f6f6b2d7265616465722d6c696e75782d383030783435302e6a706567
[15]:https://itsfoss.com/bookworm-ebook-reader-linux/
[16]:https://github.com/michaldaniel/Ebook-Viewer
[17]:https://camo.githubusercontent.com/4bf7889bf3c496e6868c7d4f2f4738e4cb2b7ea4/68747470733a2f2f346264733668657267632d666c79776865656c2e6e6574646e612d73736c2e636f6d2f77702d636f6e74656e742f75706c6f6164732f323031372f30392f456173792d45626f6f6b2d5669657765722e6a7067
[18]:https://camo.githubusercontent.com/00b382d99eaadd350347a6d2a084f3c8065fd2f3/68747470733a2f2f346264733668657267632d666c79776865656c2e6e6574646e612d73736c2e636f6d2f77702d636f6e74656e742f75706c6f6164732f323031372f30392f42756b61322d383030783535352e706e67
[19]:https://github.com/oguzhaninan/Buka/releases
[20]:https://itsfoss.com/use-appimage-linux/
