"请领取你的魔法游戏胶囊, 也许你做梦都没想到, 切换3A游戏竟然比切歌还方便." --大陌DM

这是一款让你可以随心冻结游戏的软件(游戏暂停软件),想玩就玩,想停就停.

雪藏会让你深刻感受到--内存,原来是这么用的.

作者:大陌DM   Q:269653764 
# HsFreezer(Hidden in the snow)

高速下载地址: https://www.123pan.com/s/o8hUjv-2dllA.html

最新版本:---1.25---更新日期2024 / 5 / 5 (最近一个月更新非常快,请关注获取最新特性)---

视频演示1: https://www.bilibili.com/video/BV1zm421L76B (本视频演示使用版本 V1.05)

视频演示2: https://www.bilibili.com/video/BV1xp421S7PX?t=332.0 (感谢up主:博van小哥哥的推荐)(本视频演示使用版本 V1.14)

视频演示3: https://www.bilibili.com/video/BV19H4y137hx/ (感谢up主:甜蜜的泡芙 制作) (本视频演示使用版本 V1.211)

更多待您创作! 我会把关于雪藏的投稿创作都做展示,欢迎大家用雪藏来创作.


特别注意:

1.使用各种查看帧数功耗OSD软件( 游戏加加,RTSS 等)的用户,请更新至1.13以上版本! 
此类软件属于强制内覆盖绘制软件,已经适配.

2.卡普空部分游戏:如生化危机等,尽量画面设置中尽量使用DX11,因为AMD驱动与DX12有某些冲突
(当然,这个驱动版本是玄学,也不一定需要这样做,可自行测试,现阶段,DX11更为稳定).

3.鄙人狠下心下载了80+个g的原神,  已经于V1.18版本解决原神窗体条纹问题 .
(原神党久等了, 原神随意冻结,冻结时长太长解冻仅会重连而已,非常快速的还原. 实测联网类游戏可用)

4.多设备玩steam游戏,由于云存档机制问题, 要注意有没有自动云存档，雪藏中的游戏,没退出前steam可能会没有把游戏存档即时更新, 换设备后, 会造成存档回溯. (感谢:古赫分享)
(单设备就尽情的造,设备太多也是一种烦恼哈哈)

5.某些网游的反调试机制, 会使雪藏无法生效, 属正常现象.(极少数,目前已知有:崩坏3)



更新日志:

    v0.01
    弹窗模式初代雪藏于2017年建立 (当时80行代码,自用,迭代至今, 现GUI界面+逻辑处理代码总量13700+行,持续增加中..窗体线程操作是大头...如果纯挂起那不如用ZY监视器,要的就是在体验中追求极致,不然何必打磨?)

    v1.00 
    雪藏Freezer v1.0  GUI版本上线.
    v1.01 
    修复一些窗体内覆盖干扰, ,优化部分win掌机体验,优化线程挂起顺序,针对不同引擎
    的调用链,合理调节各个内覆盖线程句柄的上下文保存和恢复顺序,极大提升稳定性,
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
    1.加入一些不必要冻结进程名单进行忽略,误操作后,如雪藏判定此项为非必要操作项
    (如服务,附属子进程等), 直接删除其列表项,不响应,提升容错率.
    2.防止游戏被系统级压缩机制压爆,冻结后提升内存优先级,提升稳定性.
    (平时雪藏后再睡眠或者休眠,效果更佳,相当于一个安全缓冲)

    v1.10
    加入 快捷键功能.  "默认呼出主界面快捷键":ctrl+alt+X    
    以及"默认单锁模式下解冻"快捷键: ctrl+alt+E (已删除此快捷键,原件可见v1.13)  
    掌机用户可映射至某个自定义键上. 键盘鼠党就随意啦.

    v1.11 
    1.加入更强窗体内覆盖检测, 从线程层面顺序挂起,保证稳定性.
    (之前一天收到三五个游戏反馈,现在已经3天没收到反馈了,说明稳定性达到了一个全新高度,众人拾柴火焰高)

    v1.12
    1.移除解锁快捷键:原因,有些游戏ctrl,alt,shift等键为某功能键,唤醒同时会把多余键位信息带到游戏中,
    导致某些误发操作.(比如急冻前是潜行状态, 然后用快捷键来解冻, 快捷键按压信息传入游戏中来飞个扑暴露了.......)
    所以解锁操作还是用点击解锁等方式进行比较稳妥,保证不把多余键位操作带到游戏中,之前属实没料到这种特殊情景...
    2.增加睡眠和休眠稳定性.
    3.增加使用呼出主界面快捷键后是否在光标位置呼出雪藏选项, 方便呼出后快速点击急冻/解冻.(急冻\解冻 快捷键平替方案)

    v1.13
    1.解决RTSS, 游戏加加等游戏窗体内覆盖软件影响, 进行精细线程剥离处理.(感谢:浅墨染血  提供线索)
    (如有其他此类内覆盖软件造成雪藏异常,请及时反馈)
    2.加入开机自启功能.

    v1.14
    1.呼出快捷键功能升级,:呼出/隐藏切换.
    2.开机自启后自动最小化(1.13版本开启自启的请右键点击自启按钮取消,再开启方可生效)
    3.删除v1.07的右键急冻/解冻功能, 改为把已冻结的程序因特殊情况出现在活跃程序列表时的纠错功能(如果该已被雪藏程序不在雪藏列表中也可用全局功能解冻)
    
    v1.15
    1.修复开机自启提示环境异常问题(感谢:熊伽喵的熊 提供线索)
    2.优化线程句柄控制,进一步增加窗体显隐稳定性.

    V1.16
    1.加入自动提示更新功能.
    2.列表无选中项时,自动选中第一项, 如需要 急冻\解冻 的目标在第一项,不用选中直接点击 急冻\解冻 即可.
    3.优化性能,衔接更为丝滑.

    V1.17
    1.经过优化后, 重新加入急冻/解冻快捷键 (快捷键操作时, 如当前没有选中对象, 雪藏自动选择第一项, 大概率能自动选中您目前在玩的游戏)
    2.进行更合理的线程顺序挂起调优, 使雪藏更好的应对各种情景. (某些盗版可能有反调试机制,中断后故意报出"致命错误"等弹窗,无视即可,别点确定就能继续玩,多见于某xxx520的游戏. 甚至还劝你重启电脑,离谱!  :(  ) 
    3.加入主动提升内存映射优先级的操作, 让雪藏的游戏进程更为稳定, 避免被系统级压缩操作影响.

    V1.18 
    1. 修复"原神"与若干与此原理相似窗体条纹问题.
    2. 修复活跃进程退出残留问题.
    3. 更可靠的窗体控制优化
    
    V1.19
    1.优化快捷键页面反馈
    2.优化识别效率.
    
    V1.20
    1.在主界面加入:实时模式/性能模式 切换开关 . 
    实时模式:自动扫描检测并列出高耗能进程, 在未找到目标进程时建议开启此模式
    性能模式: 固定当下列表, 不再进行扫描检测,  在找到目标进程后, 可开启性能模式达到极致性能,且更利于急冻/解冻快捷键的使用,这将会使急冻解冻反复触发这同一个程序上(当然, 实时模式也没啥消耗,但处女座嘛....)
    2.优化急冻/解冻性能, 消除迟滞感.
    3.优化列表刷新机制, 不再频闪.

    V1.21
    1.不再限制非游戏进程的急冻操作.(可对QQ,微信,东方财富,同花顺,各种常见办公软件等一系列软件进行急冻,真正往全局调度算力的实用性工具方向发展)
    2.对多窗体in单进程的场景进行深度优化适配,比如:QQ/微信,浏览器等同一个进程产生多个窗口的情况,全面覆盖.(同名多进程谨慎使用)
    3.修复部分游戏自适应窗体稳定性问题,体验更佳.
    
    V1.211
    修复单锁模式异常.
    
    V1.22
    1.修复一些导致解冻卡住的情景(多见于各种网游,与网游反调试机制冲突)
    2.UI优化
    3.优化物理内存与虚拟内存之间的压入与释放的机制.
    4.实时模式下,进程退出后, 进程名更快的在活跃程序列表消除.

    V1.23
    1.UI界面优化更新.
    2.加入:窗体空白处皆可拖拽,解决低分辨率用户UI超出屏幕无法拖回问题.
    3.修复开机自启偶尔出现环境加载错误.(感谢:疏星 提供线索)
    4.修复若干其他细节问题.
    
    V1.24
    1.加入白名单:选中活跃进程框里的进程后, 左键点击右边的小星星添加/删除白名单,右键点击小星星为查看白名单列表,
    白名单里的进程, 会优先置顶显示,且不再进行首次冻结提示弹窗,建议把常玩游戏无脑全加入白名单.
    2.修复开机自启后,任务栏图标消失问题.
    
    V1.25
    1.修复初始化问题.
    2.加入系统托盘小图标,开机自启则以小图标隐藏启动.(点打叉是压入系统托盘小图标哦)

    
 *加入sklearn高级加密算法,动态打包技术,按每个不同的机器环境,动态打包,因为py的静态打包机制,经常会出现放到另一个机子上无法运行的状况,所以首次部署都会从本机环境进行打包生成, 
 顺便调用sklearn的模板算法,从内存层面自动匹配各种不同的游戏引擎以及窗体特征(比特征码稳定,性能更好),做出最优的子窗体内覆盖判定,按最优的线程顺序逐步挂起,从底层提高稳定性.
    (本程序适侧重用于游戏,对其他进程无特别的适配,毕竟窗体匹配围绕着游戏引擎展开, 如需要的话,可自行对其他非游戏类进程进行测试.)

    即将加入...
    敬请期待.....欢迎反馈..
    
    特色功能:
    1.自动检测高耗能软件置顶列出.(精简sklearn算法,让本体消耗更小)
    2.对多款不同引擎做出来的窗体进行针对性适配,适配99%以上父子窗体关系内覆盖检测, 一键收纳隐藏.(1%待你反馈,我将一一适配)
    3.加入省心省力, 数十项自动化优化, 堪比最强游戏资源管理器.(后台有朋友说: 这不就是资源JS器么? emmmm...看似同源,但细节差远了,
    不嫌手累麻烦的可以用默认资源JS器,还不会隐藏,且管理不便, 这就好像系统自带输入法就能打字,自带记事本就能记录,自带播放器就能看片,你为何要用第三方输入法?用第三方编辑器?播放器?   一个道理,功能同源, 但有不同体验.五个字:术业有专攻.).
    这个见仁见智.

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


使用说明and疑难解答（Q&A）:


急冻:点击冻结后,被选定的程序则会进入绝对停止状态.(不消耗CPU and GPU资源)

    高能耗的游戏(进程)都能被"雪藏HsFreezer"检测到,
    在活跃列表中选择目标游戏进行冻结

解冻:冻结的游戏(进程)从冻结那一刻的状态继续正常运行.

    冻结状态的进程也能被"雪藏HsFreezer"检测到.
    咱冻结列表中选择目标游戏进行解冻

白名单:

    白名单进程优先置顶,且不再进行首次冻结确认提示,建议把常玩的游戏全加入白名单.
    
 全局模式:可以快速找到本机所有运行的进程(也可用作刷新功能)
 
    如果需要"急冻"/"解冻"的游戏不在列表中的时,请打开"全局模式",即,加以搜索,轻松揪出这个小调皮.
    这个模式非常好用,本人大多数情况用的是喜欢模式,相对稳定.
    
 单锁模式:对某个已经冻结的游戏(进程)进行附加监控(平时强烈推荐使用此模式,当然,需要后台加载等场景不适用,适用于你后台需要绝对停止的场景)
    
    在游戏进行中,实现win键或tab+alt或者ctrl+esc切出桌面后,则该游戏(进程)自动冻结,极致省电,点击解冻即可恢复.
    此功能1.06版本体验会大幅度提升,1.10加入快捷键功能, 更是随心唤醒.

 注意:由于非商用软件,精力有限,很多头尾细节还没抓起来, 暂时仅专注攻克适配软件主体功能. 部分非主体功可能实现得粗糙点,希望谅解, 毕竟无人赞助.
以下是一些问题的原因:
 
     1.没做卸载程序,如果更新新版本, 旧版本也许守护线程附加到游戏进程中造成文件占用等, 可能需要等待下次重启后才能删除.
     2.联网更新还未上线,(测试中,现方案打算用爬虫形式做个简单推送(以及打开edge跳转到最新版下载链接),如看到提示框即可到b站或这儿获取最新更新,
     当然, 如果没提示你也偶尔来这看看哦,因为爬虫不一定稳定>_< , 毕竟有很多网络请求限制因素,所以各位大人偶尔想起我的话就劳烦到这来看看有没有更新版本. (买个服务器来维护貌似划不来.)
     3.如有bug,最好截图或者录屏,保存现场弹窗或者提示, 以便排查.
     4.有的朋友会奇怪为何安装包偏大, emmmm..pyGUI打包他就是那么大, 没办法,为了快速搭建界面,开发效率大于一切.毕竟免费分享,就不讲究打磨这种细节了.(安装包包含动态打包环境,先尝试运行预设单文件,如无法运行则进行动态打包)
     
关于敏感操作(很玄学,有时候报有时候不报,但还是说明情况):

    两方面原因:1.高权限操作2.python的pyinstaller打包机制问题.
    高权限操作就不用说了,类似风灵月影修改器的情况,频繁跨不同游戏进程进行操作肯定会被视为敏感操作的,这操作一般是输入法和杀软才正常,咱这软件还没一个清晰的权限归类,所以被判定很正常,加上又没弄签名,没氪金是有点小问题.
    至于pyinstaller打包, 分享一位博主关于pyinstaller打包的测试,打包print一句hello,world的空程序都报毒:
    https://www.bilibili.com/video/BV1PR4y187oj/
    评论区里也说得很到位,就是这么回事, 现阶段你要么就关掉杀软要么就白名单要么就换火绒,这是最简单的解决方案.

     360, 还有微软那些什么基于声誉保护,实时保护等功能是很令人无语, 有一次下个软件死活打不开, 也没个是否同意运行选项, 强制性拦截.,把人整疯,后来在设置里钻来钻去才找到开关...前些天调试雪藏的时候, 不打包就没事,一打包就报毒..我原本以为是导入某些库导致报毒, 看了上面视频才发现和写的内容毫无关系, 仅仅用pyinstaller打包exe就能报毒, pyinstaller也算py用户最常用打包工具了(没有之一), 所以最好的方式就是关掉或者白名单.   不然真心无解.  我为啥换成火绒?..之前我用360,并不是用他的杀毒功能多好用, 用的是各种他附带的小工具,断网急救箱啊,清理垃圾磁盘啊等等(我这人比较懒,我知道有其他针对性的软件都能做到这些,但懒得找,直接在360工具包里用), 后来发现各种常用的软件被他强行关掉开机自启, 这就算了,像pixpin这种软件甚至被删掉各种dll组件...真的是添乱第一名,  火绒就很巴适了,至少不那么霸道.  话说回来,反正我常年一直都用pyinstaller打包, 自用没问题(可能我关闭微软自带那些东西很久了,如果没有某个机友的反馈我还真不知道是pyinstaller的问题.)如果不打包咋分享?哪怕以后我开源了,扔源代码给用户,没环境用户也没法直接跑啊,所以打包是绕不开的, 也懒得去研究这些东西了,这并不是我这普通用户层面能解决的问题,已经上升到pyinstaller编译器和杀软的层面,(就好像易语言,现在py都成易语言了么...感叹!),连打包一句hello world都报毒,那还能咋办?这让大陌心有余而力不足, 我估摸着微软是想卖各种签名,一个签名几千上万,咱一个小软件,本身就是自用的,做成软件分享给大家使用仁至义尽了吧? 属实更没必要去搞签名了,当然,有人赞助另外一回事,听讲也有其他好几种打包方式, 部署环境较为麻烦, 但我懒得一一去尝试了,pyinstaller我都嫌够麻烦了, 如果如果有更好(能解决报毒问题)的py打包方式可以推荐,感谢

注意事项:

    1.内存百分百到达85%以上,就不建议再继续往"雪藏"里面冻结游戏(进程), 可把虚拟内存调高一些.
    且不要各种开启新进程,与已经处于"雪藏"状态的进程争抢内存资源,它此时很脆弱....(当然,你可以挑战性能极限)
    2.网游类冻结会造成离线,请勿在摆摊,自动打怪等需要挂机的场景使用.(像永劫无间,不想玩了可以冻住,想玩解冻重连即可,其他游戏待各位自行尝试.)
    3.冻结操作属于高权限操作, 需要进行各种线程的精细附加才能达到最理想的效果,非简单无脑粗暴的挂起(这样会各种bug), 所以也许某些软件会阻止相关操作,请关闭相关软件.(纯用来打游戏的掌机你装啥乱七八糟的管家?哈哈)
    4.如冻结\解冻的目标不在列表中,请点击"全局模式"进行搜索查找.
    5.我在新版本里会陆续加入忽略一些不必要冻结的进程名单,用户进行冻结操作后,如雪藏判定此项为非必要操作项(如服务,附属子进程等), 直接删除其列表项,不作响应,提升容错率.(玩游戏就玩游戏嘛,有些同学手贱好奇去冻个后台进程...导致系统(程序)崩溃还怪雪藏不稳定咧.)


总结: 以上,我反复提到 "碎片时间" ."资源调度"这些概念,你在没用雪藏之前, 可能没啥感觉, 一旦你长期用下来你才能体会到其中的精妙之处,使用电脑的过程中,玩游戏的流畅度是一方面体验, 其实还有一个很重要的方面就是各种进程切换等待的体验,我们日常就觉得换个好的固态硬盘,增加读写效率,能提升这方面体验, 但其实,这个已经到了瓶颈,若干年前从机械到固态的升级,确实感受速度提升很明显,再往后就很难有质的飞跃了,这是程序io机制导致的,并不是读写瓶颈 ,就好像你买一台世界顶级的电脑,你想从A游戏进入到B游戏,你的硬盘和内存哪怕读写速率再快,常规流程操作下来,也远远比雪藏中的两个游戏间切换要慢的,这个已经超越比拼硬件性能的范畴,纯属机制上的降维打击. 这个工具你利用得当的话,会让你日常使用的过程中,感受到一种奇妙的体验,这个体验不是单纯堆硬件性能能堆出来的,堆硬件相当于是在琢磨怎么提升第一第二宇宙速度, 但雪藏像虫洞,空间跳跃...完全不是一个层面的感受, 其实我做这东西的初衷本来是方便我自己玩的,其实我用了快10年有余,习惯成自然,都快以为这个是大家都在用的东西了, 后来才发现并不是, ,后面想着如果把这个理念推广出去,能让硬件(软件)厂商,直接在游戏和系统上重视这块,那该多好,我也希望PC端也有能媲美游戏机那样的机制,我的大我理想,就是以后雪藏成为一款"多余的软件", 到那时候,我也非常欣慰了,至少,咱把一个不被人注意的的理念,推广成了普遍的共识, 这就像星星之火一样,可以燎原, 那句话咋说来着, 这世界上, 本没有路人走多了,就成路了,这需要大家的共同努力,发光发热,推进一些不起眼但实则非常重要的细节进步.   其实看到一些能马上get到雪藏亮点的小伙伴,很是欣慰,(每当我看到群里,评论区里有人说这个东西有啥用,我真是恨我表达能力有限,无法将这一理念普及给所有人,哪怕我已经对他进行各种深度优化,19分钟的2倍速视频都不能说清楚,哎哎,属实惭愧) . 大陌在此感谢能喜欢雪藏的各位. --咖喱阿多 玛玛哈哈.
