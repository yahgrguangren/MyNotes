2024-03-22

WinGet 是微軟最新推出的套件管理器，專為 Windows 用戶提供簡單、快速的軟體安裝和管理方式。通過強大的命令列界面，用戶可以輕鬆搜索、安裝、更新和卸載軟體，省去了繁瑣的手動操作步驟。WinGet 還支持自定義軟體源和自動解決依賴關係，為用戶帶來了更大的靈活性和便利性。無論你是軟體開發者、程式設計師，還是普通的電腦用戶，WinGet 都能滿足你對軟體管理的各種需求。WinGet 是一款實用而強大的工具，讓 Windows 用戶的軟體管理變得更加輕鬆愉快。

winget是一个指令集，所以先要打开终端机。
1、看看winget版本
winget --version
2、更新winget
https://github.com/microsoft/winget-cli/releases
下载最新版，在Microsoft.DesktopAppInstaller_8wekyb3d8bbwe.msixbundle
链接上点击右键，复制链接
回到命令窗口，输入Add-AppxPackage -Path Microsoft.DesktopAppInstaller_8wekyb3d8bbwe.msixbundle
3、搜寻软件
winget search RaiDrive
winget install Mozilla.firefox
4、搜寻软件
winget search 'python 3.10' 如果没有找到，则再输入winget show python.python.3.10 --version 列出所有3.10的版本
输入winget install Python.python.3.10.6 -v 3.10.6
5、winget list 列出目前已安装的应用程序
6、检查程序有没有新的更新版本就输入 winget upgrade
7、输入winget upgrade --all 更新所有程序
8、输入winget upgrade 程序名称或识别码，可以更新具体软件。
9、不想自动升级某个程序，就输入winget pin add 程序的识别码
例如：winget pin add python.python.3.10
10、要取消上面的钉选就输入winget pin remove python.python.3.10
11、输入winget pin add python.python.3.10. --blocking 则直到取消钉选才能升级更新
12、卸载程序输入winget uninstall 程序名称或识别码
例如winget uninstall firefox
13、要了解winget某个指令（例如uninstall）的选项，就输入
winget uninstall -?
14、输出已经安装的软件清单，用于在重新安装系统后安装程序
winget export -o C:\Users\yahgr\apps.json
15、winget import -i C:\Users\yahgr\apps.json就可以重新安装程序

