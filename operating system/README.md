计算机操作系统发展历史简述

1947，发明了晶体管，使得计算机不再是机械设备，而是电子设备，为操作系统奠定了基础。

1960，很多计算机制造商做出了各自的可以进行批处理操作的系统，但是只能限定于限定的硬件环境。

1964，IBM推出了IBM System/360系统，能够在一系列的硬件环境中运行。

1965，AT&T贝尔实验室、麻省理工和其他一些团队打算搞一个多用户多任务的复杂操作系统，取名为Multics（Multiplexed Information and Computing System），但是1969年，该项目发展过于缓慢，导致破产。

1969，参与项目的Ken Thompson（汤姆森）和Dennis Ritchie（瑞奇）因为项目的破产回到贝尔实验室，利用PDP-7机器写了一个简易的系统（1970年完成），但是因为调侃这个系统无法和Multics媲美（其实是调侃Multics），就取名为Unics（Uniplexed Information and Computing System）,汤姆森把名字稍微改了一下变成了Unix，所以1970便是Unix的元年。
其他：早期的Unix是完全使用汇编写的，在开发Unix时候汤姆森在BCPL（由CPL（Combined Programming Language）改进而来，两者都由剑桥大学发明）基础上发明了B语言，然后对Unix使用B语言进行了部分改进，1973年，瑞奇与汤姆森一起改进了B语言从而发明了C语言，1974年，Unix用C语言完全重写并且向外界发布。

1974，贝尔实验室把Unix的源代码拷贝给了各个实验室、学校、公司，其中加州大学伯里克分校对Unix源代码进行了深度研究不断改进Unix，极大地推进了Unix的发展，其中著名的TCP/IP协议就是他们在Unix实现的，然后他们把他们搞的这一套Unix称作BSD（Berkeley Software Distribution）。

1980，西雅图一名程序员研发出86-DOS系统，被微软比尔盖茨买下版权。

1981，MS-DOS上市，与IBM合作，在IBM机器上捆绑销售MS-DOS。

1983，AT&T被反垄断法拆成了几个子公司，这时，AT&T看到Unix分光无限好决定对其进行商业用途，不再对外开放源代码，然而伯里克分校的BSD团队并不需要钱，所以他们把受Unix商业版影响的代码部分全部自己改写。最后BSD项目团队最后研究出了完全自己的Unix，因为版权问题只能叫做类Unix系统（Unix-like）（例如Free-BSD, MAC OS前身等等）。

1983，Richard Stallman发起革奴计划（GNU，GNU is Not Unix，意指是一个免费的，开源的，自由的，和Unix一样强大的，但不是Unix的系统），目标是创建一个完全自由开放的操作系统。

1984，苹果公司发布基于BSD项目的操作系统System 1.0（MAC OS 8之前都是以System x.x命名的），并搭载在麦金塔电脑上，含有桌面、窗口?、图标、光标、菜单和卷动栏等项目。
其他：这是第一款真正的图形界面桌面系统，微软的Windows当时还只是嵌入在MSDOS下的一个程序而已。

1990，此时，GNU计划已经完成了Unix中大部分工具的编写工作，就是GNU操作系统内核（当时称为HURD）迟迟没能完成。

1991，System 7发布，这时的MAC OS已经具备了256色的简易图形界面，当时的微软还停留在DOS时代。

1991，芬兰赫尔辛基大学的Linus Torvalds学生，在校期间自己搞了一个操作系统玩玩，当时在自己的系统中使用了GNU的GCC, Bash等软件，受到GNU计划的影响，他把自己的系统内核源代码发布到了网上，内核取名Linux（Linus's Unix）。

1992，当时不太成熟的Linux内核和GNU工具结合产生了一个完整的自由的操作系统，称为GNU/Linux。
其他：在GNU/Linux诞生的年代，已经有很多优秀的开源项目，他们和GNU计划无关，都是个人或是组织开发，例如Vim, Apache, Perl, Python等等。也正是GNU/Linux的开源影响，世界掀起了一股开源热，兴起了开源文化的运动，大量开源项目出现，例如PHP, MYSQL, Ruby, NodeJS, KDE等等。
其他：GNU/Linux现在都被简称为Linux，其实是不规范的，也是对GNU不尊敬的表现。

1993，MS-DOS 6.X ~ MS-DOS 7.X（1996年），其中添加了一款名叫Windows的GUI程序。（Windows 1.x/2.x/3.x一直到Windows 9X/ME都是MS-DOS下的一个GUI（图形用户界面）程序！）

1993，微软发布Windows10 NT 3.1系统，这时Windows NT的第一代产品，包括Workstation和Server两个版本。

1994，当时1991年Linux发布到网上，世界各地广大程序员对其产生兴趣，对其研究改进，94年3月Linux 1.0发布，Linux成为了一个基本可用的系统内核，从此Linux开始了迅猛的发展。（至于为什么Linux图标是个企鹅，因为Linus小时候被企鹅攻击过，其实也没什么逻辑关系，就像你问鲁迅窗帘为什么是蓝色的，他会回答你就是我当时随便选了一个颜色而已）
其他：当时的BSD衍生的系统还在和AT&T的Unix系统打官司，也促使了Linux的发展，并且Linus本人承认当时他不知道还有FreeBSD这样的系统存在，如果知道的话，可能就不会有Linux了。

1995，GNU/Linux系统越做越成熟，各个发行版推进了GNU/Linux在全世界的推广。

1996，KDE团队创建了K桌面环境项目（K Desktop Environment），为GNU/Linux系统设计图形化桌面环境，桌面要有浏览器，所以他们就分了一个组来设计浏览器内核，这便是大名鼎鼎的KHTML和KJavaScript，便有了之后的Webkit和Blink。

1996，微软发布Windows NT 4.0操作系统，是NT系列的一个里程碑，为接下来2000年之后Windows迅猛发展打下了基础。

1997，MAC OS 8问世，这时历史上第一款32位色彩，用户界面相当友好的桌面系统，甚至被称为艺术作品，以至于在Windows 2000之后的系统中模拟出惟妙惟肖的Mac OS X操作环境为荣。

1997，GNU发起GNOME(The GNU Network Object Model Environment)计划，意指为UNIX-like系统提供统一的桌面环境，1999年第一个版本发布。

2000，MS-DOS 8.0发布，这时最后一个MSDOS版本，因为微软看到了Windows的曙光，于是放弃了DOS，发布Windows NT操作系统。
其他：Windows NT在2000之前并不流行，直到Windows2000（NT5.0），XP（NT5.1），Vista（NT6.0），Win7（NT6.1）的诞生，Windows才真正的开始迎来自己的巅峰。另外：Windows 10预览版内核NT6.4，正式版内核NT10.0。

2002，南非商人Mark shuttleworth推出了Ubuntu发行版。
