# Xcode翻译

```text
  !一级目录    @二级目录   #三级目录   $四级目录   %五级目录   ^六级目录 
							3TAB		5TAB		7TAB		9TAB
查看 Xcode Help 帮助是最好的办法
生成和调试文件都在  /Users/ns/Library/Developer/Xcode/DerivedData/Products
mac for : Welcome to Xcode 一级窗口界面翻译:____________________________

	Get started with a playground.
Explore new ideas quickly and easily.
// 创建 Swift 代码开发环境(苹果的编程语言).
// 快速轻松的探索新想法.
// 只适用于 ios 开发

*	Create a new Xcode projcet.
Create an app for iphone , ipad ,Mac Apple,Watch or Apple TV.
// 创建一个新的Xcode项目。
// 为iphone、ipad、Mac Apple、Watch或Apple TV开发一个应用程序。
// 这个可以创建所有语言的工作环境. C C++ Java 之类的

*	Clone an existing project.
Start working on something from an SCM repository.
// 克隆一个现有的项目.
// 开始从 SCM 存储库着手处理一些东西.

Show this window when Xcode launches.
// 当Xcode 启动时显示此窗口.

Open another project...
// 打开另一个项目.
___________________________________________________________________________
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
//////////////////////////////////////////////////////////////////////////
创建模版的介绍:
{
@@	点击第一个创建 IOS 模版后
		Choose a template for your new playground: <选择一个模版>
			包括 ios  tvOS  macOS ,但是仅限于 ios 的项目开发.
		
		Application <应用程序>
			包括 Blank  Game  Map  Single View 
				 空白   游戏  地图  单一视图

##	点击第二个创建 所有语言程序 模版后{___
$$			可以创建的应用有:
				IOS 应用程序
				Single View App  <单一视图应用程序>
				Augmented Reality App  <增强现实应用.就是 AR 应用>
				Document Based App  <基于文档的应用程序>
				Master-Detail App  <主从复合结构的应用>
				Page-Based App  <页面程序应用>
				Tabbed App  <标签的应用>
				Sticker Pack App  <贴纸包装应用>
				iMessage App  <短信应用>
$$			可以创建 Framework & Library <框架和库>:
				Cocoa Touch Framework  <通用触摸框架>
				Cocoa Touch Static Library  <通用静态库>
				Metal library  <金属库>

##	点击 macOS 项目后可以创建:
$$			可以创建的应用有:
				Command Line Tool  <命令行工具>
$$			可以创建的 框架和库:
				Cocoa Framework  <Cocoa 框架>
				XPC Service  <XPC 服务>
				Bundle  <包>
$$			可以创建的 Other  <其他> 内容:
				AppleScript App  <苹果脚本应用>
				Automator Action  <自动动作>
				Contacts Action Plug-in  <交互式行动插件>
				Installer Plug-in  <安装插件>
				IOKit Driver  <IOKit 驱动程序>
				Preference Pane  <首选项面板>
				Quartz Composer Plug-in  <石英复合插件>
				Quick Look Plug-in  <快速浏览插件>
				Screen Saver  <屏幕保护程序>

}

\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
///////////////////////////////////////////////////////////////////////////
!! 主界面.菜单栏翻译:

	Xcode  <Xcode>
	File   <文件>
	Edit   <编辑>
	View   <视图>
	Find   <查找>
	Navigate  <导航>
	Editor  <编辑器>
	Product <产品>
	Debug   <调试>
	Source control  <控制源>
	Window  <窗口>
	Help  <帮助>

***** 菜单栏二级及以下选项翻译 ******
@@ Xcode <Xcode> 下的目录:
{
	About Xcode  <关于 Xcode>
	Preferences...  <首选项>
##	Behaviors  <行为>{___
			No Custom Behaviors  <无自定义行为>
			Edit Behaviors...  <编辑行为>
			}
	Xcode Server...  <Xcode 服务器>
##	Open Developer Tool  <开放的开发工具>{___
			Instruments  <仪器>
			Simulator  <模拟器>
			Accessibility Inspector  <可访问性检查>
			FileMerge  <文件合并>
			Application Loader  <应用程序加载器>
			More Developer Tools..  <更多的开发人员工具>
			}
##	Services  <服务>{___
			No Services Apply  <没有服务应用>
			Services Preferences...  <服务首选项>
			}
	Hide Xcode  <隐藏 Xcode>
	Hide Others  <隐藏其他应用窗口>
	Show All  <显示所有窗口>
	Quit Xcode  <退出 Xcode>
}

///////////////////////////////////////////////////////////////////////////
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

@@ File <文件> 下的目录:
{
##	New  <新建>{___
			Tab  <新建 选项卡>
			Window  <新建 窗口>
			File...  <新建 文件>
			Playground...  <新建 Swift 开发环境>
			Target...  <在项目中新建一个项目,相当于一项目包含两个项目的文件>
			Project...  <新建 项目>
			Workspace...  <新建 工作空间>
			Group  <新建 组>
			Group without Folder  <新建 无文件夹的组>
			Group from Selection  <新建 选择组>
			}
	Add Files to "项目名"  <为这个项目引入新文件>
	Open...  <打开文件>
##	Open Recent  <打开最近打开过的项目或工作组>{___
			"文件名"  <我曾经打开过的文件>
			Clear Menu  <清除打开过的文件记录>
			}
	Open Quickly...  <通过搜索快速打开一个文件>
	Close Window  <关闭窗口>
	Close Tab  <关闭选项卡>
	Close "文件名"  <关闭某个文件>
	Close Workspace  <关闭工作空间>
	Save  <保存文件>
	Duplicate...  <复制文件>
	Revert to Saved...  <将文件的修改直接回退到上次保存时>
	Unlock...  <要对第三方库或系统文件进行修改时解锁>
	Show in finder  <在文件中打开.通过访达打开>
	Open with External Editor  <使用外部编辑器打开>
	Save As Workspace...  <工作组 另存为>
	Workspace Settings..  <工作区设置>
	Page Setup...  <打印机.页面设置>
	Print...  <用打印机打印当前文件>
}

///////////////////////////////////////////////////////////////////////////
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

@@ Edit <编辑> 下的目录:
{
	Undo Typing  <撤销>
	Redo Typing  <反撤销>
	Cut  <剪切>
	Copy  <拷贝>
	Paste  <粘贴>
	Special Paste  <特殊的粘贴>
	Paste and Preserve Formatting  <粘贴并匹配样式>
	Duplicate  <复制.不等同于拷贝>
	Delete  <删除>
	Select All  <全选>
##	Filter  <筛选,可以选择在导航栏中筛选和在库中筛选>{___
			Filter in Navigator  <在导航栏中筛选>
			Filter in Library  <在库中筛选>
			}
##	Sort  <排序>{___
			By Name  <根据名字排序>
			By Type  <根据类型排序>
			}
##	Format  <格式>{___
			Show Fonts  <显示字体,修改字体>
			Show Colors <显示颜色,字体高亮颜色之类的>
$$			Font  <字体>{___
					Bold  <粗体>
					Italics  <斜体字>
					Underline  <下划线>
					Outline  <轮廓>
					Show Styles...  <显示样式..>
					Bigger  <更大的>
					Smaller  <更小的>
%%				%%	Kern  <字体>{___
						Use Default  <使用默认>
						Use None   <使用无设置>
						Tighten  <收缩>
						Loosen  <松开>
						}
%%				%%	Ligatures  <绑扎>{___
						Use Default  <使用默认>
						Use None	<使用没有>
						Use All  <使用所有>
						}
%%				%%	Baseline  <基线>{___
						Use Default  <使用默认>
						Superscript  <上标>
						Subscript  <下标>
						Raise  <较高的>
						Lower  <较低的>
						}
					Copy Style  <复制的风格>
					Paste Style  <粘贴风格>
					}
$$			Text  <文本,可以更改页面文本>{___
					Align Left  <左对齐>
					Center  <中心>
					Justify  <证明>
					Align Right  <右对齐>
%%				%%	Writing Direction  <书写方向>{___
							Paragraph  <段落>
							  Default  <默认的>
							  Left to Right  <从左到右>
							  Right to Left  <从右到左>
							Selection  <选择>
							  Default  <默认的>
							  Left to Right  <从左到右>
							  Right to Left  <从右到左>
							}
					Show Ruler  <显示标尺>
					Copy Ruler  <复制标尺>
					Paste Ruler  <粘贴标尺>
					}
$$			Spelling and Grammar  <拼写提示和语法提示>{___
					Show Spelling and Grammar  <显示拼写和语法>
					Check Document Now  <现在检查文档>
					Chack Spelling While Typing  <打字时拼写错误>
					Check Grammar With Spelling  <用拼写检查语法>
					Correct Spelling Automatically  <自动拼写正确>
					}
$$			Substitutions  <替换>{___
					Show Substitutions  <显示替换>
					Smart Copy/Paste  <智能拷贝/粘贴>
					Smart Quotes  <智能报价>
					Smart Dashes  <智能破折号>
					Smart Links  <智能链接>
					Data Detectors  <数据探测器>
					Text Replacement  <文本替换>
					}
$$			Transformations  <转换>{___
					Make Upper Case  <变成大写字母>
					Make Lower Case  <变成小写字母>
					Capitalize  <单词中的第一个字母大写>
					}
$$			Speech  <开始说话,结束说话>{___
					Start Speaking  <开始说话>
					Stop Speaking	<停止说话>
					}
##	Refactor  <重构>{___
					Rename  <重命名>
			        Extract  <提取>
			        Create Superclass  <创建超类>
			        Move Up  <上移>
			        Move Down  <下移>
					}
##	Convert  <转换成ARC,swift等的语法>{___
			To Current Swift Syntax...  <目前流行的语法>
			To Modern Objective-C Syntax...  <到现代 对象-c管理内存 语法>
			To Objective-C ARC  <对象-c 管理内存语法>
			}
	Encapsulate  <封装>
	Start Dictation...  <开始听写>
	Emoji & Symbols  <表情和特殊符号>
}

///////////////////////////////////////////////////////////////////////////
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

@@ View <视图> 下的目录:
{
##	Standard Editor  <标准模块.编辑器>{___
			Show Standard Editor  <显示标准编辑器>
			Show Related Items  <显示相关项目>
			Show Previous Files History  <显示之前的文件历史记录>
			Show Next Files History  <显示下一个文件的历史记录>
			Show Top Level Items  <展示顶级项目>
			Show Group Files  <显示组文件>
			Show Document Items  <显示文件内容>
			}
##	Assistant Editor  <助理模块.编辑器>{___
			Show Assistant Editor  <显示助理编辑器>
			Add Assistant Editor  <添加辅助编辑器>
			Remove Assistant Editor  <删除助理编辑器>
			Reset Editor  <重制编辑器>
			Assistant Editors on Right  <右侧编辑助理>
			Assistant Editors on Bottom  <底部编辑助理>
			All Editors Stacked Horizontally  <所有编辑器水平堆叠>
			All Editors Stacked Vertically  <所有编辑器垂直堆叠>
			}
##	Version Editor  <版本模块.编辑器>{___
			Show Version Editor  <显示版本编辑器>
			Show Comparison View  <显示比较视图>
			Show Authors View  <显示作者视图>
			Show Log View  <显示日志视图>
			}
##	Navigators  <导航模块.主界面左边8个导航模块的切换>{___
			Show Project Navigator  <显示项目导航>
			Show Source Control Navigator  <显示源代码控制导航>
			Show Symbol Navigator  <显示符号导航>
			Show Find Navigator  <显示查找导航>
			Show Issue Navigator  <显示问题导航>
			Show Test Navigator  <显示测试导航>
			Show Debug Navigator  <显示调试导航>
			Show Breakpoint Navigator  <显示断点导航>
			Show Report Navigator  <显示报表导航>
			Hide Navigator  <隐藏导航>
			}
##	Debug Area  <调试区域模块.主界面中下部调试框和打印输出框>{___
			ACtivate Console  <激活控制台>
			Hide Debug Area  <隐藏调试区域>
			}
##	Utilities  <查看使用程序.包括主界面右边上面两个选项和下面四个选项>{___
			Show File Inspector  <显示文件检查>
			Show Quick Help Inspector  <显示快速帮助>
			Show File Template Library  <显示文件模板库>
			Show Code Snippet Library  <显示代码片段库>
			Show Object Library  <显示对象库>
			Show Media Library  <显示媒体库>
			Hide Utilities  <隐藏实体工具>
			Hide Library  <隐藏库>
			}
	Hide Toolbar  <隐藏工具栏>
	Show Tab Bar  <显示标签栏>
	Show All Tabs  <显示所有选项卡>
	Enter Full Screen  <进入全屏>
}

///////////////////////////////////////////////////////////////////////////
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

@@ Find <查找> 下的目录:
{
	Find in Project...  <在项目中查找>
	Find and Replace in Project...  <在项目中查找和替换>
	Find Next in Project  <在项目中查找下一个>
	Find Previous in Project  <查找项目中的前一个>
	Find Selected Text in Project  <在项目中查找选定文本>
	Find Call Symbol in Project  <在项目中查找调用符号>
	Find in Selected Groups...  <在选定的区域中查找>
	Find ...  <查找>
	Find and Replace...  <查找和替换>
	Find Next  <查找下一个>
	Find Previous  <查找之前的>
	Replace  <替换>
	Replace All  <全部替换>
	Replace and Find Next  <替换并查找下一个>
	Replace and Find Previous  <替换并查找之前的>
	Hide Find Bar  <因此查找栏>
	Use Selection for Find  <使用选择查找>
	Use Selection for Replace  <使用替换查找>
}

///////////////////////////////////////////////////////////////////////////
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

@@ Navigate <导航> 下的目录:
{
	Reveal in Project Navigator  <在项目导航中显示此文件>
	Reveal in Symbol Navigator  <在符号导航中显示出某种方法>
	Reveal in Debug  Navigator  <在调试导航中显示>
	Open in Assistant Editor  <在辅助编辑器中打开>
	Open in ...  <你想怎么打开>
	Move Focus To Next Area  <把焦点移到下一个区域>
	Move Focus To Next Editor  <将焦点移动到下一个编辑器>
	Move Focus To Editor...  <将焦点移动到编辑器>
	Go Forward  <前进>
	Go Back  <后退>
	Jump to Selection  <跳转到选择>
	Jump to Definition  <跳转到定义>
	Jump to Original Source/Generated Interface  <跳转到源文件/生成接口>
	Jump to Next Issue  <跳转到下一个问题>
	Jump to Previous Issue  <跳转到上一个问题>
	Jump to Instruction Pointer  <跳转到指令指针>
	Jump to Previous Counterpart  <跳转到上一对应部分>
	Jump To...  <跳转到>
	Jump to Next Placeholder  <跳转到下一个占位符>
	Jump to Previous Placeholder  <跳转到上一个占位符>
}

///////////////////////////////////////////////////////////////////////////
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

@@ Editor <编辑器> 下的目录:
{
	Show Completions  <显示自动补全>
	Edit All in Scope  <在当前文件全文修改选中的一个变量或单词>
##	Refactor  <重构>{___
			Rename...  <重命名>
			Extract Function  <提取函数>
			Extract Method  <提取方法>
			Extract Variable  <提取变量>
			Extract All Occurrences  <提取所有出现次数>
			Add Missing Abstract Class Overrides  <添加缺少的抽象类覆盖>
			Add Missing Protocol Requirements  <添加缺少协议要求>
			Add Missing Switch Cases  <添加丢失的交换机案例>
			Convert To Switch  <转换为切换>
			Expand Default  <展开默认值>
			Generate Missing Function Definitions  <生成缺失函数定义>
			Wrap In NSLocalizedString  <封装在 .strings 文件中>
			}
	Fix All Issues  <自动解决它能解决的error警告>
	Show Issues  <显示所有错误和隐藏错误>
##	Issues  <错误>{___
			Show All Issues  <显示所有问题>
			All Issues  <所有错误>
			Errors Only  <仅显示错误>
			}
	Select Structure  <选择结构>
##	Structure  <构造>{___
			Balance Delimiter  <直接选中光标所在的整个大括号>
			Re-Indent  <将格式缩进整理一下>
			Shift Right  <向右移动一个 tab 的距离>
			Shift Left  <向左移动一个 tab 的距离>
			Move Line Up  <向上移动一行>
			Move Line Down  <向下移动一行>
			Toggle Comments  <注释和取消 选择以及光标所在行>
			Add Documentation  <在当前位置添加一个注释>
			}
##	Code Folding   <提供代码堆叠和取消堆叠>{___
			Fold  <折叠>
			Unfold  <展开>
			Unfold All  <展开所有>
			Fold Methods & Functions  <折叠模式和函数>
			Unfold Methods & Functions  <展开模式和函数>
			Fold Comment Blocks  <折叠注释块>
			Unfold Comment Blocks  <展开注释块>
			}
##	Syntax Coloring  <设置各个语法的高亮配色>{___
			Default for File Type  <默认文件类型>
			AppleNone  <苹果的脚本>
			ARM-Assembly  <ARM类型>
			C
			C++
			XML   (各种开发类型)
			}
##	Font Size  <字体大小设置>{___
			Increase  <增大字体>
			Decrease  <减小字体>
			Reset  <重置大小>
			}
##	Theme  <主题>{___
			Basic  <基本>
			Civic  <思域>
			Default  <默认>
			Dusk  <黄昏>
			Low Key  <低调>
			Midnight  <午夜>
			Presentation  <演讲>
			Presentation Large  <演示文稿大主题>
			Printing  <印刷主题>
			Sunset  <日落>
			Edit Themes...  <编辑主题>
			}
	Show Invisibles  <显示所有隐藏的东西.比如空格>
	Hide Whitespace  <隐藏空白>
	Copy Source Changes  <复制源代码更改>
	Revert Selected Difference  <回复选定区域的上一个版本>
	Don`t Commit Selected Difference  <你还没有进行修改>
	Show Blame for Line  <显示选中的行的修改者和Log>
	Show Code Coverage  <展示代码的覆盖范围>
}

///////////////////////////////////////////////////////////////////////////
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

@@ Product <产品> 下的目录:
{
	Run  <运行>
	Test  <测试>
	Profile  <配置文件>
	Analyze  <分析.可以检测一些不规范的 OC 语法>
	Archive  <存档>
##	Build For <为...编译>{___
			Running  <运行>
			Testing  <测试>
			Profiling  <分析>
			}
##	Perform Action  <执行动作>{___
			Run Without Building  <不生成运行>
			Test Without Building  <不生成测试>
			Profile Without Building  <不生成测试文件>
			Test  <测试>
			Test Again  <再次测试>
			Profile  <描述>
			Profile Again  <再次描述>
			Compile "文件名"  <编译该文件>
			Analyze "文件名"  <分析该文件>
			Generate Optimization Profile...  <生成优化概要文件>
			}
	Build  <编译>
	Clean  <清理一下之前编译的缓存>
	Stop  <停止>
##	Scheme  <方案>{___
			Select Next Scheme  <选择下一个方案>
			Select Previous Scheme  <选择上一个方案>
			"已经生成的文件.out"  <已经生成的运行方案>
			Edit Scheme...  <编辑方案>
			New Scheme...  <新方案>
			manage Schemes...  <管理计划>
			}
##	Destination  <生成位置>{___
			Select Next Destination  <下一个位置>
			Select Previous Destination  <上一次使用的位置>
			My MAC  <我的苹果电脑>
			}
	Create Bot...  <创建自动化>
}

///////////////////////////////////////////////////////////////////////////
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

@@ Debug <调试> 下的目录:
{
	Pause  <暂停和继续>
	Continue To Current Line  <走到光标选中的这行>
	Step Over  <跳过>
	Step Into  <进入>
	Step Out  <跳出>
	Step Over Instruction  <跨过指示>
	Step Over Thread  <跨过单步线程>
	Step Into Instruction  <步进指令>
	Step Into Thread  <单步执行线程>
	Capture GPU Frame  <捕捉GPU框架>
	Capture GPU Scope  <捕捉GPU范围>
	Gpu OVerrides  <GPU 覆盖>
##	Simulate Location  <模拟定位>{___
			Don`t Simulate Location  <不要模拟位置>
			London,England  <英国伦敦>
			Johannesburg,South Africa  <内飞约翰内斯堡>
			Moscow,Russia  <莫斯科,俄罗斯>
			Mumbai,India  <印度孟买>
			Tokyo,Japan  <日本东京>
			Sydney,Australia  <澳大利亚悉尼>
			Hong Kong,China  <中国香港>
			Honolulu,USA  <美国檀香山>
			San Francisco,CA,USA  <旧金山,加州,美国>
			Mexico City,Mexico  <墨西哥城,墨西哥>
			New York,NY,USA  <纽约,美国>
			Rio de Janeiro,Brazil  <巴西热内卢>
			Add gpX File to Project...  <向项目添加位置文件>
			}
	Simulate Background Fetch  <模拟后台提取.让模拟器去后台>
	Simulate UI Snapshot  <模拟用户界面快照>
##	iCloud  <苹果云相关>{___
			Trigger Sync in Simulator  <触发操作同步到模拟器>
			Delete Container Contents  <删除容器的内容>
			}
##	View Debugging  <查看视图调试>{___
			Take Screenshot of Active Device  <拍摄活动设备的截图>
			Capture View hierarchy  <捕捉视图层次>
			Show View Frames  <显示视图框架>
			Show Alignment Rectangles  <显示对齐矩形>
			Show View Drawing  <显示视图绘制>
			Show Responsive Scrolling Status  <显示响应滚动状态>
$$		$$	Rendering  <致使>{___
					Color Blended Layers  <颜色混合层>
					Color Hits Green and Misses Red  <变成绿色而不是红色>
					Flash Updated Regions  <flash  更新区域>
					}
	Deactivate BreakPoints  <停用中断点>
##	Breakpoints  <增加各种断点.相当于左下角的加号>{___
			Add Breakpoint at Current Line  <在当前行添加断点>
			Create Swift Error Breakpoint  <创建快速错误断点>
			Create Exception Breakpoint...  <创建异常断点>
			Create Symbolic Breakpoint...  <创建符号断点>
			Create Test Failure Breakpoint  <创建测试失败的断点>
			}
##	Debug Workflow  <可以显示内存和清理打印等操作>{___
			Always Show Disassembly  <总是显示拆卸>
			Shared Libraries...  <共享库>
			View Memory  <查看内存>
			Clear Console  <清除控制台>
			Reload Console  <重载控制台>
			}
	Attach to Process by PID or Name...  <设置权限ID或name.连接到进程>
##	Attach to Process  <附加到进程.连接到过程>{___
			Likely Targets  <调试的目标>
			file(3333)(already being debugged) <文件编号.(已经调试)>
			Applications  <应用程序>
			  <全部都是已经安装的应用>
			system  <系统程序>
			  <全部都是系统应用(包括vim)之类的>
			}
	Detach from "被调试文件"  <删除被调试文件>
	}

///////////////////////////////////////////////////////////////////////////
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

@@ Source control <控制源> 下的目录:
{
	Commit...  <提交>
	Push...  <上传代码>
	Pull...  <拉取代码>
	Fetch and Refresh Status  <获取和更新状态>
	Discard All Changes...  <放弃所有修改>
	Add Selected Files  <添加选定文件>
	Discard Changes in "文件"...  <丢弃 “文件”中的修改 >
	Mark Selected Files as Resolved  <将选定文件标记为已解决>
	Create Git Repositories...  <创建Git 存储库>
	Clone...  <克隆>
}

///////////////////////////////////////////////////////////////////////////
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

@@ Window <窗口> 下的目录:
{
	Minimize  <最小化>
	Zoom  <放大窗口或缩小窗口>
	Rename Tab...  <重命名选项卡>
	Show Previous Tab  <切换到上一个选项卡>
	Show Next Tab  <切换到下一个选项卡>
	Move Tab To New  Window  <将选项卡移动到新窗口>
	Merge All Windows  <合并所有的窗口>
	Developer Documentation  <打开开发者文档>
	Welcome to Xcode  <打开起始页>
	Devices and Simulators  <设备和模拟器>
	Organizer  <打开可以看到 Archives档案 和 Crashes崩溃>
	Show Touch Bar  <显示触摸栏>
	Bring All to Front  <把所有xcode打开文件的都前置>
}

///////////////////////////////////////////////////////////////////////////
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

@@ Help <帮助> 下的目录:
{
	Search  <在目录中搜索功能>
	Developer Documentation  <开发人员文档>
	API Changes  <API的变化>
	Xcode Help  <Xcode 的帮助>
	What`s New in Xcode  <有什么新特性>
	Release Notes  <发布说明>
	Report an Issue  <报告一个问题>
	Show Quick Help for Selected Item  <显示选定项目的快速帮助>
	Search Documentation for Selected Text  <详细帮助.直接在文档里找这个>
}

```

