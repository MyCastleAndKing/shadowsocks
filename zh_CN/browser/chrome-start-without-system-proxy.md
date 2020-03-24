**您需要首先设置好代理客户端，然后确保 Chrome 已经完全退出。**


1. Windows 用户按 Win+R 打开运行窗口，输入 `cmd` 回车后打开命令提示符窗口。 macOS 用户在应用程序中搜索打开 终端( Terminal) 程序

2. 复制粘贴下面的内容到命令窗口后回车即可在代理模式下启动 Chrome，使用命令前请确认 Chrome 已完全退出。

Windows 用户：
```
"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --proxy-server="socks5://127.0.0.1:1080"
macOS 用户（请注意客户端的 socks 监听端口需要设置为 1080）：
```

macOS 用户（请注意客户端的 socks 监听端口需要设置为 1080）：
```
/Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome  --proxy-server="socks5://127.0.0.1:1080"
```

3. 然后可以打开 https://www.google.com/ 测试或是访问 https://ip.sb 以及 https://www.ipip.net/ip.html 查看自己的 IP 状态。

注：如果可以打开 Google 则表示成功设置了代理，这样设置是一次性的，关闭后就不再影响正常使用。


上面命令提供的是最新版本 Chrome 的默认安装路径，如果输入后提示 `不是内部或外部命令，也不是可运行的程序或批处理文件`。

说明路径不正确，请按照下面的提示找到 Chrome.exe 的路径，然后替换对应的内容（替换引号内部的内容，引号需要保留）

```
"这里替换为 Chrome.exe 的路径" --proxy-server="socks5://127.0.0.1:1080"
```
在 Chrome 的快捷方式上右键，点击菜单中的属性。（如果是 Windows 的任务栏图标，请按住 Shift 后再点击右键）
在弹出的窗口中，找到目标一栏，即可复制对应的 Chrome.exe 的路径。
