"请领取你的魔法游戏胶囊, 也许你做梦都没想到, 切换3A游戏竟然比切歌还方便." --大陌   

作者:大陌DM   Q:269653764 
# HsFreezer(Hidden in the snow)
最新版本:1.11

    v1.00 
    雪藏Freezer v1.0  GUI版本上线.
    v1.01 
    修复一些窗体内覆盖干扰, ,优化部分win掌机体验,优化线程挂起顺序,针对不同引擎的调用链,合理调节各个内覆盖线程句柄的上下文保存和恢复顺序,极大提升稳定性,
    v1.02 
    增加雪藏栏, 更方便的管理资源 
    v1.03 
    优化检测进程性能算法, 使雪藏本体后台消耗近乎为0.
    v1.04 
    增加寒霜引擎, RE引擎内覆盖窗体检测排除,实现更完美的收纳隐藏效果. 
    v1.05 
    加入单锁模式, 更适合极限切换, win键(或者alt+tab,ctrl+esc等)即可匿藏无踪, 老板键都直呼内行.
    v1.06 
    1.优化适配了DX12的界面检测, 不再被底层内覆盖影响.  (感谢:博van 提供线索)  
    2.修复:某些DX12内覆盖窗体问题.
    
    v1.07 
    1.全局模式中加入搜索匹配功能,快速揪出"调皮的进程". 
    2.优化UI, 加量加大, plus版. 方便掌机用户点选.
    3.加入sklearn快速诊断日志,跟我联系,可快速找到问题并解决解决.
    4.加入"生成快捷方式功能", 可发送至桌面.(默认图标不好看,可自行修改:右键>属性.) 

    v1.08
    1.加入双击冻结/解冻功能.
    2.优化界面反馈,加入图标等.
    3.进行各种窗体内覆盖地毯式适配, 极大提升游戏兼容性和稳定性.(感谢awsLL,用上百个T的游戏库NAS配合测试,全面通过.)
    
    v1.09 
    1.加入一些不必要冻结进程名单进行忽略,误操作后,如雪藏判定此项为非必要操作项(如服务,附属子进程等), 直接删除其列表项,不响应,提升容错率.
    2.防止游戏被系统级压缩机制压爆,冻结后提升内存优先级,提升稳定性.(平时雪藏后再睡眠或者休眠,效果更佳,相当于一个安全缓冲)

    v1.10
    加入 快捷键功能.  "默认呼出主界面快捷键":ctrl+alt+X    以及"默认单锁模式下解冻"快捷键: ctrl+alt+E (均可修改)  掌机用户可映射至某个自定义键上. 键盘鼠党就随意啦.

    v1.11 
    1.加入更强窗体内覆盖检测, 从线程层面顺序挂起,保证稳定性.(之前一天收到三五个游戏反馈,现在已经3天没收到反馈了,说明稳定性达到了一个全新高度,众人拾柴火焰高)

    v1.12
    1.移除解锁快捷键:原因,有些游戏ctrl,alt,shift等键为某功能键,唤醒同时会把多余键位信息带到游戏中,
    导致某些误发操作.(比如急冻前是潜行状态, 然后用快捷键来解冻, 快捷键按压信息传入游戏中来飞个扑暴露了.......)
    所以解锁操作还是用点击解锁等方式进行比较稳妥,保证不把多余键位操作带到游戏中,之前属实没料到这种特殊情景...
    2.增加睡眠和休眠稳定性.
    3.增加使用呼出主界面快捷键后是否在光标位置呼出雪藏选项, 方便呼出后快速点击急冻/解冻.(快捷键平替方案)

    v1.13
    1.解决RTSS, 游戏加加等游戏内覆盖影响, 进行精细线程剥离处理.(感谢:浅墨染血  提供线索)
    (如有其他此类内覆盖软件造成雪藏异常,请及时反馈)
    2.加入开机自启功能.
    3.加入日志功能.

 *加入sklearn高级加密算法,动态打包技术,按每个不同的机器环境,动态打包,因为py的静态打包机制,经常会出现放到另一个机子上无法运行的状况,所以首次部署都会从本机环境进行打包生成, 
 顺便调用sklearn的模板算法,从内存层面自动匹配各种不同的游戏引擎以及窗体特征(比特征码稳定,性能更好),做出最优的子窗体内覆盖判定,按最优的线程顺序逐步挂起,从底层提高稳定性.
    (本程序适侧重用于游戏,对其他进程无特别的适配,毕竟窗体匹配围绕着游戏引擎展开, 如需要的话,可自行对其他非游戏类进程进行测试.)

    即将加入...
    敬请期待.....欢迎反馈..
    
    特色功能:
    1.自动检测高耗能软件置顶列出.(精简sklearn算法,让本体消耗更小)
    2.对多款不同引擎做出来的窗体进行针对性适配,适配99%以上父子窗体关系内覆盖检测, 一键收纳隐藏.(1%待你反馈,我将一一适配)
    3.加入省心省力, 数十项自动化优化, 堪比最强游戏资源管理器.(后台有朋友说: 这不就是资源JS器么? emmmm...
    不嫌手累的可以用默认资源JS器,还不会隐藏,且管理不便, 这就好像系统自带输入法就能打字,你为何要用第三方输入法?  一个道理,同源, 但有不同体验.五个字:术业有专攻.).
    
使用说明（Q&A）:

急冻:点击冻结后,被选定的程序则会进入绝对停止状态.(不消耗CPU and GPU资源)

    高耗能的游戏(进程)都能被"雪藏Freezer"检测到,
    在活跃列表中选择目标游戏进行冻结

解冻:则为冻结的游戏(进程)继续正常运行.

    冻结状态的进程也能被"雪藏Freezer"检测到.
    咱冻结列表中选择目标游戏进行解冻

    
 全局模式:可以快速找到本机所有运行的进程
 
    如果需要"急冻"/"解冻"的游戏不在列表中的时,请打开"全局模式",即,加以搜索,轻松揪出这个小调皮.
    这个模式非常好用,本人大多数情况用的是喜欢模式,相对稳定.
    
 单锁模式:对某个已经冻结的游戏(进程)进行附加监控(平时强烈推荐使用此模式,当然,需要后台加载等场景不适用,适用于你后台需要绝对停止的场景)
    
    在游戏进行中,实现win键或tab+alt或者ctrl+esc切出桌面后,则该游戏(进程)自动冻结,极致省电,点击解冻即可恢复.
    此功能1.06版本体验会大幅度提升,1.10加入快捷键功能, 更是随心唤醒.

 注意:由于非商用软件,精力有限,很多头尾细节还没抓起来, 暂时仅专注攻克适配软件主体功能. 部分非主体功可能实现得粗糙点,希望谅解, 毕竟无人赞助.
 
     1.没做卸载程序,如更新新版本, 旧版本也许守护线程附加到游戏进程中造成文件占用等, 可能需要等待下次重启后才能删除.
     2.联网更新还未上线,(测试中,现方案打算用爬虫形式做个简单推送(以及打开edge跳转到最新版下载链接),如看到提示框即可到b站或这儿获取最新更新,
     当然, 如果没提示你也偶尔来看看哦,因为爬虫不一定稳定>_< , 毕竟有很多网络请求限制因素,所以各位大人偶尔想起我的话就劳烦到这来看看有没有更新版本. (买个服务器来维护貌似划不来.)
     3.如有bug,最好截图保存现场弹窗或者提示, 以便排查.
     4.有的朋友会奇怪为何安装包那么大, emmmm..py打包他就是那么大,没办法,为了快速搭建界面,开发效率大于一切.毕竟免费放送,就不讲究打磨这种细节了.
    
雪藏应用于掌机,笔记本,台式机等windows PC设备,有以下妙用场景:

    0.真·暂停功能,不再受限限制于游戏内的暂停机制,降维打击,无需休眠(睡眠)想停就停, 把资源腾出来办公或者干其他事.哪怕你说你不在于进程在后台抢资源,但那种交杂在一起的背景音乐(音效), 抢占资源带来的卡顿,等等,这些都是非常影响体验的,你说你看个网页聊个天 , CPU风扇和显卡在呼呼响,心里总不得劲吧?.
    1.将游戏在后台的运算"资源"占用降为0,变相"增加续航".(仅占用内存)
    2.节省不同游戏间的切换的"时间",变相"增加续航".
    3.节省游戏载入过程中的"时间",变相"增加续航".
    4.大内存用户的福音,内存终于有用武之地,既能多开后台暂存,又不用负担多开的运算资源,妥妥的优化资源调度..(和win掌机绝配,因为掌机的显存和内存是动态拓展的,128g的内存,你开10个3A不成问题,本人测试48g内存的掌机,开5个左右3a问题不大,小游戏更是开到手软,让我想起了小时候100合1的游戏卡带,至于独显嘛,这个有待测试,不过一般情况也是你算力用完了,显存没吃满.这就可以用上雪藏, 把显存都利用起来) 
    5.办公or娱乐状态随时切换,切3A大作比切歌还方便.
    6.其他妙用有待开发(不只是可以冻结游戏,一切进程都可以,但不能乱冻哦!)
    7.针对掌机优化, 休眠之前先把游戏冻起来, 使得稳定性更高.不会造成休眠崩溃.( 其实就是你没关游戏,马上休眠,导致休眠或者唤醒的那一瞬资源抢不过来导致crash, 雪藏Hsfreezer就能很好的解决这个问题)
    8.雪藏特有的资源"one by one" 理念, 让计算机资源专注用户当下操控的进程,不再让计算机资源像匹脱缰的野马(渣男?), 处处留情. 哪怕王思聪100w的电脑,4路8路的xxx旗舰卡, 其实也不能同时负荷多个后台进程全速运行的, 计算机资源就是一个愈强愈耗, 不借助工具的话完全无法控制.现在市面上普遍的机能现状是: 物理内存升级突飞猛进, 但算力资源挤牙膏,完全是木桶效应,内存很难匹配到足够的算力, 这个短板, 就由雪藏来补上. 资源one by one的情况, 大内存用户就能体验到"不同游戏中的平行世界来回穿梭"的快感.
    番外特殊功能: 辅助治疗电子ED.e.有木有朋友跟我一样,有时候想玩游戏,但想想启动流程太久了, 干脆就不玩了,  但是你把一个游戏常驻后台, 想玩的时候随时切上来,
    像switch,ds等游戏机,好处就在游戏可以长时间贮存后台,一拿起来就玩,免去了等待焦虑,其实PC的3A大作很多就缺这功能,当然,我玩过那么多游戏当中, 有极少数是有后台自动冻结功能的.
    台式机:虽然没有续航焦虑, 但也可节省时间,免除等待焦虑,一台中等配置的台式机跑3A,整机功耗也有个200w-300w左右,
    很多朋友离开座位,或者干其他事情,游戏不关,其实一年下来也造成不少电量消耗.我以前经常爱这么干,关掉嘛,又嫌重新启动麻烦,不关心理又膈应,特别是离开时长不长不短的情况,就很纠结, 但现在, 你可以通过"雪藏"来灵活对待各种碎片时间, 不用纠结关不关游戏,待机不待机,休眠不休眠这些问题了,一年下来,全国千千万万个网友因为这些"雪藏"住这些大大小小的碎片时间,星星之火可以燎原,假设雪藏能帮助每个玩家平均一年平均省下20度电, 达到一定量级,在宏观上也能为节能减排做出一定贡献.总体经济效益不错.(省下的时间就更不计其数)
    100个用户x20=2000度, 1000个用户x20=20000度   10000个用户x20=200000度  100000个用户x20=2000000度电


注意事项:

    1.内存百分百到达85%以上,就不建议再继续往"雪藏"里面冻结游戏(进程), 可把虚拟内存调高一些.
    且不要各种开启新进程,与已经处于"雪藏"状态的进程争抢内存资源,它此时很脆弱....(当然,你可以挑战性能极限)
    2.网游类冻结会造成离线,请勿在摆摊,自动打怪等需要挂机的场景使用.(像永劫无间,不想玩了可以冻住,想玩解冻重连即可,其他游戏待各位自行尝试.)
    3.冻结操作属于高权限操作, 需要进行各种线程的精细附加才能达到最理想的效果,非简单无脑粗暴的挂起(这样会各种bug), 所以也许某些软件会阻止相关操作,请关闭相关软件.(纯用来打游戏的掌机你装啥乱七八糟的管家?哈哈)
    4.如冻结\解冻的目标不在列表中,请点击"全局模式"进行搜索查找.
    5.我在新版本里会陆续加入忽略一些不必要冻结的进程名单,用户进行冻结操作后,如雪藏判定此项为非必要操作项(如服务,附属子进程等), 直接删除其列表项,不作响应,提升容错率.(玩游戏就玩游戏嘛,有些同学手贱好奇去冻个后台进程...导致系统(程序)崩溃还怪雪藏不稳定咧.)
    
总结: 以上,我反复提到 "碎片时间" ."资源调度"这些概念,你在没用雪藏之前, 可能没啥感觉, 一旦你长期用下来你才能体会到其中的精妙之处,使用电脑的过程中,玩游戏的流畅度是一方面体验, 其实还有一个很重要的方面就是各种进程切换等待的体验,我们日常就觉得换个好的固态硬盘,增加读写效率,能提升这方面体验, 但其实,这个已经到了瓶颈,若干年前从机械到固态的升级,确实感受速度提升很明显,再往后就很难有质的飞跃了,这是程序io机制导致的,并不是读写瓶颈 ,就好像你买一台世界顶级的电脑,你想从A游戏进入到B游戏,你的硬盘和内存哪怕读写速率再快,常规流程操作下来,也远远比雪藏中的两个游戏间切换要慢的,这个已经超越比拼硬件性能的范畴,纯属机制上的降维打击. 这个工具你利用得当的话,会让你日常使用的过程中,感受到一种奇妙的体验,这个体验不是单纯堆硬件性能能堆出来的,堆硬件相当于是在琢磨怎么提升第一第二宇宙速度, 但雪藏像虫洞,空间跳跃...完全不是一个层面的感受, 其实我做这东西的初衷本来是方便我自己玩的,其实我用了快10年有余,习惯成自然,都快以为这个是大家都在用的东西了, 后来才发现并不是, ,后面想着如果把这个理念推广出去,能让硬件(软件)厂商,直接在游戏和系统上重视这块,那该多好,我也希望PC端也有能媲美游戏机那样的机制,我的大我理想,就是以后雪藏成为一款"多余的软件", 到那时候,我也非常欣慰了,至少,咱把一个不被人注意的的理念,推广成了普遍的共识, 这就像星星之火一样,可以燎原, 那句话咋说来着, 这世界上, 本没有路人走多了,就成路了,这需要大家的共同努力,发光发热,推进一些不起眼但实则非常重要的细节进步.   其实看到一些能马上get到雪藏亮点的小伙伴,很是欣慰,(每当我看到群里说这个东西有啥用,我真是恨我表达能力有限,19分钟的2倍速视频都不能说清楚,哎哎,属实惭愧) . 大陌在此感谢能喜欢雪藏的各位. --咖喱阿多 玛玛哈哈.
