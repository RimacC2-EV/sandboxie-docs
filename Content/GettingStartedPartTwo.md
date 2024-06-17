# Getting Started Part Two

### Part Two: Run Web Browser

要启动你的网络浏览器，请在桌面上找到它的快捷方式：

![image](https://github.com/RimacC2-EV/sandboxie-docs/assets/125170682/724de545-50b5-4d2a-b19b-bc532889cdc3)

或者，右键单击 [Sandboxie Control](SandboxieControl.md) 托盘图标, 导航到 [托盘图标界面](TrayIconMenu.md) 并选择 _运行默认浏览器_ 选项。

![](../Media/TrayPopupMenu.png)

A third option is via the [Sandbox Menu](SandboxMenu.md) in the main window of Sandboxie Control:

![](../Media/SandboxMenu.png)

* * *

Your Web browser should come up _sandboxed_. You can tell that a program is sandboxed because its window title bar contains additional Sandboxie **[#]** indicators: ((NOTE: Newer browsers may not show the # in the title bar, however if you hover your mouse along the edges of the window, it will turn yellow.)

![](../Media/SandboxedTitle.png)

(Note: In some computer systems, Sandboxie starts the wrong program when you select _Run Web Browser_. If this is the case for you, see [Frequently Asked Questions](FrequentlyAskedQuestions.md#why-does-the-wrong-program-start-when-i-run-my-default-web-browser-sandboxed) to fix this.)

The sandboxed program should appear in the main window of [Sandboxie Control](SandboxieControl.md):

![](../Media/MainWindow.png)

The window displays the list of programs that are currently running _sandboxed_ under the supervision of Sandboxie. Initially there is just one sandbox, _DefaultBox_, however, more sandboxes can be created; see the [Create New Sandbox](SandboxMenu.md#create-new-sandbox) command in the [Sandbox Menu](SandboxMenu.md).

The picture above shows Sandboxie is running three programs. The first, _iexplore.exe_, stands for Internet Explorer, as this tutorial assumes Internet Explorer is the Web browser in use. If the default Web browser in your system is Firefox, or Opera, then you would see _firefox.exe_ or _opera.exe_, respectively, as the first program running in the sandbox.

The screenshot shows two more programs are running, **SandboxieRpcss.exe** and **SandboxieDcomLaunch.exe**. These support programs are part of Sandboxie. If they are needed, they will be automatically started, without any explicit action on your part. See [Service Programs](ServicePrograms.md).

When Sandboxie is actively running programs in any of the sandboxes, the Sandboxie tray icon (at the corner of the screen) displays red dots: ![](../Media/TrayIconFull.png)

* * *

The tutorial continues in [Getting Started Part Three](GettingStartedPartThree.md).
