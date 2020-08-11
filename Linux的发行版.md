## Linux的发行版，不同发行版之间的联系和区别 

### 1.介绍

Linux 主要作为Linux发行版（通常被称为"distro"）的一部分而使用。这些发行版由个人，松散组织的团队，以及商业机构和志愿者组织编写。它们通常包括了其他的系统软件和应用软件，以及一个用来简化系统初始安装的安装工具，和让软件安装升级的集成管理器。大多数系统还包括了像提供GUI界面的XFree86之类的曾经运行于BSD的程序。一个典型的Linux发行版包括：Linux内核，一些GNU程序库和工具，命令行shell，图形界面的X Window系统和相应的桌面环境，如KDE或GNOME，并包含数千种从办公套件，编译器，文本编辑器到科学工具的应用软件。

### 2.简介

   发行版为许多不同的目的而制作, 包括对不同计算机结构的支持, 对一个具体区域或语言的本地化，实时应用，和嵌入式系统，甚至许多版本故意地只加入免费软件。已经有超过三百个发行版被积极的开发，最普遍被使用的发行版有大约十二个。

### 3来历

- Linux是一个诞生于网络、成长于网络且成熟于网络的奇特的操作系统。1991年，芬兰大学生Linus Torvalds萌发了开发一个自由的UNIX操作系统的想法，当年，Linux就诞生了，为了不让这个羽毛未丰的操作系统矢折，Linus将自已的作品Linux通过Internet发布。从此一大批知名的、不知名的电脑黑客、编程人员加入到开发过程中来，Linux逐渐成长起来。
- Linux一开始是要求所有的源码必须公开，并且任何人均不得从Linux交易中获利。然而这种纯粹的自由软件的理想对于Linux的普及和发展是不利的，于是Linux开始转向GPL，成为GNU阵营中的主要一员。
- Linux凭借优秀的设计，不凡的性能，加上IBM、INTEL、CA、CORE、ORACLE等国际知名企业的大力支持，市场份额逐步扩大，逐渐成为主流操作系统之一。

### 4发行版最流行的12个

#### Fedora Core

1. Fedora Core（自第七版直接更名为Fedora）是众多 Linux 发行版之一。它是一套从Red Hat Linux发展出来的免费Linux系统。Fedora Core 的前身就是Red Hat Linux。Fedora是一个开放的、创新的、前瞻性的操作系统和平台，基于Linux。它允许任何人自由地使用、修改和重发布，无论现在还是将来。它由一个强大的社群开发，这个社群的成员以自己的不懈努力，提供并维护自由、开放源码的软件和开放的标准。Fedora 项目由 Fedora 基金会管理和控制，得到了 Red Hat, Inc. 的支持。Fedora 是一个独立的操作系统，是Linux的一个发行版，可运行的体系结构包括 x86(即i386-i686), x86_64 和 PowerPC。

#### Linux版本Debian

1. Debian Project诞生于1993年8月13日，它的目标是提供一个稳定容错的Linux版本。支持Debian的不是某家公司，而是许多在其改进过程中投入了大量时间的开发人员，这种改进吸取了早期Linux的经验。
2. Debian以其稳定性著称，虽然它的早期版本Slink有一些问题，但是它的现有版本Potato已经相当稳定了。这个版本更多的使用了 pluggable authentication modules (PAM)，综合了一些更易于处理的需要认证的软件（如winbind for Samba）。
3. Debian的安装完全是基于文本的，对于其本身来说这不是一件坏事。但对于初级用户来说却并非这样。因为它仅仅使用fdisk 作为分区工具而没有自动分区功能，所以它的磁盘分区过程令人十分讨厌。磁盘设置完毕后，软件工具包的选择通过一个名为dselect的工具实现，但它不向用户提供安装基本工具组（如开发工具）的简易设置步骤。最后需要使用anXious工具配置X Windows，这个过程与其他版本的X Windows配置过程类似。完成这些配置后，Debian就可以使用了。
4. Debian主要通过基于Web的论坛和邮件列表来提供技术支持。作为服务器平台，Debian提供一个稳定的环境。为了保证它的稳定性，开发者不会在其中随意添加新技术，而是通过多次测试之后才选定合适的技术加入。当前最新正式版本是Debian 6，采用的内核是Linux 2.6.32。Debian 6 第一次包含了一个100%开源的Linux内核，这个内核中不再包含任何闭源的硬件驱动。所有的闭源软件都被隔离成单独的软件包，放到Debian软件源的 "non-free" 部分。由此，Debian用户便可以自由地选择是使用一个完全开源的系统还是添加一些闭源驱动.

#### Linux版本Mandrake

1. MandrakeSoft，Linux Mandrake的发行商，在1998年由一个推崇Linux的小组创立，它的目标是尽量让工作变得更简单。最终，Mandrake给人们提供了一个优秀的图形安装界面，它的最新版本还包含了许多Linux软件包。
2. 作为Red Hat Linux的一个分支，Mandrake将自己定位在桌面市场的最佳Linux版本上。但该公司还是支持服务器上的安装，而且成绩并不坏。Mandrake的安装非常简单明了，为初级用户设置了简单的安装选项。它完全使用[GUI](http://baike.baidu.com/view/25309.htm)界面，还为磁盘分区制作了一个适合各类用户的简单GUI界面。软件包的选择非常标准，另外还有对软件组和单个工具包的选项。安装完毕后，用户只需重启系统并登录进入即可。
3. Mandrake主要通过邮件列表和Mandrak 自己的Web论坛提供技术支持。Mandrak对桌面用户来说是一个非常不错的选择，它还可作为一款优秀的服务器系统，尤其适合Linux新手使用。它使用最新版本的内核，拥有许多用户需要在Linux服务器环境中使用的软件——数据库和Web服务.
4. Mandrak没有重大的软件缺陷，只是它更加关注桌面市场，较少关注服务器市场。

#### Linux版本Ubuntu

1. Ubuntu是一个以桌面应用为主的Linux操作系统，其名称来自非洲南部祖鲁语或豪萨语的“ubuntu”一词（译为吾帮托或乌班图），意思是“人性”、“我的存在是因为大家的存在”，是非洲传统的一种价值观，类似华人社会的“仁爱”思想。Ubuntu基于Debian发行版和unity桌面环境，与Debian的不同在于它每6个月会发布一个新版本。Ubuntu的目标在于为一般用户提供一个最新的、同时又相当稳定的主要由自由软件构建而成的操作系统。Ubuntu具有庞大的社区力量，用户可以方便地从社区获得帮助。随着云计算的流行，ubuntu推出了一个云计算环境搭建的解决方案，可以在其官方网站找到相关信息。于2012年4月26日发布最终版ubuntu 12.04，ubuntu 12.04是长期支持的版本。

#### Linux版本Red Hat Linux

1. 这可能是最著名的Linux版本了，Red Hat Linux已经创造了自己的品牌，越来越多的人听说过它。Red Hat在1994年创业，当时聘用了全世界500多名员工，他们都致力于开放的源代码体系。
2. Red Hat Linux是公共环境中表现上佳的服务器。它拥有自己的公司，能向用户提供一套完整的服务，这使得它特别适合在公共网络中使用。这个版本的Linux也使用最新的内核，还拥有大多数人都需要使用的主体软件包。
3. Red Hat Linux的安装过程也十分简单明了。它的图形安装过程提供简易设置服务器的全部信息。磁盘分区过程可以自动完成，还可以选择GUI工具完成，即使对于 Linux新手来说这些都非常简单。选择软件包的过程也与其他版本类似；用户可以选择软件包种类或特殊的软件包。系统运行起来后，用户可以从Web站点和 Red Hat那里得到充分的技术支持。我发现Red Hat是一个符合大众需求的最优版本。在服务器和桌面系统中它都工作得很好。
4. Red Hat的唯一缺陷是带有一些不标准的内核补丁，这使得它难于按用户的需求进行定制。 Red Hat通过论坛和邮件列表提供广泛的技术支持，它还有自己公司的电话技术支持，后者对要求更高技术支持水平的集团客户更有吸引力。

#### Linux版本SuSE

1. 总部设在德国的SuSE AG在商界已经奋斗了8年多，它一直致力于创建一个连接数据库的最佳Linux版本。为了实现这一目的，SuSE与Oracle 和IBM合作，以使他们的产品能稳定地工作。SuSE还开发了SuSE Linux eMail Server III，一个非常稳定的电子邮件群组应用。
2. 基于2.4.10内核的SuSE 7.3，在原有版本的基础上提高了易用性。安装过程通过GUI完成，磁盘分区过程也非常简单，但它没有为用户提供更多的控制和选择。
3. 在SuSE 操作系统下，可以非常方便地访问Windows磁盘，这使得两种平台之间的切换，以及使用双系统启动变得更容易。SuSE的硬件检测非常优秀，该版本在服务器和工作站上都用得很好。
4. SuSE拥有界面友好的安装过程，还有图形管理工具，可方便地访问Windows磁盘，对于终端用户和管理员来说使用它同样方便，这使它成为了一个强大的服务器平台。 SuSE也通过基于Web的论坛提供技术支持，另外我还发现它有电话技术支持。

#### Linux版本Linux Mint

1. Linux Mint是一份基于Ubuntu的发行版，其目标是提供一种更完整的即刻可用体验，这包括提供浏览器插件、多媒体编解码器、对DVD播放的支持、Java和其他组件。它与Ubuntu软件仓库兼容。Linux Mint 是一个为pc和X86电脑设计的操作系统。因此，一个可以跑得动Windows的电脑也可以使用Linux Mint来代替Windows，或者两个都跑。既有Windows又有Linux的系统就是传说中的“双系统”。同样，MAC，BSD或者其他的Linux版本也可以和Linux Mint 共存。一台装有多系统的电脑在开机的时候会出现一个供你选择操作系统的菜单。Linux Mint可以很好的在一个单系统的电脑上运行，但是它也可以自动检测其他操作系统并与其互动，例如，如果你安装Linux Mint在一个安装了Windows版本的（xp，vista或者其他版本），它会自动检测并建立双启动以供您在开机的时候选择启动哪个系统。并且你可以在Linux Mint下访问Windows分区。Linux是更安全，更稳定，更有效并且日益易于操作的甚至可以和Windows相媲美的系统，它越来越让人感到难以抉择了。

#### Linux版本Gentoo

1. Gentoo是Linux世界最年轻的发行版本，正因为年轻，所以能吸取在她之前的所有发行版本的优点。Gentoo最初由Daniel Robbins（FreeBSD的开发者之一）创建，首个稳定版本发布于2002年。由于开发者对FreeBSD的熟识，所以Gentoo拥有媲美FreeBSD的广受美誉的ports系统 ——Portage包管理系统。

#### Linux版本centos

1. CentOS（Community ENTerprise Operating System）是Linux发行版之一，它是来自于Red Hat Enterprise Linux依照开放源代码规定释出的源代码所编译而成。由于出自同样的源代码，因此有些要求高度稳定性的服务器以CentOS替代商业版的Red Hat Enterprise Linux使用。两者的不同，在于CentOS并不包含封闭源代码软件,CentOS 是一个基于Red Hat Linux 提供的可自由使用源代码的企业级Linux发行版本。每个版本的 CentOS都会获得十年的支持（通过安全更新方式）。新版本的 CentOS 大约每两年发行一次，而每个版本的 CentOS 会定期（大概每六个月）更新一次，以便支持新的硬件。这样，建立一个安全、低维护、稳定、高预测性、高重复性的 Linux 环境。CentOS是Community Enterprise Operating System的缩写。
2. CentOS 是RHEL（Red Hat Enterprise Linux）源代码再编译的产物，而且在RHEL的基础上修正了不少已知的 Bug ，相对于其他 Linux 发行版，其稳定性值得信赖。
3. RHEL 在发行的时候，有两种方式。一种是二进制的发行方式，另外一种是源代码的发行方式。

### 5.区别

- Redhat，应该称为Redhat系列，包括RHEL(Redhat Enterprise Linux，也就是所谓的Redhat Advance Server收费版本)、FedoraCore(由原来的Redhat桌面版本发展而来，免费版本)、CentOS(RHEL的社区克隆版本，免费)。Redhat应该说是在国内使用人群最多的Linux版本，甚至有人将Redhat等同于Linux，而有些老鸟更是只用这一个版本的Linux。所以这个版本的特点就是使用人群数量大，资料非常多，言下之意就是如果你有什么不明白的地方，很容易找到人来问，而且网上的一般Linux教程都是以Redhat为例来讲解的。Redhat系列的包管理方式采用的是基于RPM包的YUM包管理方式，包分发方式是编译好的二进制文件。稳定性方面RHEL和CentOS的稳定性非常好，适合于服务器使用，但是Fedora Core的稳定性较差，最好只用于桌面应用。
-   Debian，或者称Debian系列，包括Debian和Ubuntu等。Debian是社区类Linux的典范，是迄今为止最遵循GNU规范的Linux系统。Debian最早由Ian Murdock于1993年创建，分为三个版本分支（branch）： stable, testing和unstable。其中，unstable为最新的测试版本，其中包括最新的软件包，但是也有相对较多的bug，适合桌面用户。testing的版本都经过unstable中的测试，相对较为稳定，也支持了不少新技术（比如SMP等）。而stable一般只用于服务器，上面的软件包大部分都比较过时，但是稳定和安全性都非常的高。Debian最具特色的是apt-get /dpkg包管理方式，其实Redhat的YUM也是在模仿Debian的APT方式，但在二进制文件发行方式中，APT应该是最好的了。Debian的资料也很丰富，有很多支持的社区，有问题求教也有地方可去。
- Ubuntu严格来说不能算一个独立的发行版本，Ubuntu是基于Debian的unstable版本加强而来，可以这么说Ubuntu就是一个拥有Debian所有的优点，以及自己所加强的优点的近乎完美的Linux桌面系统。根据选择的桌面系统不同，有多个版本可供选择，比如基于unity的Ubuntu，基于Gnome的Ubuntu Gnome，基于KDE的Kubuntu，基于LXDE的Lubuntu以及基于Xfce的Xubuntu等。特点是界面非常友好，容易上手，对硬件的支持非常全面，是最适合做桌面系统的Linux发行版本。
- Gentoo，伟大的Gentoo是Linux世界最年轻的发行版本，正因为年轻，所以能吸取在她之前的所有发行版本的优点，这也是Gentoo被称为最完美的Linux发行版本的原因之一。
-  FreeBSD，需要强调的是：FreeBSD并不是一个Linux系统！但FreeBSD与Linux的用户群有相当一部分是重合的，二者支持的硬件环境也比较一致，所采用的软件也比较类似，所以可以将FreeBSD视为一个Linux版本来比较。FreeBSD拥有两个分支：stable和current。顾名思义，stable是稳定版，而current则是添加了新技术的测试版。FreeBSD采用Ports包管理系统，与Gentoo类似，基于源代码分发，必须在本地机器编后后才能运行，但是Ports系统没有Portage系统使用简便，使用起来稍微复杂一些。FreeBSD的最大特点就是稳定和高效，是作为服务器操作系统的最佳选择，但对硬件的支持没有Linux完备，所以并不适合作为桌面系统。

### 6.版本之间的联系

####  基于Debian

- 1，Adamantix：基于Debian，特别关注安全。
- 2，Amber Linux：基于Debian，针对拉脱维亚用户作了一些定制。
- 3，ASLinux Desktop：西班牙语，基于Debian与KDE，针对各种桌面用途，包括家用、办公、教育、游戏、科学、软件开发，最大的卖点在于其丰富的可用性。
- 4，B2D Linux：基于Debian，希望可以由“做中学”来产生一个小而美的中文Linux包的计划。
- 5，Debian GNU/Linux：由大批社区志愿者收集的包。Debian拥有庞大的软件包可供选择（25000个以上），支持大量的硬件平台(12个计算机系统结构)。以前该包因为安装困难受到责难，但最新的版本具备了简单易用的文本式安装环境。非自由软件不会包含在Debian的主要软件包中。
- 6，Guadalinex：由西班牙的安达卢西亚地方政府推动，基于Debian，针对西班牙语的家庭用户以及学校。
- 7，Knoppix：第一张Debian的自启动运行光盘。包含的软件非常多，启动时会自动进行硬件监测。从4.0起，用DVD作光盘。

#### 基于Knoppix

-  Gnoppix：Knoppix的GNOME版，该包发行周期较长，未来会跟Ubuntu进行集成。
- Kanotix：自启动运行光盘，基于Knoppix，也可以安装到硬盘上。有很好的硬件支持，桌面与笔记本电脑的集成也很出色。Kurumin：针对巴西用户的Knoppix。
- 8，LinEx：由西班牙的埃斯特雷马杜拉地方政府推动的包。
- 9，Loco Linux：基于Debian的阿根廷Linux。
- 10，MEPIS: 基于Debian的桌面和服务器。
- 11，Rays Linux（华镭）：基于Debian，针对亚洲市场，由新华科技（南京）系统软件有限公司开发。
- 12，Skolelinux：在挪威发起，旨在打造适合于学校的轻便包。
- 13，Symphony OS：基于Debian，与众不同地采用Mezzo桌面。
- 14，Ubuntu：对初学者而言最易用的Linux包。由Canonical有限公司赞助，基于Debian，使用自己的软件包库，与Debian的有所不同，旨在开发出更加友好的桌面，已经取得了良好的声誉。
- 15，Wdlinux是基于CentOS精简的定制版本,是针对web服务器的应用而精简的.同时安装做了些自动化安装的处理,达到更易于安装和使用.

#### 基于Ubuntu

- Ubuntu Kylin：中国定制本地化的ubuntu发行版
- LinuxMint：基于Ubuntu的发行版，人气很高，是目前排行榜上第三名的发行版。
- Edubuntu：是Ubuntu的教育发行版。
- Hiweed：基于Ubuntu，使用Xfce桌面环境的轻量级中文发行版。0.x版基于Debian（现已改名Deepin）。
- Kubuntu：使用KDE桌面环境的Ubuntu包。
- Lubuntu：使用LXDE桌面环境的Ubuntu包。
- PUD GNU/Linux：基于Ubuntu的小型Linux，可安装于光盘或256 MB以上的USB 闪存盘
- Xubuntu：使用Xfce桌面环境的Ubuntu包。

#### Linux版本基于RPM

- 1，aLinux：原名Peanut Linux，针对家庭用户。
- 2，ALT Linux：东欧版本。
- 3，Ark Linux：强调易学易用。
- 4，ASPLinux：提供俄语等东欧语言的支持。
- 5，Asianux Server：由中国红旗、日本Miracle、韩国Hannsoft三家联合开发，主要市场针对亚洲地区，对中,文、日文、韩文的支持比较好。
- 6，Blag Linux：体积小，但功能较多。
- 7，Caixa Mágica：葡萄牙语的Linux。
- 8，cAos Linux：由社区创建的包，功能通用、培植简单。
- 9，CentOS：由社区支持的包，旨在100%地与Red Hat Linux企业版兼容，但不包含Red Hat 的商业软件。
- 10，Cobind：桌面。
- 11，Conectiva：一个巴西包，曾经是United Linux的创建成员，现在该公司已经并入到Mandriva Linux。
- 12，EduLinux：用于教育的包。
- 13，Fedora：可用作工作站、桌面以及服务器，由[红帽](http://baike.baidu.com/view/414282.htm)公司及其社区开发。
- 14，Linux Mobile System：基于Fedora Core的包，设计成从USB存储设备启动，比如U盘。
- 15，Linpus Linux：来自台湾厂商发行的Linux版本。是一套通过LSB 3.1认证、GB18030-2000编码检验测试及支持CNS11643中文标准交换码全字库的Linux桌面型系统。在中文支持能力上较为完善。
- 16，Magic Linux：一个易用的中文包。
- 17，Mandriva Linux：最初是红帽的一个变种，针对奔腾级CPU作了优化，后来在保持兼容性的同时，派生成为更友好的包。Mandriva中所有的软件仍然免费，还有活跃的社区支持，另外通过注册以及销售盒装产品，Mandriva还提供企业级的支持与服务，还有针对付费用户的俱乐部。
- 18，Novell Linux Desktop：由于Novell收购了SUSE，他们的Linux产品对原来的包有所继承。
- 19，PCLinuxOS：一个易用的自启动运行光盘，以良好的观感著称；硬盘安装也同样轻而易举。最初基于Mandrake 9.2，而后PCLinuxOS针对桌面用户，开始自己的开发道路。在保留基于RPM包的同时，PCLinuxOS别出心裁地使用自己的APT包管理工具（受Debian影响），但图形前端仍然用的是Synaptic。
- 20，PCQLinux2004：由印度的PCQuest杂志生产，基于Fedora Core。
- 21，PLD Linux：来自波兰的包，针对较高级别的用户，比Slackware、Gentoo更加易用。

- 22，QiLinux：意大利生产，包括桌面版、光盘自启动版，还有服务器版、高级服务器版。
- 23，红旗Linux：由北京中科红旗软件技术有限公司开发，主要针对中国市场。
- 24，Red Hat Enterprise Linux：红帽Linux家族中唯一的商业分支。
- 25，Scientific Linux：由红帽Linux企业版，将遵循GPL的软件重新编译而成。
- 26，SUSE/openSUSE：来自德国，是欧洲最流行的包之一。跟红帽一样，也包括大量的软件，需要7张以上的CD，现在则用双DVD。这个包有独特的配置工具YaST。也是United Linux的创立者之一，已经被Novell公司收购。openSUSE是一个新的版本，基于社区，完全开源。
- 27，Tinfoil Hat Linux：对安全格外关注的包。
- 28，Trustix：专注于安全与稳定性的包。
- 29，Turbo Linux：在亚洲较流行的一个包，基于Red Hat，是United Linux的成员。
- 30，Vine Linux：基于Red Hat的一个日本包。
- 31，White Box Enterprise Linux：意在兼容Red Hat企业版第三版。
- 32，Yellow Dog：基于Red Hat，针对PowerPC平台。
- 33，YOPER："Your Operating System"（你的操作系统），来自新西兰的桌面包。Slackware

#### Linux版本其它打包方式的包

- 1，ArchLinux：基于KISS原则，针对i686的CPU做了优化，以.tar.xz格式打包并由包管理器进行跟踪维护，特别适合动手能力强的linux用户。
- 2，Foresight Linux：采用Conary包管理系统，引入了GNOME中的许多最新技术，比如beagle、f-spot、howl以及最新的hal等，这个包在保持易用的同时，更注重革新。
- 3，Gentoo：这个包采用自己独特的Portage包管理系统，吸引了许多狂热爱好者以及专业人士，强调自己编译源码，而不是直接用二进制包，这样程序运行速度更快。
- 4，GoboLinux：构建了新的文件系统，比如GCC放在/Programs/GCC/这样的目录，为了让系统能找到这些文件，在/System/Links/Executables这样的目录下归组，这样就包含了/Programs目录下所有可执行文件的符号链接。
- 5，Heretix：以前叫做RubyX，包的管理，包括包管理，都是通过由Ruby写的脚本来完成，所有的包都安装在/pkg目录下。
- 6，ImpiLinux，来自南非的包，主要针对非洲用户。
- 7，Jedi GNU/Linux：使用force-get包管理器，允许源码、二进制软件包共存。
- 8，Linux From Scratch：这是一份文档，介绍如何自己动手，如何白手起家编译打造自己独一无二的Linux系统。
- 9，Lunar Linux，基于源码，由Sorcerer GNU/Linux所派生。
- 10，MkLinux："Microkernel Linux"的缩写，旨在将Linux移植到跑Mach微核的PowerPC机器上。
- 11，Onebase Linux：采用OLM包管理器，对二进制、源码进行管理。
- 12，[Sabayon Linux](http://baike.baidu.com/view/1525544.htm)：基于Gentoo，来自意大利。
- 13，Sorcerer GNULinux：基于源码。
- 14，Source Mage GNU/Linux：也是基于源码，由Sorcerer GNU/Linux所派生。

- 15，Ututo：基于Gentoo，来自阿根廷。

- 16，Open Client：基于Red Hat Enterprise Linux，来自IBM，提供有Fedora、Ubuntu、SLED的Layer。给老机器订制的小型包

 